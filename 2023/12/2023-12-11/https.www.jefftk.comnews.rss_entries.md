# Source:Jeff Kaufmann, URL:https://www.jefftk.com/news.rss, language:en-US

## Implicitly Typed C
 - [https://www.jefftk.com/p/implicitly-typed-c](https://www.jefftk.com/p/implicitly-typed-c)
 - RSS feed: https://www.jefftk.com/news.rss
 - date published: 2023-12-11T08:00:00+00:00

<p><span>

I don't know any good reason to do this, but if you would rather be
writing Python or JavaScript here's something you can do with a C
compiler:

</span>

<p>

</p>

<pre>
$ cat tmp.c
foo(x) {
  return x+5;
}
bar() {
  return 4;
}
main() {
  printf("%d\n", foo(bar()));
}

$ gcc -w -o tmp.out tmp.c &amp;&amp; ./tmp.out
9
</pre>



<p>

This code takes advantage of a historical quirk of C where types are
assumed to be <code>int</code> unless otherwise specified:
<code>foo(x) {...}</code> is equivalent to <code>int foo(int x)
{...}</code>. Additionally the <code>printf</code> works because gcc
includes <code>stdio.h</code> by default, and <code>main</code> is
special-cased to assume a final <code>return 0</code>.

</p>

<p>

I've occasionally used this style when writing <a href="https://www.jefftk.com/p/a-function-that-returns-twice-fork">example code</a> to
remove visual noise, but it's probably not a good idea there either.

  </p>

<p><i>Comment via: <a href="https://www.f


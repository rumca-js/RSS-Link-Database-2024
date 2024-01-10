# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## How to Print Unicode Text to the Windows Console in C++ -- Giovanni Dicanio
 - [https://isocpp.org//blog/2024/01/how-to-print-unicode-text-to-the-windows-console-in-cpp-giovanni-dicanio](https://isocpp.org//blog/2024/01/how-to-print-unicode-text-to-the-windows-console-in-cpp-giovanni-dicanio)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-01-09T18:34:03+00:00

<p>
	Have you ever wondered how to correctly print Unicode text to the Windows console in your C++ programs? Maybe you tried something, and you got meaningless output, or even an assertion failure at runtime, pointing to some obscure code in the CRT? Well, then this article is for you!</p>
<blockquote>
	<h3>
		<a href="https://giodicanio.com/2023/06/01/how-to-print-unicode-text-to-the-windows-console-in-c-plus-plus/">How to Print Unicode Text to the Windows Console in C++</a></h3>
</blockquote>
<blockquote>
	<p>
		by Giovanni Dicanio</p>
</blockquote>
<p>
	From the blog post:</p>
<blockquote>
	<p>
		Suppose that you want to print out some <strong>Unicode text</strong> to the Windows console. From a simple C++ console application created in Visual Studio, you may try this line of code inside main:</p>
	<pre class="prettyprint lang-cpp">
std::wcout &lt;&lt; L"Japan written in Japanese: x65e5x672c (Nihon)n";</pre>
	<p>
		As you can see, the Japanese kanjis are <em>not printed</em>. More

## Breaking Down C++20 Callable Concepts -- John Farrier
 - [https://isocpp.org//blog/2024/01/breaking-down-cpp20-callable-concepts-john-farrier](https://isocpp.org//blog/2024/01/breaking-down-cpp20-callable-concepts-john-farrier)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-01-09T17:55:28+00:00

<p>
	Learn about C++20's Callable Concepts, how they improve on SFINAE, and how to use them in your own code.</p>
<blockquote>
	<h3>
		<a href="https://johnfarrier.com/breaking-down-c20-callable-concepts/">Breaking Down C++20 Callable Concepts</a></h3>
	<p>
		By John Farrier</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		C++20 Callable Concepts refer to a powerful feature introduced in the C++20 standard that allows developers to specify and enforce constraints on function objects, lambdas, and other callable entities in a more expressive and type-safe manner. Callable Concepts enable the compiler to check if a given callable meets specific requirements, such as having certain member functions or satisfying particular type traits, before allowing it to be used in a template or function. This helps improve code readability, maintainability, and error detection, as it provides clearer and more structured ways to define the expected behavior and capabilities of callabl

## Easily Protect Your C++ Code Against Integer Overflow With SafeInt -- by Giovanni Dicanio
 - [https://isocpp.org//blog/2024/01/easily-protect-your-cpp-code-against-integer-overflow-with-safeint-by-giova](https://isocpp.org//blog/2024/01/easily-protect-your-cpp-code-against-integer-overflow-with-safeint-by-giova)
 - RSS feed: https://isocpp.org/blog/rss/category/news
 - date published: 2024-01-09T17:54:07+00:00

<p>
	Integer overflows can be hidden inside your C++ code and can cause subtle nasty bugs.</p>
<p>
	Fortunately, it's easy to guard your code against those subtle bugs, thanks to an open-source easy-to-use library:</p>
<blockquote>
	<h3>
		<a href="https://giodicanio.com/2023/11/13/protecting-your-c-plus-plus-code-against-integer-overflow-made-easy-by-safeint/">Protecting Your C++ Code Against Integer Overflow Made Easy by SafeInt</a></h3>
</blockquote>
<blockquote>
	<p>
		by Giovanni Dicanio</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		In previous blog posts I discussed the problem of integer overflow and some subtle bugs that can be caused by that. (...)</p>
	<p>
		Of course, writing this kind of complicated check code each time there is a sum operation that could potentially overflow would be excruciatingly cumbersome, and bug prone! (...)</p>
	<p>
		Fortunately, you don&rsquo;t have to do all that work! In fact, there is an open source library that does exactl


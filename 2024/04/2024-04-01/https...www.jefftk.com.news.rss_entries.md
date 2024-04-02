# Source:Jeff Kaufmann, URL:https://www.jefftk.com/news.rss, language:en-US

## Pluck Sensor Circuit
 - [https://www.jefftk.com/p/pluck-sensor-circuit](https://www.jefftk.com/p/pluck-sensor-circuit)
 - RSS feed: https://www.jefftk.com/news.rss
 - date published: 2024-04-01T08:00:00+00:00

<p><span>

A </span>

<a href="https://www.jefftk.com/p/mandolin-harp-sensor-placement">while
ago</a> I finished the "user interface" portion of my electronic harp
mandolin.  I'm 

<a href="https://www.jefftk.com/p/prototyping-pluck-sensors">happy with
the signals</a> the piezos put out, but now I need some electrical
engineering to get the signals into a computer where I'll be more at
home.



<p>

Since I made a design with 13 piezos, I wanted something with at least
that many analog to digital converters, and decided on the <a href="https://www.pjrc.com/store/teensy40.html">Teensy 4.0</a> with
14.  It turns out that this only has ten easily accessible ADCs,
though, and in retrospect the <a href="https://www.pjrc.com/store/teensy41.html">4.1</a> would have
been a better choice.  More on that later!

</p>

<p>

Reading the docs, each ADC pin converts an input voltage between 0 and
+3.3v into a number between 0 and 1023.  The piezo puts out voltages
centered on zero, and not guarantee


Download Link: https://assignmentchef.com/product/solved-assignment-1-operating-system-concepts
<br>
In Section 2.3, the textbook describes a program that copies the contents of one file to a destination file. This program works by first prompting the user for the name of the source file and destination files. Write this program using an API of your choice, either Windows API, POSIX API, of Java API; though, I prefer that you use the POSIX API. Be sure to include all necessary error checking, including ensuring that the source file exists.




The system-call sequence for this program (which copies the contents a source file to the destination file) is shown below.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/02/153.png?w=980&amp;ssl=1" class="aligncenter lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" class="aligncenter" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/02/153.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>One you have correctly designed and tested the program, if you used system that supports it, run the program using a utility that traces system-calls. Linux systems provide the <strong><em>strace</em></strong> utility, and Solaris and Mac OS X systems use the <strong><em>dtrace</em></strong> command. As Windows systems do not provide such features, you will have to trace through the Windows version of this program using a debugger.
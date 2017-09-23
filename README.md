Copy, Past & the Terminal
=========================

Please try [the demo site](https://nudin.github.io/copy-paste-and-the-terminal/copypaste.html)!

When coping something from a Webbrowser (or any other untrusted source) to your terminal you might end up executing code without your knowledge. 

To prevent this:
* update to readline 7.0+
* add the following line to you `~/.inputrc`

    set enable-bracketed-paste On
 
Dokumentation of [enable-bracketed-paste](https://cnswww.cns.cwru.edu/php/chet/readline/rluserman.html#SEC10).

## design principles

* Non-blocking I/O
    - every I/O call must take a callback. <!-- .element: class="fragment" -->

* Built-in support for the most important protocols <!-- .element: class="fragment" -->
    * HTTP, DNS, TLS <!-- .element: class="fragment" -->

* Low-level. <!-- .element: class="fragment" -->
    * Do not remove functionality present at the POSIX layer. <!-- .element: class="fragment" -->

* Stream everything; never force the buffering of data. <!-- .element: class="fragment" -->

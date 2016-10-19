## iframe inception
Demonstrates a recursive scenario in which a webpage loads an iframe pointing at itself. Browsers will prevent this behavior when the urls match. In this case, the iframe's src is set to `"/iframe-inception"` which resolves to `"/iframe-inception/`" (with a trailing slash). This disparity between the routes allows for the (infinite) recursion.

A sane, max-depth of 12 recursions has been set to prevent your browser from crashing. Beware!

#### Screenshot:

<img width="465" alt="iframe inception screenshot" src="https://cloud.githubusercontent.com/assets/1489337/19500741/de4877b2-9554-11e6-889e-d3a46717f707.png">

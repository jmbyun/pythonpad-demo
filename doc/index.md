# Pythonpad: Demo

Pythonpad is a JavaScript-based python programming environment that supports users to work on hands-on programming exercises with GUI and File I/O on static websites using Python code.

Pythonpad supports users to edit and run Python 3.7 code on static websites based on customized [Brython](http://brython.info/). User's code snippets are transpiled to JavaScript code on the web browser for execution, and tiny on-memory file system supports basic file i/o tasks on the environment. External servers are not needed.

However, accepting standard input in runtime is not supported since there is no equivalent blocking function available in web worker environment of JavaScript. To mitigate this issue, Pythonpad supports standard input in runtime when an external proxy server is available. In this case, one server on the smallest VM in AWS can handle more than 100,000 concurrent users in theory.

## Examples

Say "hello world" with Pythonpad.

<iframe src="/pad.html?embed=1&title=Hello world&p=hello-world.json" frameborder="0" width="840" height="480"></iframe>

<a href="/pad.html?title=Hello world&p=hello-world.json" target="_blank">
  Open in new window
</a>


### CS1Robots

Pythonpad supports RUR-PLE inspired cs1robots library (originally written by [Otfried Cheong](http://otfried.org/)).

<iframe src="/pad.html?embed=1&title=Robot: Example&p=robot-intro.json" frameborder="0" width="840" height="480"></iframe>

<a href="/pad.html?title=Robot: Example&p=robot-intro.json" target="_blank">
  Open in new window
</a>

### CS1Media

Pythonpad supports cs1media library for manipulating images (originally written by [Otfried Cheong](http://otfried.org/)).

<iframe src="/pad.html?embed=1&title=Media: Example&p=media-intro.json" frameborder="0" width="840" height="480"></iframe>

<a href="/pad.html?title=Media: Example&p=media-intro.json" target="_blank">
  Open in new window
</a>

### CS1Graphics

Pythonpad supports cs1graphics library for drawing and manipulating objects on a canvas (originally written by [Michael H. Goldwasser and David Letscher](https://dl.acm.org/doi/10.1145/1597849.1384369)). 

<iframe src="/pad.html?embed=1&title=Graphics: Example&p=graphics-intro.json" frameborder="0" width="840" height="480"></iframe>

<a href="/pad.html?title=Graphics: Example&p=graphics-intro.json" target="_blank">
  Open in new window
</a>

### File I/O

Pythonpad supports basic file i/o with its tiny on-memory file system.

<iframe src="/pad.html?embed=1&title=File I/O: Example&p=fileio-intro.json" frameborder="0" width="840" height="480"></iframe>

<a href="/pad.html?title=File I/O: Example&p=fileio-intro.json" target="_blank">
  Open in new window
</a>

### Hands-on Exercise

Pythonpad supports auto-grading user code with `.grader.py` on its file system.

<iframe src="/pad.html?embed=1&title=Exercise: Example&p=robot-zigzag.json" frameborder="0" width="840" height="480"></iframe>

<a href="/pad.html?title=Exercise: Example&p=robot-zigzag.json" target="_blank">
  Open in new window
</a>

### StdIn in Runtime

Pythonpad with stdin proxy server support is available at [Pythonpad.co](https://www.pythonpad.co).

<iframe src="https://www.pythonpad.co/pads/rzlo60ze9kw5tpxg/embed" frameborder="0" width="840" height="480"></iframe>

<a href="https://www.pythonpad.co/pads/rzlo60ze9kw5tpxg/" target="_blank">
  Open in new window
</a>
# CMeson

## About

* * *

CMeson is a lightweight and developer-friendly curses interface that
provides a simplistic way to interact with the venerable Meson build
system, it is also a cross-platform application meaning it can run
on most common host systems.

The main design goals of CMeson is to provide a standalone portable
curses interface and allow the users of the Meson build system to
access all or most of Meson build systems features with minimal effort
from within the command-line.

## Tooling information

* * *

Targeted audience we are building for is Windwos 10, MacOSX and Linux
users. This project uses [Python](https://www.python.org/) `3.8.x` and newer.

## Setup, Compile and Install

* * *

We should make sure the test run with no failed test cases:

```console
python3 -m pip install -r requirements.txt
python3 -m pytest test/run_tests.py
```

Installing should be easy. We install the application like so:

```console
python3 setup.py install
```

And finally we run this cool application:

```console
cmeson
```

## Contact the developer

* * *

You may find that I have a number of ways that you can contact
me. All of these methods happen to be listed on my blogging platform
[Mike's virtual office](https://michaelbrockus.home.blog/contact/).

Lastly don't forget to have a cup of virtual coffee. Thanks.

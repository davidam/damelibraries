<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#sec-1">1. Logo</a></li>
<li><a href="#sec-2">2. Introduction</a></li>
<li><a href="#sec-3">3. Install and Check tests in a Library</a></li>
<li><a href="#sec-4">4. License</a></li>
</ul>
</div>
</div>

# Logo<a id="sec-1" name="sec-1"></a>

![img](files/images/mapgie_in_madrid_91.jpg)

# Introduction<a id="sec-2" name="sec-2"></a>

Many people needs little snippets of source to make exercises and
learn a library. You can store your exercises in a repository, such
as, <https://github.com/davidam/python-examples.git>. It's useful, but
if the library is suffering changes or changing dependencies, perhaps
your snippets is not running.

In this project, we are experimenting a way, to store the snippets in
files to execute unit test. So, the snippets is easy to maintain.

# Install and Check tests in a Library<a id="sec-3" name="sec-3"></a>

If you want python virtual environment

    $ python3 -m venv /tmp/dl
    $ cd /tmp/dl
    $ source bin/activate

Now, you can install with pip

    $ pip install --upgrade pip
    $ pip3 install damelibraries

Checking my snippets:

    $ cd /tmp/dl/lib/python3.5/site-packages/damealgorithms
    $ nosetests3 tests
    $ cd /tmp/dl/lib/python3.5/site-packages/damejson
    $ nosetests3 tests
    $ cd /tmp/dl/lib/python3.5/site-packages/damepandas
    $ nosetests3 tests
    $ cd /tmp/dl/lib/python3.5/site-packages/damenltk
    $ nosetests3 tests
    $ cd /tmp/dl/lib/python3.5/site-packages/damenumpy
    $ nosetests3 tests
    $ cd /tmp/dl/lib/python3.5/site-packages/damescipy
    $ nosetests3 tests

# License<a id="sec-4" name="sec-4"></a>

This document is under a [Creative Commons Attribution 4.0 International](http://creativecommons.org/licenses/by/4.0/deed)

[![img](http://i.creativecommons.org/l/by/3.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/deed)
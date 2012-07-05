## Gnuplot.py: Py3k portage

This is a portage of [Gnuplot.py] to Python 3. All of the files and sources were taken from original repository.

## Installation

As you can read on the official page, Gnuplot.py depends on [NumPy]. Make sure you have NumPy installed for Python 3. 

### Few words about NumPy installation
If you are installing NumPy from sources, then you should install 

* "[ATLAS] + [LAPACK], or [MKL], or ACML" - as written on the official site;
* [nose] - for running tests.

To install nose from sources it's better to have fresh version of [distribute].

Go to the gnuplot.py-py3k directory and install Gnuplot.py-Py3k as other packages. For example:

    python3 setup.py install

## Testing

To test package you can run *demo.py* and *test.py*.

Tested on Linux under Python 3.2.3 and GCC 4.7.0. Running testing original package under Python 2.7.3 made *the same* output.

## Bugs and issues

Bugs and issues from the original repository were not fixed yet, so they still exist. No code refactoring yet was made too.

## Changes list

Look through commits messages to see the changes list. The rule of 'one change per commit' was followed.

## Credits

Despite this is my repository, credits are lived without changes.

## Additional info

All original info can be obtained from "*.txt" files.

[Gnuplot.py]:http://gnuplot-py.sourceforge.net/
[NumPy]:http://www.numpy.org/
[nose]:http://nose.readthedocs.org/en/latest/
[ATLAS]:http://math-atlas.sourceforge.net/
[LAPACK]:http://www.netlib.org/lapack/
[MKL]:http://software.intel.com/en-us/articles/intel-mkl/
[ACML]:http://developer.amd.com/libraries/acml/pages/default.aspx
[distribute]:http://pypi.python.org/pypi/distribute/#installing-and-using-distribute

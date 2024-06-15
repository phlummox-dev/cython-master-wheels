# Cython `master` wheel

Contains a GitHub Action workflow to build a wheel from the `master` branch of [Cython](https://github.com/cython/cython).

The use of `Py_LIMITED_API` - needed for building python extensions which are usable by multiple Python versions -
is buggy in the most recent Cython release (see [here][bug]). It only works well in the `master` branch.

[bug]: https://github.com/cython/cython/issues/6244

## to use 

Push a commit to the `main` branch to trigger the workflow.



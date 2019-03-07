# Welcome #

We're so glad you're thinking about contributing to this open source
project!  If you're unsure or afraid of anything, just ask or submit
the issue or pull request anyway.  The worst that can happen is that
you'll be politely asked to change something.  We appreciate any sort
of contribution, and don't want a wall of rules to get in the way of
that.

Before contributing, we encourage you to read our CONTRIBUTING policy
(you are here), our [LICENSE](LICENSE.md), and our
[README](README.md), all of which should be in this repository.

## Issues ##

If you want to report a bug or request a new feature, the most direct
method is to [create an
issue](https://github.com/cisagov/ansible-role-banner/issue) in this
repository.  We recommend that you first search through existing
issues (both open and closed) to check if your particular issue has
already been reported.  If it has then you might want to add a comment
to the existing issue.  If it hasn't then feel free to create a new
one.

## Pull requests ##

If you choose to [submit a pull
request](https://github.com/cisagov/ansible-role-banner/pulls), you
will notice that our continuous integration (CI) system runs a fairly
extensive set of linters and syntax checkers.  Your pull request may
fail these checks, and that's OK.  If you want you can stop there and
wait for us to make the necessary corrections to ensure your code
passes the CI checks.

If you want to make the changes yourself, or if you want to become a
regular contributor, then you will want to set up
[pre-commit](https://pre-commit.com/) on your local machine.  Once you
do that, the CI checks will run locally before you even write your
commit message.

### Setting up pre-commit ###

There are a few ways to do this, but we prefer to use
[`pyenv`](https://github.com/pyenv/pyenv) and
[`pyenv-virtualenv`](https://github.com/pyenv/pyenv-virtualenv) to
create a Python virtual environment specific to this project.  Once
`pyenv` and `pyenv-virtualenv` are installed on your system, you can
create the virtual environment with these commands:

```bash
cd ansible-role-banner
pyenv virtualenv <python_version_to_use> ansible-role-banner
pyenv local ansible-role-banner
pip install -r requirements-dev.txt
pre-commit install
```

## Public domain ##

This project is in the public domain within the United States, and
copyright and related rights in the work worldwide are waived through
the [CC0 1.0 Universal public domain
dedication](https://creativecommons.org/publicdomain/zero/1.0/).

All contributions to this project will be released under the CC0
dedication. By submitting a pull request, you are agreeing to comply
with this waiver of copyright interest.

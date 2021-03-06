Contributing to TwitStat
==========================

We love your input! We want to make contributing to this project as easy and transparent as possible, whether it's:

* Reporting a bug
* Discussing the current state of the code
* Submitting a fix
* Proposing new features
* Becoming a maintainer

We Develop with Github
------------------------

We use GitHub to track issues and feature requests, as well as accept pull requests.

We Use `Github Flow <https://guides.github.com/introduction/flow/index.html>`__, So All Code Changes Happen Through Pull Requests

Pull requests are the best way to propose changes to the codebase (we use `Github Flow <https://guides.github.com/introduction/flow/index.html>`__). We actively welcome your pull requests:

1. Fork the repo, clone and create your ``branch`` from ``develop``.

.. code-block:: bash

    git clone git@github.com:<your-username>/twitstat.git
    cd twitstat
    git checkout -b develop remotes/origin/develop
    git checkout -b "your_feature_branch"

2. Make your changes
3. Write clear meaningful git commit messages.

.. code-block:: bash

    git add <changed_files>
    git commit -m "Commit Header(limit to 72 chars)
    >
    > commit body (markdown supported)"
    git push -u origin <your_feature_branch>

4. Always create PR to ``develop`` branch.
5. If you are solving any issue(s), link that to your PR.
6. Make sure your code lints.
7. Issue that pull request!

Bugs and Issues
-----------------

Report bugs using Github's `issues <https://github.com/MLH-Fellowship/twitstat/issues>`__

We use `GitHub issues` to track public bugs. Report a bug by `opening a new issue <https://github.com/MLH-Fellowship/twitstat/issues/new>`__, it's that easy!

Conventions, we follow
-----------------------

* Git Branches::
    * ``main`` branch is used for Production
    * ``develop`` branch is used for the development or staging
    * ``feature_branch`` branch should create PR to ``develop`` branch
    * Delete the ``feature_branch`` once merged

* Project Board::
    * ``Frontend`` for the Frontend part of the Application
    * ``Backend`` for the backend part of the application
    * ``Bugs`` for reporting all the bugs, found on the application

Contribution Guidelines
------------------------

* Write clear meaningful git commit messages (Do read `How to Write a Git Commit Message <https://chris.beams.io/posts/git-commit/>`__).
* Make sure your PR's description contains GitHub's special keyword references that automatically close the related issue when the PR is merged. (Check out `Closing Issues via Pull Requests <https://github.com/blog/1506-closing-issues-via-pull-requests>`__ for more info)
* When you make very very minor changes to a PR of yours (like for example fixing a text in button, minor changes requested by reviewers) make sure you squash your commits afterward so that you don't have an absurd number of commits for a very small fix. (Learn how to squash at `Squash Commits with Git <https://davidwalsh.name/squash-commits-git>`__)
* When you're submitting a PR for a UI-related issue, it would be really awesome if you add a screenshot of your change or a link to a deployment where it can be tested out along with your PR. It makes it very easy for the reviewers and you'll also get reviews quicker.
* Please follow the `PR Template <https://github.com/MLH-Fellowship/twitstat/blob/main/.github/PULL_REQUEST_TEMPLATE.md>`__ to create the PR.
* Always open PR to ``develop`` branch.

* Please read our `Code of Conduct <./CODE_OF_CONDUCT.md>`__.

Contributing to the Documentation
----------------------------------

We use `sphinx <https://www.sphinx-doc.org/en/master/index.html>`__ to generate documentation. Sphinx uses `reStructuredText <http://docutils.sourceforge.net/rst.html>`__ as its markup language.

1. Move to the ``docs`` Directory

.. code-block:: bash

    cd docs

2. Install dependencies

.. code-block:: bash

    python -m pip install -r requirements.txt

3. Make Changes
4. Running the docs locally

.. code-block:: bash

    # inside docs directory
    make html   # build html
    open build/html/index.html  # Open/Refresh the index page to check the output

License
---------

**Any contributions you make will be under the MIT Software License**

In short, when you submit code changes, your submissions are understood to be under the same `MIT License <https://github.com/MLH-Fellowship/twitstat/blob/main/LICENSE>`__ that covers the project. Feel free to contact the maintainers if that's a concern.

By contributing, you agree that your contributions will be licensed under its `MIT License <https://github.com/MLH-Fellowship/twitstat/blob/main/LICENSE>`__.

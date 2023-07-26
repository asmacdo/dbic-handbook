
# Contributing to the DBIC Handbook

**Welcome to the DBIC Handbook repository located at [github.com/dbic/handbook](http://github.com/dbic/handbook) !**

*We're so excited you're here and want to contribute.*

We hope that these guidelines are designed to make it as easy as possible to get involved. If you have any questions that aren't discussed below, please let us know by [opening an issue](#understanding-issues).

## Table of contents

Been here before? Already know what you're looking for in this guide? Jump to the following sections:

*   [Joining the DBIC community](#joining-the-community)
*   [Contributing through GitHub](#contributing-through-github)
*   [Understanding issues](#understanding-issues)
*   [Writing in markdown](#writing-in-markdown)
*   [Make a change with a pull request](#making-a-change-with-a-pull-request)
*   [Example pull request](#example-pull-request)
*   [Fixing Remark errors from Travis](#fixing-travis-remark-errors)
*   [Recognizing contributions](#recognizing-contributions)

## Joining the community

DBIC - the [Dartmouth Brain Imaging Center](https://dartmouth.edu/dbic/) - is a growing community of neuroimaging enthusiasts, and we want to make our resources accessible to and engaging for as many researchers as possible.

How do you know that you're a member of the DBIC community? You're here! You know that DBIC exists! You're officially a member of the community. It's THAT easy! Welcome!

Most of our discussions take place here in [GitHub issues](#understanding-issues).
We also have a [mrusers mailing list](http://dbic.dartmouth.edu/mailman/listinfo/mrusers) for general DBIC announcements and discussion.

Moving forward, we encourage all members to contribute here on [GitHub](https://github.com/dbic/handbook).

As a reminder, we expect that all contributions adhere to our [Code of Conduct](CODE_OF_CONDUCT.md).

## Contributing through GitHub

[Git](https://git-scm.com/) is a really useful tool for version control. [GitHub](https://github.com/) sits on top of git and supports collaborative and distributed working.

We know that it can be daunting to start using git and GitHub if you haven't worked with them in the past, but the DBIC Handbook maintainers are here to help you figure out any of the jargon or confusing instructions you encounter!

In order to contribute via GitHub you'll need to set up a free account and sign in. Here are some [instructions](https://help.github.com/articles/signing-up-for-a-new-github-account/) to help you get going. Remember that you can ask us any questions you need to along the way.

## Understanding issues

Every project on GitHub uses [issues](https://github.com/dbic/handbook/issues) slightly differently.

The following outlines how DBIC developers think about communicating through issues.

**Issues** are individual pieces of work that need to be completed or decisions that need to be made to move the project forwards.
A general guideline: if you find yourself tempted to write a great big issue that
is difficult to describe as one unit of work, please consider splitting it into two or more issues.

Issues are assigned [labels](#issue-labels) which explain how they relate to the overall project's goals and immediate next steps.

### Issue labels

The current list of labels are [here](https://github.com/dbic/handbook/labels) and include:

* [![Help wanted](https://img.shields.io/badge/-help%20wanted-159818.svg)](https://github.com/dbic/handbook/labels/community) *These issues contain a task that a member of the team has determined we need additional help with.*

    If you feel that you can contribute to one of these issues, we especially encourage you to do so!

* [![Opinions wanted](https://img.shields.io/badge/-opinions%20wanted-84b6eb.svg)](https://github.com/dbic/handbook/labels/opinions%20wanted) *These issues hold discussions where we're especially eager for feedback.*

    Ongoing discussions benefit from broad feedback.
    This label is used to highlight issues where decisions are being considered, so please join the conversation!

* [![Community](https://img.shields.io/badge/-community-%23ddcc5f.svg)](https://github.com/dbic/handbook/labels/community) *These issues are related to building and supporting the DBIC community.*

    In addition to the handbook itself, we are dedicated to creating a healthy community.
    These issues highlight pieces of work or discussions around how we can support our members and make it easier to contribute.


## Writing in markdown

The handbook documents follow the [Markdown Style
Guide](http://www.cirosantilli.com/markdown-style-guide/).

You can validate your changes against the guide using
[remark](https://github.com/remarkjs/remark-lint) which works as a
[standalone command line
tool](https://github.com/remarkjs/remark/tree/master/packages/remark-cli)
as well as [a plugin for various text
editors](https://github.com/remarkjs/remark-lint#editor-integrations).
Remark preserves consistent markdown styling across the contributions.
Please ensure before submitting a contribution that you do not have any
linter errors in your text editor.  You can also use
[prettier](https://github.com/prettier/prettier) to automatically
correct some of the style issues that might be found in the proposed
changes.

We have deployed a continuous integrator ([circle
CI](https://circleci.com/)) to further allow for integrating changes
continuously. The CI is testing that the changes are inline with our
standard styling.

GitHub has a helpful page on [getting started with writing and
formatting on
GitHub](https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github).

## Building the handbook using mkdocs

We are using mkdocs to render our handbook. Please follow these
instructions if you would like to build the handbook locally.

#### 1. Install mkdocs

To begin please follow [this link](https://www.mkdocs.org/#installation)
to install mkdocs locally.

#### 2. Download the DBIC Handbook [repository](https://github.com/dbic/handbook/tree/master)

Cloning the repository with `git`(TODO link to docs). You will need
`git` to contribute the changes you make later.

#### 3. Install our theme

`pip install mkdocs-material`
See [theme website](https://squidfunk.github.io/mkdocs-material/) for
more info.

#### 4. In the terminal (command line) navigate to your local version of the handbook

This location will have the same files you see on our [main handbook
page](https://github.com/dbic/handbook). Note: A finder window may not
show the hidden files (those that start with a period i.e. .remarkrc)

#### 5. Ready to build!

Using the terminal (command line) please enter `mkdocs serve`. This will
allow you to see a local version of the handbook. The local address will
be `http://127.0.0.1:8000` or `localhost:8000`. You may enter that into
your browser and this will bring up the handbook!

## Making a change with a pull request

We appreciate all contributions to the DBIC Handbook. **THANK YOU** for
helping us build this useful resource.

#### 1. Comment on an existing issue or open a new issue referencing your addition

This allows other members of the DBIC Handbook team to confirm that you
aren't overlapping with work that's currently underway and that everyone
is on the same page with the goal of the work you're going to carry out.

#### 2. [Fork](https://help.github.com/articles/fork-a-repo/) [this repository](https://github.com/dbic/handbook) to your profile

This is now your own unique copy of the DBIC Handbook. Changes here
won't affect anyone else's work, so it's a safe space to explore edits
to the handbook!

Make sure to [keep your fork up to
date](https://help.github.com/articles/syncing-a-fork/) with the master
repository, otherwise you can end up with lots of dreaded [merge
conflicts](https://help.github.com/articles/about-merge-conflicts/).

#### 3. Make the changes you've discussed

Try to keep the changes focused. If you submit a large amount of work in
all in one go it will be much more work for whomever is reviewing your
pull request. Please detail the changes you are attempting to make.

#### 4. Submit a [pull request](https://help.github.com/articles/about-pull-requests/)

Please keep the title of your pull request short but informative - it
will appear in the [changelog](CHANGES.md).

Use one of the following prefixes in the title of your pull request:
  - `[ENH]` - enhancement of the handbook that adds a new feature or
    support for a new data type
  - `[FIX]` - fix of a typo or language clarification
  - `[INFRA]` - changes to the infrastructure automating the handbook
    release (for example building HTML docs etc.)
  - `[MISC]` - everything else including changes to the file listing
    contributors

If you are opening a pull request to obtain early feedback, but the changes
are not ready to be merged (a.k.a. Work in Progress pull request) please
use a [draft pull request](https://github.blog/2019-02-14-introducing-draft-pull-requests/).

A member of the DBIC Handbook team will review your changes to confirm
that they can be merged into the main codebase.

A [review](https://help.github.com/articles/about-pull-request-reviews/)
will probably consist of a few questions to help clarify the work you've
done. Keep an eye on your GitHub notifications and be prepared to join
in that conversation.

You can update your
[fork](https://help.github.com/articles/about-forks/) of the DBIC
Handbook and the pull request will automatically update with those
commits. You don't need to submit a new pull request when you make a
change in response to a review.

GitHub has a [nice
introduction](https://help.github.com/articles/github-flow/) to the pull
request workflow, but please [get in
touch](https://github.com/dbic/handbook/issues/new) if you have any
questions.

## Example pull request
<img align="center" src="https://i.imgur.com/s8yELfK.png" alt="Example-Contribution" width="800"/>


## Fixing Travis Remark errors

We use a linter called [Remarkjs](https://github.com/remarkjs/remark-lint) to ensure all of
our Markdown documents are consistent and well-styled.
This commonly produces errors, which are flagged by [Travis CI](https://travis-ci.org/),
a continuous integration service.
When Travis returns an error, use the following process to resolve the issue:

#### 1. Install NodeJS / npm

We use a markdown linter written in Javascript.
To run command Javascript tools on the command line, please [download and
install](https://nodejs.org/en/download/) NodeJS.

#### 2. Install Remark-CLI and our style guide

Remark-CLI can be installed via [npm](https://www.npmjs.com/), which is part of
the NodeJS distribution.

To install the packages we use for our style guide, the following
command will work on most command lines:

```
npm install `cat npm-requirements.txt`
```

The equivalent command on PowerShell is:

```
npm install @(cat npm-requirements.txt)
```

#### 3. Fix the flagged document

Please go to the directory where the flagged file is and run remark like this:

```
remark flagged_file.md -o flagged_file_fixed.md
```

Please confirm this has fixed the file.
To do this, please run this:

```
remark flagged_file_fixed.md --frail
```

This command will indicate whether this file now conforms to the style guide.
If it passes, replace `flagged_file.md` with the contents of `flagged_file_fixed.md`,
add and commit the change:

```
mv flagged_file_fixed.md flagged_file.md
git add flagged_file.md
git commit -m 'STY: Fixed Markdown style'
```

## How the decision to merge a pull request is made?

Everyone use your best judgement, it's worked fine so far.

## Recognizing contributions

DBIC follows the [all-contributors](https://github.com/kentcdodds/all-contributors) handbook, so we welcome and recognize all contributions from documentation to testing to code development. You can see a list of current contributors in the [DBIC Handbook](https://github.com/dbic/handbook/blob/master/src/99-appendices/01-contributors.md).

## Thank you!

You're awesome.

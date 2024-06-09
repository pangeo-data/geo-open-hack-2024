# Introduction

## Welcome to the Geo Open Hack GitHub Community!

Thank you for considering to contribute to this repository with your ideas and suggestions.

## Guidelines

Reading our guidelines is key to maximise your contribution, understanding project policies, knowing repositories management, naming conventions, etc.

## Contributing through GitHub

[Git][git] is a really useful tool for version control.
[GitHub][github] sits on top of Git and supports collaborative and distributed working.

We know that it can be daunting to start using Git and GitHub if you haven't worked with them in the past, but _Geo Open Hack 2024_ maintainers are here to help you figure out any of the jargon or confusing instructions you encounter! :green_heart:

In order to contribute via GitHub, you will need to set up a free account and sign in.
Here are some [instructions](https://help.github.com/articles/signing-up-for-a-new-github-account/) to help you get going.
Remember that you can ask us any questions you need to along the way.

## Writing in Markdown

GitHub has a helpful page on [getting started with writing and formatting on GitHub](https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github).

Most of the writing that you will do will be in [Markdown][markdown].
You can think of Markdown as a few little symbols around your text that will allow GitHub to render the text with a little bit of formatting.
For example, you could write words as **bold** (`**bold**`), or in _italics_ (`_italics_`), or as a [link][rick-roll] (`[link](https://youtu.be/dQw4w9WgXcQ)`) to another webpage.

Also when writing in Markdown, please [start each new sentence on a new line](https://the-turing-way.netlify.app/community-handbook/style.html#write-each-sentence-in-a-new-line-line-breaks).
Having each sentence on a new line will make no difference to how the text is displayed, there will still be paragraphs, but it makes the [diffs produced during the pull request](https://help.github.com/en/articles/about-comparing-branches-in-pull-requests) review easier to read! :sparkles:

## Where to start: issues

Before you open a new issue, please check if any of our [open issues](https://github.com/pangeo-data/geo-open-hack-2024/issues) cover your idea already.

## Making a change with a pull request

We appreciate all contributions to _Geo Open Hack 2024_.
**THANK YOU** for helping us build this useful resource. :seedling:

All project management, conversations and questions related to _Geo Open Hack 2024_ project happens here in [_Geo Open Hack 2024_ repository](https://github.com/pangeo-data/geo-open-hack-2024).
This is also where you can contribute directly to writing or editing chapters of [the rendered website](https://pangeo-data.github.io/geo-open-hack-2024)!

The following steps are a guide to help you contribute in a way that will be easy for everyone to review and accept with ease :mortar_board:.

### 1. Comment on an [existing issue](https://github.com/pangeo-data/geo-open-hack-2024/issues) or open a new issue referencing your addition

This allows other members of _Geo Open Hack 2024_ team to confirm that you aren't overlapping with work that's currently underway and that everyone is on the same page with the goal of the work you're going to carry out.

[This blog](https://www.igvita.com/2011/12/19/dont-push-your-pull-requests/) is a nice explanation of why putting this work in upfront is so useful to everyone involved.

### 2. [Fork][github-fork] _Geo Open Hack 2024_ repository

This is now your own unique copy of _Geo Open Hack 2024_.
Changes here won't affect anyone else's work, so it's a safe space to explore edits to the code!

Make sure to [keep your fork up to date][github-syncfork] with the main repository, otherwise, you can end up with lots of dreaded [merge conflicts][github-mergeconflicts].
If you prefer working in the browser, [these instructions](https://github.com/KirstieJane/STEMMRoleModels/wiki/Syncing-your-fork-to-the-original-repository-via-the-browser) describe how to sync your fork to the original repository via GitHub.

### 3. Make the changes you've discussed

Try to keep the changes focused.
If you submit a large amount of work all in one go it will be much more work for whoever is reviewing your pull request.
[Help them help you.][jerry-maguire] :wink:

While making your changes, commit often and write good, detailed commit messages.
[This blog](https://chris.beams.io/posts/git-commit/) explains how to write a good Git commit message and why it matters.
It is also perfectly fine to have a lot of commits - including ones that break code.
A good rule of thumb is to push up to GitHub when you _do_ have passing tests then the continuous integration (CI) has a good chance of passing everything. 😸

If you feel tempted to "branch out" then please make a [new branch][github-branches] and a [new issue][geo-open-hack-2024-issues] to go with it. [This blog](https://nvie.com/posts/a-successful-git-branching-model/) details the different Git branching models.

Please do not re-write history!
That is, please do not use the [rebase](https://help.github.com/en/articles/about-git-rebase) command to edit previous commit messages, combine multiple commits into one, or delete or revert commits that are no longer necessary.

Are you new to Git and GitHub or just want a detailed guide on getting started with version control? Check out our [Version Control chapter](https://the-turing-way.netlify.com/version_control/version_control.html) in _The Turing Way_ Book!

### 4. Submit a [pull request][github-pullrequest]

We encourage you to open a pull request as early in your contributing process as possible.
This allows everyone to see what is currently being worked on.
It also provides you, the contributor, feedback in real-time from both the community and the continuous integration as you make commits (which will help prevent stuff from breaking).

If you have opened the pull request early and know that its contents are not ready for review or to be merged, add "[WIP]" at the start of the pull request title, which stands for "Work in Progress".
When you are happy with it and are happy for it to be merged into the main repository, change the "[WIP]" in the title of the pull request to "[Ready for review]".

A member of _Geo Open Hack_ team will then review your changes to confirm that they can be merged into the main repository.
A [review][github-review] will probably consist of a few questions to help clarify the work you've done.
Keep an eye on your GitHub notifications and be prepared to join in that conversation.

You can update your [fork][github-fork] of _Geo Open Hack_ [repository][geo-open-hack-2024-repo] and the pull request will automatically update with those changes.
You don't need to submit a new pull request when you make a change in response to a review.

You can also submit pull requests to other contributors' branches!
Do you see an [open pull request](https://github.com/pangeo-data/geo-open-hack-2024/pulls) that you find interesting and want to contribute to?
Simply make your edits on their files and open a pull request to their branch!

What happens if the continuous integration (CI) fails (for example, if the pull request notifies you that "Some checks were not successful")?
The CI could fail for a number of reasons.
At the bottom of the pull request, where it says whether your build passed or failed, you can click “Details” next to the test, which takes you to a CI run log site.
If you have the write access to the repo, you can view the log or rerun the checks by clicking the “Restart build” button in the top right.
You can learn more about CI in the [Continuous Integration chapter](https://the-turing-way.netlify.app/reproducible-research/ci.html)!

GitHub has a [nice introduction][github-flow] to the pull request workflow, but please [get in touch](#get-in-touch) if you have any questions or ideas :bulb:.

## Local development

You can build and host the book website locally. The steps are:

### To build book locally

1. Install the required software to build the book, optionally in a [virtual environment](https://packaging.python.org/tutorials/installing-packages/#creating-virtual-environments):

   To install Python, we recommend to install [conda](https://conda.io/projects/conda/en/latest/index.html) or [miniconda](https://docs.anaconda.com/free/miniconda/) and then create a new conda environment using [.binder/environment.yml](https://raw.githubusercontent.com/pangeo-data/geo-open-hack-2024/main/.binder/environment.yml):

   ```
   conda env create -f environment.yml
   ```

   Do not forget to switch to the `geohack` conda environment prior to executing any Jupyter notebooks or programs from the `geo-open-hack-2024` repository.

   ```
   conda activate geohack
   ```

2. You can now build or refresh the book using:

   ```
   cd ./docs
   jupyter-book build .
   ```

[geo-open-hack-2024-repo]: https://github.com/pangeo-data/geo-open-hack-2024/
[geo-open-hack-2024-issues]: https://github.com/pangeo-data/geo-open-hack-2024/issues
[git]: https://git-scm.com
[github]: https://github.com
[github-branches]: https://help.github.com/articles/creating-and-deleting-branches-within-your-repository
[github-fork]: https://help.github.com/articles/fork-a-repo
[github-flow]: https://guides.github.com/introduction/flow
[github-mergeconflicts]: https://help.github.com/articles/about-merge-conflicts
[github-pullrequest]: https://help.github.com/articles/creating-a-pull-request
[github-review]: https://help.github.com/articles/about-pull-request-reviews
[github-syncfork]: https://help.github.com/articles/syncing-a-fork
[markdown]: https://daringfireball.net/projects/markdown
[rick-roll]: https://www.youtube.com/watch?v=dQw4w9WgXcQ
[jerry-maguire]: https://media.giphy.com/media/uRb2p09vY8lEs/giphy.gif
[all-contributors]: https://github.com/kentcdodds/all-contributors#emoji-key

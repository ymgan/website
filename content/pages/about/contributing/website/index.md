---
title: Contributing to the TDWG website
summary: The TDWG website is a collaborative effort: anyone can contribute! Whether it is [reporting an issue](#how-do-i-report-an-issue), [writing content](#how-do-i-edit-content) or [reviewing](#how-can-i-review-content), any help in keeping the website up to date and relevant is helpful. This page explains how.
cover_image: https://images.unsplash.com/photo-1508780709619-79562169bc64
cover_image_by: Kaitlyn Baker
cover_image_link: https://unsplash.com/photos/vZJdYl5JVXY
tags: 
toc_headers: ^h[2-3]
---

## Reporting issues

Discovered a typo? Noticed a bug? Have a suggestion to improve a page? Let us know by [creating an issue](https://github.com/tdwg/website/issues/new) in the website repository.

### How do I report an issue?

1. Go to the issues section of the website repository at <https://github.com/tdwg/website/issues>.
2. Make sure you are logged-in to GitHub.
3. Click the green button `New` or use [this direct link](https://github.com/tdwg/website/issues/new).
4. Add a title and describe the issue, e.g.:

    > BDQ page missing "Becoming involved" section
    > 
    > ---
    > 
    > **Page(s) where issue occurs**
    > 
    > <https://www.tdwg.org/community/bdq/>
    > 
    > **Issue description**
    > 
    > The biodiversity data quality page does not have a section on how people could be involved, which limits contributions to this group. Other interest group pages might also miss this section, but I didn't check for those.

5. Click the green button ` Submit new issue`.
6. Great! Your issue report has been logged and the website maintainers have been notified. You will receive an email notification if they have questions or if the issue has been resolved.

Want to solve the issue yourself instead? See [how to edit content](#how-do-i-edit-content).

## Writing content

### How do I edit content?

1. From the page you want to change, click `Edit this page` or `Edit this article` in the top right (note: this page has this too!).
2. That will take you to the corresponding Markdown document for that page. Alternatively, you can [browse the website repository](https://github.com/tdwg/website/tree/master/content) for the page you are looking for.
3. Click the pencil button on the top right to edit the page. You need to be logged-in to GitHub to do this.

    ![Edit button on GitHub]({filename}edit-button-github.png)

    Note: behind the scenes, this will fork the website repository to your account, so you can make suggestions.

4. Edit the file using [Markdown syntax](https://guides.github.com/features/mastering-markdown/).
5. Preview your suggestions by switching to the `Preview changes` tab. You can switch between the tabs `Edit file` / `Preview changes` as much as you want.
6. At the bottom of the page, write a short description of what you changed. If you want to explain more, use the bigger text box as well, e.g.:

    > Add how to become involved to BDQ IG + correct link
    > 
    > ---
    > 
    > The biodiversity data quality page was missing a section on how people could become involved in that interest group. I also updated a broken link.

7. Click the green buttons `Propose file change`, then `Create pull request` and then `Create pull request` again.
8. Great! Your proposed changes are now submitted as a [pull request](https://help.github.com/articles/about-pull-requests/) and the website maintainers have been notified. You will receive an email notification if they have questions or when your suggestions have been accepted.

Want to make more substantial changes instead? See [how to edit multiple pages at once](#how-do-i-edit-multiple-pages-at-once).

### How do I edit multiple pages at once?

If you want to edit multiple pages, then the workflow to [propose a single file change](#how-do-i-edit-content) might be too limiting. You can solve this by working on the files on your own computer. It does require some more advanced knowledge of GitHub however:

1. [Fork this repository](https://help.github.com/articles/fork-a-repo/) to your own GitHub account. This is actually done too if you [edit a single file](#how-do-i-edit-content). In your fork, you can experiment freely without effecting the original website repository.
2. [Clone your fork](https://help.github.com/articles/cloning-a-repository/#cloning-a-repository-to-github-desktop) to your computer. The easiest tool for this [GitHub Desktop](https://desktop.github.com/).
3. Edit the files in your favourite text editor. You can also add/delete files.
4. Commit and push your changes.
5. Propose your changes by [creating a pull request](https://help.github.com/articles/creating-a-pull-request-from-a-fork/) from your fork.

Note: it's best not to let your work linger in your fork, as it will get out of sync with the main repository. To get your fork up to date again, [sync your fork](https://help.github.com/articles/syncing-a-fork/).

### Do I need to login to see the "Edit this page" link?

No, there is no logged-in section for this website. The link will appear for any visitor, at the top right of any page and article:

![Edit this page]({filename}edit-this-page-link.png)

For articles it will say `Edit this article`. The link will take you to [GitHub](https://github.com/tdwg/website), where all authentication is handled.

Note: a couple of pages - like [search](/search.html) or the [news index](/news/) - are generated. The `edit this page` link will not appear on those, as there is nothing to edit manually.

### Should I use American or British English?

We use [Oxford spelling](https://en.wikipedia.org/wiki/Oxford_spelling) (British English with "-ize") for all TDWG content.

### What is page metadata?

...

### What is the difference between a page and an article?

...

### How do I start a new page?

...

### How do I start a new news article?

...

### How do I add a static document (e.g. image, pdf)?

...

### How do add an internal link?

...

## Changing layout

### How do I change the cover image?

...

### How do I change the order of pages in the navigation?

...

### How do I create the side navigation?

...

### How do I change the home page

...

### How do I change the rest of the layout?

...

## Reviewing

### Why are my suggestions not appearing on www.tdwg.org?

[Suggestions](#how-do-i-edit-content) you make do not appear live on www.tdwg.org. This takes three steps:

1. They need to be **reviewed** ([by anyone](#how-can-i-review-content)). This is done on a voluntary basis and can take some time. You will receive an email notification for this.
2. They need to be **approved** by one of the [website maintainers](#who-maintains-the-website). You will receive an email notification for this.
3. Once accepted (i.e. the pull request is merged), an **automatic build script** will rebuild the website and incorporate your changes. This can take up to a minute.

If your suggestions are rejected (i.e. the pull request is closed without merging), you will also receive an email notification, but step 3 will be skipped (i.e. the website will not be updated).

### How can I review content?

You can review content by [watching this repository](https://help.github.com/articles/watching-and-unwatching-repositories/#watching-a-single-repository):

1. Click the `Watch` button in the top right of this repository, then select `Watching`.
2. You will be notified by email of any reported issue or suggested changes.
3. From those emails, click `view it on GitHub` at the bottom to open the issue or pull request.
4. Review the issue or suggested change and leave feedback as a comment.
5. Great! Your review helps website maintainers to approve/refuse suggestions and improves the quality of the website.

If you also want to approve suggestions, you can [ask to become a website maintainer](#who-maintains-the-website)?

### Who maintains the website?

Everyone! See [how you can contribute](#how-can-i-contribute) and [who has contributed already](https://github.com/tdwg/website/graphs/contributors).

There is a dedicated group of **website maintainers** however that have admin rights to this repository: they are the people who can [approve changes](#why-are-my-suggestions-not-appearing-on-wwwtdwgorg) and have these appear on www.tdwg.org. If you want to join that group, send an email to secretary@tdwg.org.

## Other

### What is the technology behind the TDWG website?

...

### How do I update these FAQ?

...
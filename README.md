---
title: Telerik UI for WinForms Documentation Repo
publish: false
---


# Telerik UI for WinForms Public Documentation

Welcome to the GitHub repo for [Telerik UI for WinForms](http://www.telerik.com/winforms) documentation. This repository contains the source content — written in Markdown — that we use to power the Telerik UI for WinForms Documentation at [docs.telerik.com/devtools/winforms](http://docs.telerik.com/devtools/winforms). If you've arrived here wanting to search and peruse our docs, you'd be better served heading over to [docs.telerik.com/devtools/winforms](http://docs.telerik.com/devtools/winforms) where our content is prettified and searchable.

We believe that the documentation for a product is at its best when the content is a collaboration between the builders and consumers of that product. As such, this documentation is both public, and open sourced under and MIT license (see below). That means you can clone this repository, read the docs off line, or even load the entire thing to an [Apple Newton] (https://en.wikipedia.org/wiki/Apple_Newton), if that's your thing.

It also means that you can play a role in making our docs better for everyone, and if helping us make the Telerik UI for WinForms docs better sounds interesting to you, read on.

## Contributing

There are two ways you can contribute to the public Telerik UI for WinForms documentation: either create an issue in this repository, or fork the repo, make the change and send us a pull request!

* **Create an issue** - If you find an issue with our docs that needs to be addressed, the best way to let us know about it is by [creating an issue in this repository](https://github.com/telerik/winforms-docs/issues?state=open). When creating an issue, provide a descriptive title, be as specific as possible and link to the document in question (If you can provide a link to the closest anchor to the issue, all the better). Here's an example:

        Title: api/DataViz/chart.md is missing an image
        Description : Example 3 is missing an image right after the code sample. https://github.com/telerik/winforms-docs/issues?state=open

> Note: When creating issues, please don't modify the assignee or milestone fields. Also, please create one issue per fix or change. "Bundled" entries will be deleted.

* **Send us a pull request** - Creating an issue is great — and we certainly appreciate them — but what we really love are pull requests. So, if you find an issue in the docs, or even feel like creating new content, we'd be happy to have your contributions! If you're just getting started with open source, Git and GitHub, we suggest you first read up on [forking repositories](https://help.github.com/articles/fork-a-repo) and [sending pull requests](https://help.github.com/articles/using-pull-requests), both great articles from the GitHub bootcamp.

    Once you've read these — or you've already memorized them — you're ready to contribute to the Telerik UI for WinForms docs. Start by creating a local clone of our repo either using [GitHub for Windows](http://windows.github.com/), [GitHub for Mac](http://mac.github.com/) or your friendly command-line:

        git clone git@github.com:telerik/winforms-docs.git

    Then, open up the winforms-docs folder in your favorite text editor and contribute away! Of course, as you work with the docs, we do ask that you follow a couple of ground rules:

    - Fixing grammar, punctuation and other general errors is always appreciated. So are changes that expand on key ideas or correct errors in logic phrasing or otherwise. If your ambitions are greater, however, and you want to add completely new content to the site — like a new tutorial on using WinForms UI with an Atari 2600, for instance — we suggest you contact a member of the team first by entering an issue, to vet your idea. 
    - Each document in this repo contains a section of YAML Front Matter at the very top. This content, which looks like the text below, is used by our auto-import tool when content is processed for the live documentation site. Please don't edit the content in this section of a document.

         ---

        title: Introduction

        page_title: Introduction 

        description: Introduction

        slug: introduction

        tags: introduction

        published: True

        position: 1

         ---
         

    - When adding content or making changes, please use only standard Markdown syntax, and make to preview your additions or changes before sending us a pull request. You can use an online tool like [Dillinger.io](http://dillinger.io/) or [Marked](http://markedapp.com/) on OSX to view what your changes will look like when ported to HTML.

    - The [documentation Wiki](https://github.com/telerik/winforms-docs/wiki) contains the latest authoring guidelines.

    Once you've made your changes, commit, pull, merge, push and [send us a pull request](https://help.github.com/articles/using-pull-requests)! We — and WinForms users everywhere — thank you for making our docs the best front-end library documentation on the web!

## Running locally

You can generate a static web site from the Telerik UI for WinForms the documentation and browse it locally.

For the WinForms documentaion:

 1. Clone the repository `git clone git@github.com:telerik/winforms-docs.git`
 2. Run `bundle install` (you must have ruby and bundler installed beforehand)
 3. Run `bundle exec jekyll serve`
 4. Configure an [IIS server](https://github.com/telerik/winforms-docs/wiki/Deploying-Documentation-on-IIS)
 5. Open "http://localhost/devtools/winforms" in your browser

## License

The Telerik UI for WinForms Documentation is licensed under an MIT license. This license applies to the markdown (.md) files in this site **ONLY**, and does not convey, override or modify any existing licenses covering the runtime source and components of Telerik UI for WinForms. For information about available licenses for the Telerik UI for WinForms click [here](http://www.telerik.com/purchase/license-agreement/winforms-dlw-s).

### MIT License

Copyright (c) 2012-2016 Telerik

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software" ), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


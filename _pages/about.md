---
permalink: /
title: "Jingliang Deng"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a master student with the School of Software Engineering at South China University of Technology. Previously, I focused on Computer Programming Contest and obtained ICPC regional Bronze medal.  Currently, My research interests include backend development, deep learning and compuer vision.

Honor and Award
======
研究生国家奖学金, 2024

国家奖学金, 2021

国家奖学金, 2019

企业奖学金（腾讯、温氏筠城）

Competition Award
======

华为杯研究生数学建模竞赛全国三等奖, 2023

全国大学生电子商务“创新、创意及创业”挑战赛二等奖，2023&2024

ACM-ICPC Regional Bronze medal, 2022

GuangDong Province Programming Contest Silver medal, 2022

HuBei Province Programming Contest Gold medal, 2021

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/dengjl-hub/dengjl-hub.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/dengjl-hub/dengjl-hub.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/dengjl-hub/dengjl-hub.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/dengjl-hub/dengjl-hub.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://dengjl-hub.github.io/talks), each [individual page](https://dengjl-hub.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://dengjl-hub.github.io/cv), and the [map of places you've given a talk](https://dengjl-hub.github.io/talkmap.html) (if you run this [python file](https://github.com/dengjl-hub/dengjl-hub.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/dengjl-hub/dengjl-hub.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/dengjl-hub/dengjl-hub.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/dengjl-hub/dengjl-hub.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://dengjl-hub.github.io/markdown/), the [growing wiki](https://github.com/dengjl-hub/dengjl-hub.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/dengjl-hub/dengjl-hub.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

Journals
----------
<div>
  <table>
  {% for post in site.journals_main reversed %}
    <tr>{% include publication.html %}</tr>
  {% endfor %}
  </table>
   <a href="/journals/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div>

<!-- <div margin-bottom:100px>
  <a href="/journals/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div>  -->

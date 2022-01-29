---
permalink: /
title: "Welcome to Manav’s Homepage!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Third-year Undergraduate student at the Department of Electrical Engineering , Indian Institute of Technology Kharagpur. At IIT Kharagpur, I am part of the Transparency in AI and Language (TrAIL) Lab under the supervision of [Prof. Somak Aditya](https://scholar.google.com/citations?user=2shiHpwAAAAJ&hl=en).
<!-- I was fortunate to intern at Adobe Research, India. I was also selected for IUSSTF-Viterbi program and got the oppotunity to intern at INK-Lab, University of Southern California. -->

News
======

<table width="100%" align="center">
          <tr>
            <td>
              <heading>News</heading>
                <hr/>
            </td>
          </tr>
        </table>
        <table width="100%" align="center">
          <tr>
            <td width="10%">&nbsp;&nbsp;&nbsp;&nbsp; [Jan 22]</td>
            <td width="90%">Started working as a <b><u>six month research intern</u></b> at <a href="https://www.microsoft.com/en-us/research/group/prose/" > PROSE, Microsoft Research</a></td>
          </tr>
          <tr>
            <td width="10%">&nbsp;&nbsp;&nbsp;&nbsp; [Jan 22]</td>
            <td width="90%">Selected to attend <a href="https://sites.google.com/view/researchweek2022" >Research Week with Google</a> from <b><u>8 - 11 Feb, 2022</u></b></td>
          </tr>
          <tr>
            <td width="10%">&nbsp;&nbsp;&nbsp;&nbsp; [Dec 21]</td>
            <td width="90%">Received the <a href="http://www1.iitkgp.ac.in/topfiles/sric" >Prof. J.C. Ghosh Memorial Endowment Prize </a> for securing highest CGPA at the end of VI semester</td>
          </tr>
          <tr>
            <td width="10%">&nbsp;&nbsp;&nbsp;&nbsp; [Nov 21]</td>
            <td width="90%">Member of coding team (at IIT Kharagpur) responsible for organizing a pan-India engineering entrance exam</td>
          </tr>
          <tr>
            <td width="10%">&nbsp;&nbsp;&nbsp;&nbsp; [Sep 21]</td>
            <td width="90%"> One paper accepted in the <a href="https://2021.argmining.org/" >8th workshop on ArgumentMining at EMNLP 2021</a></td>
          </tr>
          <tr>
            <td width="10%">&nbsp;&nbsp;&nbsp;&nbsp; [May 21]</td>
            <td width="90%">Started working as research intern at <a href="https://research.adobe.com/careers/bangalore/" >Adobe Research, India</a> on Topological Data Analysis</td>
          </tr>
          <tr>
            <td width="10%">&nbsp;&nbsp;&nbsp;&nbsp; [May 21]</td>
            <td width="90%">Accepted in IUSSTF-Viterbi program to intern at <a href="https://inklab.usc.edu/" >INK-Lab</a> under <a href="https://scholar.google.com/citations?user=_moJlrIAAAAJ&hl=en" > Prof. Xiang Ren</a></td>
          </tr>
          <tr>
            <td width="10%">&nbsp;&nbsp;&nbsp;&nbsp; [Dec 20]</td>
            <td width="90%">One paper accepted in the <a href="https://computingconf.com/2020/" >10th International Advance Computing Conference (IACC 2020)</a></td>
          </tr>
          <tr>
            <td width="10%">&nbsp;&nbsp;&nbsp;&nbsp; [Jun 19]</td>
            <td width="90%">Received the <a href="http://www1.iitkgp.ac.in/topfiles/sric" > Technology Alumni Association (Delhi Chapter) Award </a> for securing highest CGPA at the end of II semester</td>
          </tr>
        </table>
        <hr/>


Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

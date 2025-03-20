---
permalink: /
title: "个人简介"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

杨烈，特聘教授，南昌大学高层次人才，主要研究方向有：深度学习，计算集视觉，自动驾驶系统的智能感知，脑电信号解码和脑机接口技术等。2021年毕业于华南理工大学，获得工学博士学位。2022年3月加入海南大学计算机科学与技术学院，被聘为特聘副教授。2022年10月赴新加坡南洋理工大学，机械与宇航工程学院（MAE）从事博士后研究。2025年2月初回国，加入南昌大学先进制造学院，被聘为特聘教授。
近五年发表SCI论文20余篇，其中以第一作者身份共发表SCI检索论文7篇，并获得已授权的发明专利8项。在博士期间参与了国家自然科学基金2项，参与省部级项目2项；在南洋理工大学从事博士后研究期间参与了国际合作项目2项。曾获国家奖学金，校长奖学金，校特等奖学金，校一等奖学金。2021年9月获得世界机器人大赛-BCI脑控机器人大赛，全国总决赛二等奖，2021年底被评为“广东省优秀学生”。

学术兼职
======
客座编辑：
Lead Guest Editor, Special Issue on “Application of Deep Learning in Intelligent Machines” at MDPI Machines, 2023-2024.
Lead Guest Editor, Special Issue on “The Application of Deep Learning in Intelligent Vehicle Perception Systems” at MDPI Vehicles, 2024-2025.

参与审稿的主要期刊有：
IEEE Transactions on Intelligent Transportation Systems, IEEE Transactions on Vehicular Technology, IEEE Transactions on Intelligent Vehicles, IEEE Transactions on Systems, Man and Cybernetics: Systems, IEEE Transactions on Neural Systems and Rehabilitation Engineering, IEEE Journal of Biomedical and Health Informatics, Journal of Neural Engineering, IEEE Transactions on Neural Networks and Learning Systems, IEEE/CAA Journal of Automatica Sinica, Measurement Science and Technology, Assembly Automation, etc.


Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
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

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

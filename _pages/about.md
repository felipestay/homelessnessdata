---
permalink: /
title: "Repository for research on homelessness"
excerpt: "About the project"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This academic repository holds great significance as a central hub for research on homelessness in Chile and Latin America. By bringing together a wide range of resources, including studies, data, and research findings, it consolidates knowledge and facilitates collaboration among academics, researchers, and policymakers. The repository's accessibility of data ensures transparency and empowers stakeholders with up-to-date and reliable information on homelessness trends, contributing factors, and potential solutions. This wealth of research not only supports evidence-based policymaking but also raises public awareness, fostering understanding and empathy for those affected by homelessness. Ultimately, this repository serves as a vital tool in advancing research, policy development, and advocacy efforts aimed at addressing and alleviating homelessness in Chile and Latin America.

About us
======
I am Felipe Estay, a researcher and a member of the board at CISCAL (Center of Research and Advocacy about Homelessness - ciscal.org). I utilise my personal academic website as a platform for disseminating data and research findings related to this urgent issue. This website serves not only as a knowledge repository but also as a collaborative hub, bringing together researchers, policymakers, activists, and community members. It fosters a sense of shared responsibility in addressing homelessness. By providing a space for exchanging ideas, best practices, and innovative approaches, it encourages fruitful discussions and the development of effective strategies.

Community engagement is central to our mission. The website acts as a bridge between academia and the broader community, making research accessible and understandable to individuals from all walks of life. Our goal is to translate complex research findings into practical information, empowering individuals and organizations to actively participate in tackling homelessness. Through this personal and collective project, we strive to raise awareness, challenge stereotypes, and advocate for policy changes that prioritize affordable housing, social support, and holistic solutions. Together, we can create a society where everyone has access to safe and stable housing, ensuring that no one is left without a place to call home.

What kind of data will you find?
======
1. Publications about qualitative and quantitative research: The academic repository offers access to publications that encompass both qualitative and quantitative research on homelessness. These publications may consist of scholarly articles, research papers, and academic studies, providing valuable insights into different research methodologies and findings related to homelessness.
1. Annual congress seminars and talks about homelessness in Chile, Latin America, and the US: The repository provides resources pertaining to annual congress seminars and talks specifically focused on homelessness in these regions. These materials may include conference presentations, keynote speeches, panel discussions, and other relevant content, fostering a platform for knowledge sharing and the discussion of current issues and advancements in addressing homelessness.
1. Teaching opportunities provided by academic institutions: The repository presents information on teaching opportunities related to homelessness offered by academic institutions. This could include courses, workshops, and training materials aimed at educating students and professionals about homelessness, its causes, impacts, and potential solutions.
1. Access to visualized data: The repository offers visualized data on homelessness, presenting information through charts, graphs, maps, and other visual representations. Visualizing data enhances understanding, facilitates comparisons, and provides a clearer overview of homelessness trends, patterns, and related factors.
1. Press notes and blog entries: The repository includes press notes and blog entries that focus on homelessness. These resources may encompass news articles, opinion pieces, and blog posts, offering diverse perspectives, updates, and discussions on topics related to homelessness.
1. Raw data: The repository provides access to raw data related to homelessness. This includes datasets, surveys, and other primary data sources that researchers can utilize for their own analyses, enabling further exploration and interpretation of homelessness-related trends and phenomena.
1. Special section on homelessness death statistics: The repository features a dedicated section specifically focused on homelessness death statistics. This section presents data and analyses related to mortality rates, causes of death, and other pertinent information regarding the impact of homelessness on individuals' health and well-being.



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

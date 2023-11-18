---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<img style="float: right; padding: 10px 10px 10px 10px;" src="https://abdul-qadirr.github.io/images/sunflower_fields%20mapped%20in%20Hungary%20for%202018.png" width=350>
I am a Geospatial Data Scientist and Future Investigators in NASA Earth and Space Science and Technology (FINESST) fellow. I will be working with NASA HARVEST as Synthetic Aperture Radar (SAR) specialist for agriculture monitoring from December, 2023. I utilize statistical and machine learning-based methods to extract insights from remote sensing data. I construct pipelines that deliver metrics from Synthetic Aperture Radar (SAR) and other satellite imagery. Additionally, I utilize causal inference to assess the impact of climate and human-induced changes on agriculture and natural resources. My objective is to assist decision-makers and the scientific community in formulating informed policies pertaining to natural resources and food security concerns.

I completed my Phd in Geographical Sciences in October 2023 from Department of Geographical Sciences, University of Maryland-College Park. My Phd thesis was on
"SAR based spatial modelling and generalization approach for crop monitoring in data sparse regions of the world". During PhD, I developed a physics-guided Machine Learning (ML) based model for sunflower crop mapping and generalization in Ukraine and Russia. Based on this model, I assessed and quantified the impact of Russian aggression on sunflower crop in Ukraine.

You can download my CV [here](http://hannah-rae.github.io/files/Kerner_Hannah_CV.pdf).

Achievements and Awards
======
- Arrell Global Food Innovation Award-2023 (NASA Harvest team member)
- Planet purpose "Do Good" Award-2023 (NASA Harvest team member)
- Future Investigators in NASA Earth and Space Science and Technology (FINESST) grant (2021-2024)
- Outstanding Graduate Research Assistant, University of Delaware (2020) 
- Ta Liang Memorial Award from American Society of Photogrammetry and Remote Sensing (2020)
- Outstanding Achievement Award, Indian Graduate Student Association, University of Delaware (2019)
- 1st prize for the ESRI-ISI competition, World Statistical Congress, Kuala lumpur Malaysia (2019)

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

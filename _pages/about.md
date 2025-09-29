---
permalink: /
title: "Biography"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Nguyen Van Sy graduated with a B.S. degree from Vietnam National University, Ho Chi Minh City (VNU-HCM) - Ho Chi Minh City University of Technology in 2017. He pursued M.S. and Ph.D. degrees in Dynamics and Control of Robots at Korea Aerospace University, completing them in August 2023. He is currently a Postdoctoral Research Associate in the Department of Mechanical & Aerospace Engineering at the University of Central Florida, USA. His research interests include Robotics-Control, Biomechanics, Medical Application Robots, Computer Vision, and Deep Learning.

Education
======
+ Postdoctoral Research Associate at the Department of Mechanical & Aerospace Engineering, Sept.2023 - Now.
University of Central  Florida, USA 
+ M.S and Ph.D of Aerospace and Mechanical Engineering, Aug. 2017- Aug.2023.
Korea Aerospace University (Dynamic/Control & Vision/Deep Learning)
+ Bachelor of Mechanical Engineering, Aug. 2012 - May. 2017
Viet Nam National University Ho Chi Minh City (VNU-HCM)-Ho Chi Minh City University of Technology  (Honors Program)

Work
======
+ BM Windows - Coteccons Construction, Apr. 2017- Aug. 2017
  A design engineer


For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Articles
======
1. Nguyen, S., Ramezani, S., & Choi, H. (2025, May). Design of a Semi-Active Ankle Foot Prosthesis Using a Pneumatic and Hydraulic Hybrid for Stiffness and Energy Timing Control. In 2025 International Conference On Rehabilitation Robotics (ICORR) (pp. 358-363). IEEE. [this template]

1. Gitifar, Siavash, Sy Nguyen, and Hwan Choi. "Mantis Shrimp-Inspired Quasi Passive Ankle-Foot Prosthesis." In 2025 International Conference On Rehabilitation Robotics (ICORR), pp. 1530-1535. IEEE, 2025. Link

1. Nguyen, Van Sy, Bohyun Hwang, Byungkyu Kim, and Jay Hoon Jung. "An End-to-End Learning-based Control Signal Prediction for Autonomous Robotic Colonoscopy." IEEE Access (2023). Link

1. Nguyen, Van Sy, Hyunseok Kim, and Dongjun Suh. "Attention Mechanism-Based Bidirectional Long Short-Term Memory for Cycling Activity Recognition Using Smartphones." IEEE Access 11 (2023): 136206-136218. Link
1. Nguyen, V. S., Hwang, B., Lee, S., Kim, S., & Kim, B. (2022). Three Degrees of Freedom-Based Master-Slave Uterine Manipulation Robot System for Laparoscopic Hysterectomy. Journal of Mechanisms and Robotics, 1-40. Link
1. Nguyen Van Sy, Jinwon Jung, Sanghoon Jung, Seonggun Joe, and Byungkyu Kim. "Deployable Hook Retrieval System for UAV Rescue and Delivery." IEEE Access (2021). Link
1. Jung Jinwon, Nguyen Van Sy, Dongkyu Lee, Seonggun Joe, Jaihyuk Hwang, and Byungkyu Kim. "A Single Motor-Driven Focusing Mechanism with Flexure Hinges for Small Satellite Optical Systems." Applied Sciences 10, no. 20 (2020): 7087.   Link
1. Jung Sanghoon, Van Sy Nguyen, Byungkyu Kim, and Taeyoung An. "Design and test of cable based airborne capture mechanism for drone." Journal of Aerospace System Engineering 14, no. 3 (2020): 10-16.   Link


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
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

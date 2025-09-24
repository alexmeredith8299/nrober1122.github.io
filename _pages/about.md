---
permalink: /
title:
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
homepage_feature_row:
  - image_path: publications/rober2024carv.gif
    title: "Refinement Algorithms for Safety Certification"
  - image_path: publications/rober2022backward.png
    title: "Backward Reachability for Neural Feedback Loops"
  - image_path: publications/rober20223d.png
    title: "Control of Underwater Vehicles"
---

I am currently a fifth-year PhD student in [MIT's Department of Aeronautics and Astronautics](https://aeroastro.mit.edu/) working in the [Aerospace Controls Lab](https://acl.mit.edu/) with Professor Jonathan How. 
I got my SM and SB degrees in Aerospace Engineering from MIT in 2023 and 2021, respectively.

---

My research seeks to improve **safety** in aerospace and robotics applications by developing algorithms for path planning and control under uncertainty.
I work on **distributionally robust control** for stochastic systems, often using **covariance steering** as an underlying tool. 
My goal is to develop autonomous systems that can operate safely and efficiently in uncertain environments where safety is critical. 
I am particularly interested in applying my work to space systems and planetary exploration.

Prior to joining ACL in fall 2023, I worked with Professor Kerri Cahoy in MIT's [Space, Telecommunications, Astronomy, and Radiation (STAR) Lab](https://aeroastro.mit.edu/starlab/). 
While in STAR Lab, I studied underactuated control for CubeSats, on-orbit computer vision, and efficient algorithms for collocating weather data from different types of satellites.

{% include homepage_feature_row %}

---

Outside of research, I'm also involved in [AeroAstro departmental Resources for Easing Friction and Stress (dREFS)](https://aeroastro-refs.mit.edu/). As a dREFS, I'm trained in conflict resolution
and volunteer as a peer facilitator helping other graduate students work through challenging situations and access on-campus resources.

---

# Recent News
- January 2025: Our [Workshop on Formal Verification of Control Systems with Neural Network Components](https://sites.google.com/view/wfvnnc/home) will be held as part of the program at ACC 2025.
- December 2024: Our work [Constraint-Aware Refinement for Safety Verification of Neural Feedback Loops](https://arxiv.org/abs/2410.00145) was accepted for publication in L-CSS and will be presented at ACC 2025 in Denver, CO.
- May 2024: I presented our paper [Online Data-Driven Safety Certification for Systems Subject to Unknown Disturbances](https://arxiv.org/abs/2310.19256) at ICRA in Yokohama, Japan.

**[Archived News](/archived-news/)**

<!---
A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

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

---
permalink: /
title:
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
homepage_feature_row:
  - image_path: publications/nfls.png
    title: "Neural Feedback Loop Verification"
  - image_path: publications/cadrl_stata.gif
    title: "Socially Aware Motion Planning"
  - image_path: publications/jackal_offroad_small.png
    title: "High-Speed Off-Road Navigation"
---

I am currently an Assistant Professor at Northeastern University, with a joint appointment in the Department of Electrical & Computer Engineering and the Khoury College of Computer Sciences.
I direct the [**Autonomy & Intelligence Laboratory**](https://neu-autonomy.github.io/lab_website) at Northeastern University.

---

<span style="color:blue">**Prospective Lab Members:**</span> Please take a look at [this page](https://neu-autonomy.github.io/lab_website/joinus) to see our current openings and express your interest using the relevant form. Unfortunately, I cannot respond to every email. Instead, by entering your info in the correct form, I can take a closer look when I am looking to hire for that position.

---

My research lies at the intersection of robotics, deep learning, and control theory, with the goal of developing **certifiable learning machines**.
This means creating robots that discover how to do cool behaviors -- with guarantees on safety, reliability, and efficiency.
Some specific techniques of interest are: reinforcement learning (RL), reachability analysis, learning cost-to-go functions,  bridging semantic perception and motion planning, and model predictive control (MPC).
A key application area of interest is **navigation in challenging environments**, such as off-road (e.g., forests, deserts) and alongside humans (e.g., on busy sidewalks, in crowded buildings).

Previously, I was a Visiting Faculty Researcher with Google's [People + AI Research (PAIR)](https://research.google/teams/brain/pair/) team, developing novel techniques for explainable and trustworthy AI.
Before that, I was a Research Scientist and Postdoctoral Associate at the MIT Department of Aeronautics and Astronautics, working on the [DARPA RACER](https://www.darpa.mil/news-events/2022-01-13) program, the [ARL SARA](https://www.arl.army.mil/business/collaborative-alliances/current-cras/sara-cra/sara-overview/) program, and advancing the field of certifiable learning.
I received the PhD (2020), SM (2017), and SB (2015) degrees from MIT in Mechanical Engineering.

---

{% include homepage_feature_row %}

Selected Awards
------
- Runner-Up: Best Paper Award ([1st Workshop on Formal Verification of Machine Learning, ICML 2022](https://www.ml-verification.com/home))
- Editors' Top 5 Published Articles of 2021 (IEEE Access)
- Winner: Best Paper Award on Cognitive Robotics (IROS 2019)
- Winner: Best Student Paper (IROS 2017)
- Finalist: Best Paper Award on Cognitive Robotics (IROS 2017)
- Finalist: Best Multi-Robot Systems Paper (ICRA 2017)
- iCampus Student Prize Winner for [ofcourse.mit.edu](https://ofcourse.mit.edu)

Recent Talks
------

<div class="row">
    <div class="col-sm-6" align="center">
        <h5 class="section-heading">Certifiable Learning Machines (Sep. 2022)</h5>
        <iframe width="356" height="200" src="https://www.youtube.com/embed/CaBBSDjQ-zM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="display: block;"></iframe>
    </div>
    <div class="col-sm-6" align="center">
        <h5 class="section-heading">Tutorial on NN Verification in Control (Dec. 2021)</h5>
        <iframe width="356" height="200" src="https://www.youtube.com/embed/juiyRPUwetM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="display: block;"></iframe>
    </div>
    <div class="col-sm-6" align="center">
        <h5 class="section-heading">PhD Thesis Defense (June 2020)</h5>
        <iframe width="356" height="200" src="https://www.youtube.com/embed/S_I7MrOgyY8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="display: block;"></iframe>
    </div>
</div>

--->

---
permalink: /
title: "Welcome to my personal page."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a computer professional undergraduate, will graduate in June 2025, I studied at henan normal university college of computer and information engineering (https://www.htu.edu.cn/cs/main.htm), my research interests include language model, automatic driving, human-computer interaction, computer vision.

Educational experience
======
2021.09--2025.06       Henan Normal University                                    undergraduate\
2023.10--Present       University of Wisconsin-Milwaukee                          Research assistant\
2023.11--2024.04       School of Vehicle and Delivery, Tsinghua University        INTERN\
2024.04--Present       Institute of Automation, Chinese Academy of Sciences       INTERN

Project experience
======
1. Research on Autonomous Driving's Perception Challenges in Special Situations.
Intern, Advisor: Dr. Yonglin Tian, Institute of Automation, Chinese Academy of Sciences.
•	Collected autonomous driving case data and used the MMDetection and MMDetection3D frameworks, trained autonomous driving perception solutions released at top conferences by mainstream models, like SparseBEV.
•	Identified several drawbacks in mainstream solutions, leading to the creation of a specialized dataset to address these gaps.
•	Planned to optimize mainstream autonomous driving models based on the findings and the newly developed dataset. 
2. Mental Health Agent System Based on Large Language Model.
Research assistant, Advisor: Prof. Jiangtao Gong, Tsinghua University.
•	Developed a large language model system to automatically address psychological issues and implement superego functionalities.
•	Collected data through interviews and surveys to create datasets with personal characteristics, and constructed personalized response methods using RAG.
•	Built the RedisVL vector library to reduce LLM response return time.
3. Interpretable Multi-modal Perception for Intelligent Driving Based on Information Theory.
Research assistant, Advisor: Prof. Xinyu Zhang & Postdoctoral Shiyan Zhang, Tsinghua University.
•	Proposed a new measurement method of loss and a complementary training strategy to enhance perception models’ ability to handle abnormal data in complex traffic scenarios.
•	Improved the recognition accuracy of cars, pedestrians, and bicycles by 3% using the new complementary training strategy as a plug-and-play module.
•	Implemented Eloss to deviate from standard values by more than 100 times in exception data, produce different values for similar but different types of exceptions, and accurately detect abnormal data while maintaining stable model performance. 
4. Large-model Autonomous Driving Application Based on Federated Learning.
Research assistant, Advisor: Prof. Shuaiqi(Roger) Shen, University of Wisconsin-Milwaukee.
•	Built a personalized autonomous driving decision system by converting NuSence datasets to text and utilizing federated learning.
•	Fused the obtained data with the central open-source model to meet personalized driving needs.
•	Constructed data sets with strong colors to form quantitative information of indicators, demonstrating that personalized driving styles had significant effects after federated learning.
5. Classroom Participation Judgment Based on Multi-modal Feature Fusion.
Leader, Advisor: Prof. Dong Liu, Dean of Computer & Information Engineering School & Prof. Hui Liu, Henan Normal University.
•	Constructed an evaluation system for students' classroom participation based on facial expressions, movement behavior, and head posture.
•	Utilized XGBoost and ResNet residual neural network and Perspective-n-Point algorithm to analyze and judge necessary information during lessons.
•	Found that students using the system scored 20% higher on average in their finals.

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

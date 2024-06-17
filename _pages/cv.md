---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Computer Science, Henan Normal University, 2025

Search experience
======
* 2022.3--2024.6: Undergraduate Leader
   * Henan Key Laboratory of Educational Artificial Intelligence and Personalized Learning

* 2023.10--Present: Research Assistant
  * University of Wisconsin-Milwaukee 

* 2023.11--2024.04: Intern
  * School of Vehicle and Delivery, Tsinghua University 

* 2024.04--Present: Intern
  * Institute of Automation, Chinese Academy of Sciences

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Project experience
======
1. Research on Autonomous Driving's Perception Challenges in Special Situations.\
Intern, Advisor: Dr. Yonglin Tian, Institute of Automation, Chinese Academy of Sciences.\
•	Collected autonomous driving case data and used the MMDetection and MMDetection3D frameworks, trained autonomous driving perception solutions released at top conferences by mainstream models, like SparseBEV.\
•	Identified several drawbacks in mainstream solutions, leading to the creation of a specialized dataset to address these gaps.\
•	Planned to optimize mainstream autonomous driving models based on the findings and the newly developed dataset. 
2. Mental Health Agent System Based on Large Language Model.\
Research assistant, Advisor: Prof. Jiangtao Gong, Tsinghua University.\
•	Developed a large language model system to automatically address psychological issues and implement superego functionalities.\
•	Collected data through interviews and surveys to create datasets with personal characteristics, and constructed personalized response methods using RAG.\
•	Built the RedisVL vector library to reduce LLM response return time.
3. Interpretable Multi-modal Perception for Intelligent Driving Based on Information Theory.\
Research assistant, Advisor: Prof. Xinyu Zhang & Postdoctoral Shiyan Zhang, Tsinghua University.\
•	Proposed a new measurement method of loss and a complementary training strategy to enhance perception models’ ability to handle abnormal data in complex traffic scenarios.\
•	Improved the recognition accuracy of cars, pedestrians, and bicycles by 3% using the new complementary training strategy as a plug-and-play module.\
•	Implemented Eloss to deviate from standard values by more than 100 times in exception data, produce different values for similar but different types of exceptions, and accurately detect abnormal data while maintaining stable model performance. 
4. Large-model Autonomous Driving Application Based on Federated Learning.\
Research assistant, Advisor: Prof. Shuaiqi(Roger) Shen, University of Wisconsin-Milwaukee.\
•	Built a personalized autonomous driving decision system by converting NuSence datasets to text and utilizing federated learning.\
•	Fused the obtained data with the central open-source model to meet personalized driving needs.\
•	Constructed data sets with strong colors to form quantitative information of indicators, demonstrating that personalized driving styles had significant effects after federated learning.
5. Classroom Participation Judgment Based on Multi-modal Feature Fusion.\
Leader, Advisor: Prof. Dong Liu, Dean of Computer & Information Engineering School & Prof. Hui Liu, Henan Normal University.\
•	Constructed an evaluation system for students' classroom participation based on facial expressions, movement behavior, and head posture.\
•	Utilized XGBoost and ResNet residual neural network and Perspective-n-Point algorithm to analyze and judge necessary information during lessons.\
•	Found that students using the system scored 20% higher on average in their finals.



  

---
layout: project_page
permalink: /

title: "NBA3D: Neighbor-Based Confidence Adjustment for 3D Rare Object Detection Using LiDAR"
authors:
  - name: "Jooyoung Lee"
    
    affiliation: 1
  - name: "Jaeyoon Lee"
    
    affiliation: 1
  - name: "Jongwon Choi"
    url: "https://scholar.google.co.kr/citations?user=F3u9qHcAAAAJ&hl=ko"
    affiliation: 1
  
affiliations:
  - id: 1
    school: "Chung-Ang University"


homepage: https://www.vilab.cau.ac.kr/
---

<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
Recent research on LiDAR-based 3D object detectors has
shown strong performance; however, evaluations typically fo-
cus on dominant classes, overlooking rare classes, such as
strollers, which could be critical in real autonomous driv-
ing scenarios. This oversight is problematic because state-
of-the-art 3D object detectors show significantly lower per-
formance on rare classes compared to dominant ones when
trained on both. To address this issue and achieve accurate
3D rare object detection using only LiDAR data, we propose
the Neighbor-Based confidence Adjustment for 3D rare class
predictions (NBA3D). NBA3D utilizes a graph neural net-
work to analyze the surrounding environment of rare class
prediction boxes, enabling more effective distinction between
true positives and false positives based on their local context.
Our approach utilizes both 3D prediction box characteristics
and CLIP-based class semantic information to better contex-
tualize neighboring objects. Various experiments demonstrate
that NBA3D effectively improves the detection performance
of rare class objects, regardless of the type of 3D object de-
tectors used.
        </div>
    </div>
</div>

---





![Framework](/static/images/framework.png)
*Figure 1: A Framework of SCENEDERELLA.*





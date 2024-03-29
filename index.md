---
layout: page
title: Real Attackers Don't Compute Gradients
tagline: Supplementary Resources
description: Website for Real-Gradients
---


Welcome to the website related to the paper _"Real Attackers Don't Compute Gradients": Bridging the Gap between Adversarial ML Research and Practice_ accepted to [IEEE SaTML'23](https://satml.org/). A preprint is [here](https://real-gradients.github.io/resources/satml23_real-gradients.pdf).

We [presented the paper](https://satml.org/) in Raleigh (NC, USA) in February 2023! [[Slides](https://real-gradients.github.io/resources/satml23_slides.pdf)] [[Poster](https://real-gradients.github.io/resources/satml23_poster.pdf)]

You can watch the presentation in the video below: 

<iframe width="560" height="315" src="https://www.youtube.com/embed/hDz3xWAEV_o?rel=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


---

### Summary: what is our (position) paper about?

We aim to spearhead more impactful research in the context of Adversarial Machine Learning (ML). In the last decade, real-world deployments of ML have skyrocketed; however, despite thousands of papers showing the vulnerability of ML models to various security violations, practitioners still see this research domain with skepticism. 

We believe that a stronger connection between adversarial ML research and practice would greatly benefit our society, as it will lead to an improved security of _operational_ ML systems. To strengthen such a connection, we:
* **present three real-world case studies**, fostering the contribution of large companies, elucidating some aspects of ML-systems' security that may be _overlooked_ by researchers;
* **review all recent papers published in top-conferences**, highlighting positive trends as well as some confusing _inconsistencies_;
* **state five positions** that, if embraced, would _build a bridge_ between adversarial ML research and practice. 

Our paper is enriched with discussions, considerations and thorough analyses on all the abovementioned points -- provided in a (lengthy!) Appendix culminating with a comprehensive table that summarizes the state-of-the-art. 

#### Acknowledgement

Our work is the result of a joint effort of researchers and practitioners. However, the _idea_ of our paper was born slightly after the Dagstuhl Seminar on "[Security of Machine Learning](https://www.dagstuhl.de/en/program/calendar/semhp/?semnr=22281)", held in July 2022. During this event (which most of the paper's authors attended to), many discussions were held on the underlying topic tackled by the paper. Thus, the authors would like to thank all participants (and organizers!) of this Dagstuhl Seminar, without which our paper would have never come to be.

---

### Extra Resources

Alongside our main paper, our contributions also cover the following additional resources:

* **Screenshots** of the 100 "evasive" phishing webpages -- described in Section III.B [[Archive](https://real-gradients.github.io/resources/data/caseStudy2_screenshots.zip) (~17MB) and [SHA256](https://real-gradients.github.io/resources/data/caseStudy2_screenshots-SHA256)]
* **Source Material** of our analysis of the 2021 MLSEC antiphishing challenge -- described in Section III.C [[Notebook](https://github.com/real-gradients/real-gradients.github.io/blob/main/resources/code/generate_plots.ipynb) and [Data](https://github.com/real-gradients/real-gradients.github.io/blob/main/resources/code/antiphish_top_submission_timing-anon.csv)] [[Submissions](https://1drv.ms/u/s!AiRbxLvsK4bMojLBxyzDoY3zY0CJ?e=nAQYF1)  (~500MB) and [SHA256](https://real-gradients.github.io/resources/data/caseStudy3_submissions-SHA256)]
* **List of Excluded Papers** that entail ML and Cybersecurity, but which fell outside our scope and were not included in our literature review -- refer to Appendix B-A [[List](https://real-gradients.github.io/resources/leftout_papers)]

If you use any of such resources, we kindly ask you to cite our paper with the following BibTeX entry:
```
@inproceedings{apruzzese2023realgradients,
  title={"Real Attackers Don't Compute Gradients": Bridging the Gap between Adversarial ML Research and Practice},
  author={Apruzzese, Giovanni and Anderson, Hyrum S. and Dambra, Savino and Freeman, David and Pierazzi, Fabio and Roundy, Kevin A.},
  booktitle={Proceedings of the 1st IEEE Conference on Secure and Trustworthy Machine Learning (SaTML)},
  year={2023},
} 
```

#### Contact
Feel free to reach out to us! You can contact either the primary author, [Giovanni Apruzzese](mailto:giovanni.apruzzese@uni.li), or any of the other authors (the contact references are at the bottom of this webpage). You can also post a comment on the [discussion page](https://github.com/real-gradients/real-gradients.github.io/discussions/) of this GitHub Repository.

---

### Follow-up

Four of the authors (Giovanni Apruzzese, Hyrum Anderson, David Freeman, Fabio Pierazzi) held a 1-hour [webinar](https://us06web.zoom.us/webinar/register/9716757880895/WN_b5VZdl8jQ4uMJzDTe0y1LQ) (organized by [Robust Intelligence](https://www.robustintelligence.com/)) in which they discussed some of the paper's main takeaways. The webinar can be watched at the following link: [YouTube](https://www.youtube.com/watch?v=6ZQli55AKwQ)
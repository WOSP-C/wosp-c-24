## 9th WOSP-C 2024

The Workshop on Challenges in Performance Methods for Software Development (WOSP-C) serves as a forum for discussions on novel and unresolved challenges in the field of software performance engineering.
The workshop encompasses topics such as performance assurance processes, the interplay between performance and software architecture, performance testing and debugging, and performance monitoring. The primary areas of interest for the workshop remain consistent with previous editions, but this edition scope will also extend to include additional novel topics.


## Program
The 9th WOSP-C 2024 is co-located with ICPE 2024, and it will be held on May 7.

| Time (GMT+1)      | Title |
|----------------------|-------|
| 9:00am       | Welcome: Heng Li, and Luca Traini |
| 9:05am      | **Keynote**: Closing the Loop: Building Self-Adaptive Software for Continuous Performance Engineering - **Marin Litoiu**, York University |
| 9:50am      | Marcel Lütke Dreimann, Birte Friesel and Olaf Spinczyk. __HetSim: A Simulator for Task-based Scheduling on Heterogeneous Hardware__|
| 10:10am       | Josef Mayrhofer. __Establish a Performance Engineering Culture in Organizations__|
| 10:30am      | Coffee Break ☕️ | 
| 11:00am       | **Keynote**:  25+ years of Software Performance: From Integrated System Modelling to ML-based Analysis, What’s Next? - **Vittorio Cortellessa**, University of L’Aquila |
| 11:45am       |  Rares Dobre, Zifeng Niu and Giuliano Casale.	__Approximating Fork-Join Systems via Mixed Model Transformations__|
| 12:05pm         | Jonathan Will, Dominik Scheinert, Seraphin Zunzer, Jan Bode, Cedric Kring and Lauritz Thamsen.	__Privacy-Preserving Sharing of Data Analytics Runtime Metrics for Performance Modeling__|
| 12:17pm         | Andreas Brunnert.	__Green Software Metrics__|

### Keynote

**Marin Litoiu**, York University

_Biography_: 

Marin Litoiu is a Professor of Software Engineering in the Department of Electrical Engineering and Computer Science and in the School of Information Technology, York University. He is also a Fellow of the Canadian Academy of Engineering. Dr. Litoiu leads the Adaptive Software Research Lab and focuses on making large software systems more versatile, resilient, energy-efficient, self-healing and self-optimizing. His research won many awards including the IBM Canada CAS Research Project of the Year Award,  the IBM CAS Faculty Fellow of the Year Award for his “impact on IBM people, processes and technology,” three Best Paper Awards and two Most Influential Paper Awards.  Prior to joining York University, Dr. Litoiu was a Research Staff member with the Centre for Advanced Studies in the IBM Toronto Lab where he led the research programs in software engineering and autonomic computing. He received the Canada NSERC Synergy Award for Innovation in recognition for these collaborative university/industry activities. He was also recipient of the IBM Outstanding Technical Contribution Award for his research vision on Cloud Computing. Dr. Litoiu   is one of the founders of the SEAMS Symposium series—ACM/IEEE Software Engineering for Adaptive and Self-Managing Systems. Dr. Litoiu is also the Scientific Director of "Dependable Internet of Things Applications (DITA)," an NSERC CREATE program.


**_Closing the Loop: Building Self-Adaptive Software for Continuous Performance Engineering_**

_Abstract_: 

Cloud computing and cloud-native platforms have rendered runtime environments more malleable. Simultaneously, the growing demand for flexible and agile software applications and services has driven the emergence of self-adaptive architectures. These architectures, in turn, facilitate software performance modeling, tuning, optimization, and scaling in a continuous manner, blurring the boundary between development-time and run-time. Self-adaptive software employs feedback loop controllers inspired by control theory or variations of the Monitoring-Analysis-Planning-Acting (MAPE) architecture. Whether implemented in a centralized or decentralized manner, most controllers utilize performance models that are learned or tuned at run-time. This shift implies that software is designed to be observable and controllable during execution, presupposing the co-design of software applications and their runtime controllers. 
This talk commences with a succinct overview of the evolution of self-adaptive software, accentuating key milestones along the journey. Subsequently, recent advancements in software performance modeling at runtime and the role of learning-enabled performance management during software operation are presented. 
Two recent works are highlighted: one focusing on constructing robust performance models to sustain continuous operation and deployment of cloud-native software, and the other on utilizing multimodal models for performance anomaly detection. The former supports cloud operations like continuous deployment of co-located applications, migration, consolidation of services, or scaling in response to workloads or interferences. The latter is tailored to support performance anomaly detection, localization, and identification of root causes, facilitating swift remediation of faults using generative AI. The final segment of the talk delves into current challenges in developing self-adaptive systems, presenting insights from a recent survey on the state of self-adaptive software in the industry and the challenges perceived by practitioners.

### Keynote

**Vittorio Cortellessa**, University of L’Aquila

_Biography_: 

Vittorio Cortellessa is Professor at the Department of Computer Science and Engineering, and Mathematics of University of L’Aquila. He had received his Ph.D. in Computer Science at University of Roma Tor Vergata in 1995. Between 1996 and 1999 he held postdoc positions at the same institution and at European Space Agency. In 2000 and 2001 he has been Research Assistant Professor at the Computer Science and Electrical Engineering Department of West Virginia University. Since 2022 he is at University of L’Aquila. His main research interests are in the areas of Software Performance, Software Reliability, and Model-Driven Engineering. He has published more than 120 papers on international conferences and journals in these areas, and he has co-authored a monographic book on Software Performance. He has served and serves in program committees and editorial boards of conference and journals in the Software Engineering domain. He is currently Co-Chair of the Steering Committee of ACM/SPEC International Conference on Performance Engineering (ICPE) and member of the Steering Committee of IEEE International Conference on Software Architecture (ICSA). More information at: http://people.disim.univaq.it/cortelle/.


**_25+ years of Software Performance: From Integrated System Modelling to ML-based Analysis, What’s Next?_**

_Abstract_: 

A new era has been opened at the end of last century in the performance analysis research area, when an explicit and independent role has started to be given to software in performance analysis of computing systems. Indeed, software has moved from being a monolithic element, strictly dependent on the platform where it is deployed and exclusively aimed at producing values to parameterize a platform model, to become an independent model itself, with its own components and interactions. This change has impacted all fields of this research area, such as: modeling languages, processes for analysis and synthesis of software models, platform model parameterization, performance model solution techniques, interpretation of results, benchmarking and performance testing. It has also represented one of the triggers that lead to the birth of a research community around the computing system performance issues strictly related to software aspects. Indeed, in 1998 the first ACM Workshop on Software and Performance (WOSP) took place, with the aim of getting together researchers and practitioners of software area with the ones of the performance area, so to offer a playground where different skills and expertise could join and originate a new vision on the role of software in performance assessment. This talk attempts to reconstruct the road of software performance research that has started at the time of the first WOSP event in 1998 down to today events (i.e., ICPE conference, WOSP-C and other workshops). The spirit of the talk is to observe the evolution of this research area, including successful and (apparently) unsuccessful directions. Some promising directions will be tentatively sketched by “standing on the shoulders of giants”.

---

### Accepted papers


Marcel Lütke Dreimann, Birte Friesel and Olaf Spinczyk.	**HetSim: A Simulator for Task-based Scheduling on Heterogeneous Hardware**

Josef Mayrhofer.	**Establish a Performance Engineering Culture in Organizations**

Rares Dobre, Zifeng Niu and Giuliano Casale.	**Approximating Fork-Join Systems via Mixed Model Transformations**

Jonathan Will, Dominik Scheinert, Seraphin Zunzer, Jan Bode, Cedric Kring and Lauritz Thamsen.	**Privacy-Preserving Sharing of Data Analytics Runtime Metrics for Performance Modeling**

Andreas Brunnert.	**Green Software Metrics**

---



## Call for paper

We welcome contributions that foster meaningful discussions on both foundational and novel topics within the performance engineering community.

This workshop edition will explore topics related to:

- Model-based performance analysis
- Empirical studies in performance engineering 
- Performance monitoring
- AIOps for performance assurance
- Performance testing and debugging
- Performance engineering in Agile/DevOps software processes
- Green software and energy efficiency
- Performance engineering for Machine Learning systems
- Machine learning for performance engineering tasks
- Industry reports on performance engineering challenges and experience


## Organizing Committee
 
 - Luca Traini, University of L'Aquila, Italy
 - Heng Li, Polytechnique Montréal, Canada

## Technical Program Committee

- Andre Bondi, Software Performance and Scalability Consulting LLC, USA
- Jinfu Chen, Wuhan University, China
- Tse-Hsun (Peter) Chen, Concordia University, Canada
- Diego Elias Costa, Concordia University, Canada
- Marios Fokaefs, York University, United Kingdom
- Sebastian Frank,  Universität Hamburg, Germany
- Sören Henning, Johannes Kepler University/Dynatrace, Austria
- Emilio Incerto, IMT School for Advanced Studies, Italy
- Michele Tucci, University of L’Aquila, Italy


## Important dates
- Paper submission: February 7, 2024
- Author notification: March 5, 2024

## Submission

Authors are invited to submit original, unpublished papers that are not being considered in any other venue. Papers should be in the ACM format. They should describe research results, experience, visions or new initiatives. This year, we accept submissions as full (8 pages), short (4 pages), and vision or work-in-progress (2 pages) papers. Page limits include references. Papers should be submitted via Easychair at [EasyChair WOSP-C 2024](https://easychair.org/conferences/?conf=icpe2024) (by selecting the "author" role, then "New Submission", and then the WOSP-C 2024 track).

ACM templates may be found [here](https://www.acm.org/publications/proceedings-template). Presented papers will be published in the ICPE 2024 companion proceedings, which will be published by ACM and included in the ACM Digital Library. Authors are required to adhere to the ACM Policy and Procedures on Plagiarism, as well as to the ACM Policy on Prior Publication and Simultaneous Submissions. Concurrent submission of the same work to ICPE 2024 and to WOSP-C or any other ICPE 2024 workshop is not permitted.

_By submitting your article to an ACM Publication, you are hereby acknowledging that you and your co-authors are subject to all ACM Publications Policies, including ACM's new Publications Policy on Research Involving Human Participants and Subjects. Alleged violations of this policy or any ACM Publications Policy will be investigated by ACM and may result in a full retraction of your paper, in addition to other potential penalties, as per ACM Publications Policy._

_Please ensure that you and your co-authors obtain an ORCID ID, so you can complete the publishing process for your accepted paper.  ACM has been involved in ORCID from the start and we have recently made a commitment to collect ORCID IDs from all of our published authors.  The collection process has started and will roll out as a requirement throughout 2022.  We are committed to improve author discoverability, ensure proper attribution and contribute to ongoing community efforts around name normalization; your ORCID ID will help in these efforts._

## Contact

[WOSPC2024@easychair.org](mailto:WOSPC2024@easychair.org)


## Past WOSP-C editions

[WOSP-C 2023](https://wosp-c.github.io/wosp-c-23/)

[WOSP-C 2022](https://wosp-c.github.io/wosp-c-22/)

[WOSP-C 2021](https://wosp-c-21.github.io/)

[WOSP-C 2020](https://wosp-c.github.io/wosp-c-20/)

[WOSP-C 2018](http://wosp-c.uib.es/)

[WOSP-C 2017](https://wosp-c.spec.org/)

[WOSP-C 2016](http://wosp-c.ipd.kit.edu/)

[WOSP-C 2015](http://wosp-c.ipd.kit.edu/wosp_c15/home/index.html)


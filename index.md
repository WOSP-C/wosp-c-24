## 7th Wosp-C 2022

The WOSP-C series of workshops on challenges in software performance has taken place at every ICPE except ICPE 2019 since ICPE 2015. It provides a forum for the discussion of emerging or unaddressed challenges in software and performance, including challenges in developing software to be performant, concurrent programming issues, performance and architecture, performance measurement, cloud performance, and testing. Its purpose was to open up new avenues of research on methods for software developers to address performance challenges. The software world is changing, and there are new challenges.

## Program April 10th, 2022 2PM - 6PM (CEST)

| time (PM CEST)| title |
| --- | ---- |
| 2:00 - 2:05 | Welcome: Catalina Lladó, and Daniele Di Pompeo |
| 2:05 - 3:05 | **Keynote**: Quantitative Evaluation of Non-Markovian systems: A Model Driven Engineering Approach - _Laura Carnevali (University of Florence)_ |
| 3:05 - 3:30 | Samuel Beck, Sebastian Frank, Alireza Hakamian and André van Hoorn. __How is Transient Behavior Addressed in Practice? Insights from a Series of Expert Interviews__|
| 3:30 - 3:55 | Martina Rapp, Max Scheerer and Ralf Reussner. __Design-time Performability Optimization of Runtime Adaptation Strategies__ |
| 3:55 - 4:10 | BREAK | 
| 4:10 - 4:35 | Siyu Zhou and Murray Woodside.	__A Multiserver Approximation for Cloud Scaling Analysis__ |
| 4:35 - 4:55 | Samyak S Sarnayak, Aditi Ahuja, Pranav Kesavarapu, Aayush Naik, Santhosh Kumar V and Subramaniam Kalambur.	__Analysis of Garbage Collection Patterns to Extend Microbenchmarks for Big Data Workloads__|
| 4:55 - 6:00 | **Keynote**: Software Performance Modeling: Then, Now and Beyond _Connie U. Smith (L&S Computer Technology, Inc.)_ | 


### KEYNOTE (45 min + 15 min Q&Discussion)

#### Laura Carnevali:

**Short Bio**: Laura Carnevali is Associate Professor of Computer Science with the Department of Information Engineering of the University of Florence,
Italy. Her research focuses on novel approaches for quantitative modeling and evaluation of concurrent non-Markovian systems, with
specific interest in hierarchical modeling formalisms, compositional solution techniques, and practices of Model Driven Engineering (MDE) and
automated model transformation. She has applied these methods to a variety of fields notably including:

 - performability evaluation of railway signalling systems;
 - performability evaluation of intelligent transportation systems;
 - performability evaluation of repair procedures for gas and water distribution networks;
 - input generation in real-time testing of stochastic systems;
 - activity recognition in ambient assisted living.

She has also worked on correctness verification of concurrent timed systems, with specific interest in verification of hierarchical scheduling systems, and integration of formal methods in the development life cycle of real-time software. 

**_Quantitative Evaluation of Non-Markovian systems: A Model Driven Engineering Approach_**

Non-Markovian models enable the representation of complex cyber-physical systems including synchronous phenomena (e.g., periodic arrivals, timeouts, offsets) and non-exponential durations possibly with bounded support (e.g., delays in transportation systems, minimum and maximum execution times in real-time systems), notably facilitating fitting of stochastic parameters from observed data. Solution techniques for quantitative evaluation of these models can give decisive support to system development by enabling early verification of design choices and assessment of non-functional requirements. Effective exploitation of this potential faces both practical and theoretical complexities. On the one hand, the activity of model construction must fit the context of use, automatically generating models from artifacts of the industrial practice and from actual operational data. On the other hand, the 
analysis needs to be able to afford complexity in terms of the size and class of the stochastic processes underlying the models generated automatically without manual intervention.

This talk presents a Model Driven Engineering (MDE) approach to performance evaluation of multimodal urban intersections, supporting automated transformation of semi-formal artifacts of the Unified Modeling Language (UML) into stochastic models that can be efficiently analyzed. On the one hand, a meta-model of the system captures structural and behavioral information on the tram flows and the car flows that cross at the intersection. On the other hand, transient analysis of a microscopic model of tram traffic, defined by Stochastic Time Petri Nets (STPNs), is combined with analytical solution of a set of ordinary differential equations characterizing the behaviour of a macroscopic model of car traffic, defined by finite-capacity queues, providing the expected number of queued cars over time for intervals of arbitrary duration. Validation of the approach in terms of accuracy and complexity is performed with respect to a traffic simulator using a large-size benchmark. Effectiveness of the solution is demonstrated on relevant use cases in operation and management of urban transportation systems.

#### Connie U. Smith:

**Short Bio**: Dr. Connie U. Smith, CTO of L&S Computer Technology, Inc., is known for her work in defining the field of Software Performance Engineering (SPE) and integrating SPE into the development of new software systems. Dr. Smith received a BA in mathematics from the University of Colorado and MA and Ph.D. degrees in computer science from the University of Texas at Austin. She is the author of the original SPE book, Performance Engineering of Software Systems, published in 1990 by Addison-Wesley, co-author of Performance Solutions: A Practical Guide to Building Responsive, Scalable Software also published by Addison-Wesley, and approximately 100 scientific papers. She is the creator of the SPE•ED™ performance engineering tool. She has over 25 years of experience in the practice, research and development of the SPE performance prediction techniques. Her research interests include computer performance modeling and evaluation, performance patterns and antipatterns, software development, tool interoperability, and tool development.  

Dr. Smith received the Computer Measurement Group’s prestigious AA Michelson Award for technical excellence and professional contributions for her SPE work. The computer science department at the University of Texas at Austin recognized the widespread impact of her work in conjunction with a 2000 symposium. She frequently serves on conference and program committees, including chairing the First International Workshop on Software and Performance (WOSP) in 1998 that became the International Conference on Performance Engineering (ICPE) in 2010. She served as an officer of ACM SIGMETRICS for 10 years, is a past ACM National Lecturer, and has been an active member of the Computer Measurement Group for Performance Professionals (CMG). Recently she led a research effort funded by the US Air Force to develop prototype tools to automate the performance modeling of software and system designs with focus on IoT and Real Time Embedded Systems. Additional information and a list of publications may be found at www.spe-ed.com.

**_Software Performance Modeling: Then, Now and Beyond_**

Software Performance Models (SPM) represent details of software architecture and design, and predict performance of the associated systems under varying workloads and configurations. SPM have been used for over 50 years, and have evolved significantly over that time. Early software was single-threaded and executed on a single processor. As computing power evolved, the software architecture and design grew more complex, and the modeling technology followed. In the past, computer and software systems were expensive and thus typically found only in large installations and in mission-critical systems. Today, software is ubiquitous; it is found in almost every type of system deployed from IT and web-based systems, to scientific, computationally intensive systems, to automobiles, appliances, IoT, and many others. What do these changes mean for performance models for today’s systems and those of the future? What changes are required for the modeling technology, and for the use of models for Software Performance Engineering (SPE) in general? 

This talk considers the evolutionary role of performance models in SPE with an eye to the future. Will performance modeling in software development still play a role, and if so, what challenges do we face? We consider early performance model technology and how diﬀerent models were used depending on the types of systems deployed. Then, we explore the adaptation of the model technology and the role of models as software evolved. Finally, we consider current systems and those envisioned in the near future to identify what role performance models might fill and the resulting adaptations needed. These observations suggest both research areas and educational requirements for researchers and performance engineers in the future.

## Accepted Papers (20 min + 5 min Q&A)

 - Samuel Beck, Sebastian Frank, Alireza Hakamian and André van Hoorn. __How is Transient Behavior Addressed in Practice? Insights from a Series of Expert Interviews__
 - Martina Rapp, Max Scheerer and Ralf Reussner. __Design-time Performability Optimization of Runtime Adaptation Strategies__
 - Siyu Zhou and Murray Woodside.	__A Multiserver Approximation for Cloud Scaling Analysis__
 - Samyak S Sarnayak, Aditi Ahuja, Pranav Kesavarapu, Aayush Naik, Santhosh Kumar V and Subramaniam Kalambur.	__Analysis of Garbage Collection Patterns to Extend Microbenchmarks for Big Data Workloads__

---

## Call for paper

WOSP-C provides a forum for discussing emerging or unaddressed challenges in software and performance, including challenges in developing software with good performance, concurrent programming issues, performance and architecture, performance measurement, cloud performance, and testing. The main areas of interest of the workshop do not change with respect to previous editions. However, the this year the call for papers will emphasize:

 - Software performance challenges in Empirical Software Performance Engineering (new)
 - Software performance challenges in Machine Learning (new)
 - Machine Learning challenges to Software Performance Engineering (new)
 - Software performance challenges in Cyber-Physical Systems (CPS) and digitization processes
 - Open source challenges to performance

## Organizing Committee
 
 - Catalina M. Lladó, Universitat Illes Balears, Spain  
 - Daniele Di Pompeo, University of L'Aquila, Italy

## Technical Program Committee

 - Catalina M.	Lladó, Universitat Illes Balears,	Co-chair
 - Daniele	Di Pompeo,	Univarsity dell'Aquila, Co-chair
 - Michele	Tucci, Charles University
 - José	Merseguer, Universidad de Zaragoza
 - Vincenzo	Grassi, University of Roma "Tor Vergata"
 - Murray	Woodside, Carleton University
 - André	van Hoorn, University of Hamburg
 - Diego	Perez-Palacin, Linnaeus University
 - Alberto	Avritzer,	eSulabSolutions

## Important dates

| Deadline: Midnight (AOE)                      |     |
|:----------------------------------------------|:---:|
| Paper Submission                              | ~~Jan 25, 2022~~ Jan 31, 2022 |
| Paper Notification of Acceptance              | ~~Feb 15, 2022~~ Feb 25, 2022   |
| Camera-Ready Submission                       | ~~Feb 24, 2022~~ May 4, 2022  |
| Workshop                                      | Apr 10, 2022 |

## Submission

Authors are invited to submit original, unpublished papers that are not being considered in another forum. Papers should be in ACM format. They should describe research results, experience, visions or new initiatives, and not exceed 8 pages in length. They should be submitted via Easychair at

[EasyChair WOSPC2022](https://easychair.org/conferences/?conf=wospc2022)

ACM templates may be found [here](https://www.acm.org/publications/proceedings-template). Presented papers will be published in the ICPE 2022 companion proceedings that will be published by ACM and included in the ACM Digital Library. Authors are required to adhere to the ACM Policy and Procedures on Plagiarism as well as to the ACM Policy on Prior Publication and Simultaneous Submissions. Concurrent submission of the same work to ICPE2022 and to WOSP-C or any other ICPE2022 workshop is not permitted.

## Wosp-C editions

[WOSP-C 2021](https://wosp-c-21.github.io/)

[WOSP-C 2020](https://wosp-c.github.io/wosp-c-20/)

[WOSP-C 2018](http://wosp-c.uib.es/)

[WOSP-C 2017](https://wosp-c.spec.org/)

[WOSP-C 2016](http://wosp-c.ipd.kit.edu/)

[WOSP-C 2015](http://wosp-c.ipd.kit.edu/wosp_c15/home/index.html)


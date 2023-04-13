---
img: ":10249091285_56c3944b28_k.jpg"
---

## 8th WOSP-C 2023

The WOSP-C series of workshops on challenges in software performance has taken place at every ICPE, except ICPE 2019, since ICPE 2015. It provides a forum for the discussion of emerging or unaddressed challenges in software and performance, including challenges in developing software to be performant, concurrent programming issues, performance and architecture, performance measurement, cloud performance, and testing. Its purpose is to open up new avenues for research on methods to address continuously emerging performance challenges. The software world is changing, and new challenges are to be expected.


---

## Program 15th, April 2023

| Time (PM GMT-1)| Title |
| --- | ---- |
| 2:00 - 2:05 | Welcome: Michele Tucci, and Daniele Di Pompeo |
| 2:05 - 3:05 | **Keynote**: Non-Volatile Hardware Transactional Memory: Advancements, Challenges, and Future Directions - _**Paolo Romano**, IST, Lisbon University & INESC-ID_ |
| 3:05 - 3:30 | Vittorio Cortellessa, Luigi Pomante and Vincenzo Stoico. __From UML/MARTE Specifications to ESL HW/SW Co-Design: Early Functional Verification and Timing Validation__|
| 3:30 - 4:00 | BREAK | 
| 4:00 - 4:25 | Sebastian Frank, Julian Brott, Dominik Kesim, Heiko Holz, Matthias Eschhold and André van Hoorn.	__dqualizer: Domain-Centric Runtime Quality Analysis of Business-Critical Application Systems__ |
| 4:25 - 4:50 | David Georg Reichelt, Stefan Kühne and Wilhelm Hasselbring.	__Towards Solving the Challenge of Minimal Overhead Monitoring__|
| 4:50 - 5:15 | Murray Woodside.	__Heuristic Derivation of a Fluid Model from a Layered Queueing Network__|

### Keynote

**Paolo Romano**, IST, Lisbon University & INESC-ID

_Biography_: 

Paolo Romano received his PhD from Rome University "Sapienza" (2007) and his Master degree summa cum laude from Rome University "Tor Vergata" (2002). He is currently an Associate Professor at Técnico (U. Lisboa) and a Researcher at INESC-ID. His research interests include parallel and distributed computing, high performance computing, emerging hardware technologies and hardware-software co-design techniques. In these areas, he published more than 150 papers, receiving 3 best awards, and has coordinated several national and European projects, including a COST Action on Transactional Memory bringing together researchers from 60 institutions and 17 countries. He serves regularly as Program Committee member and reviewer for renowned international conferences and
journals, including DSN, EuroSys, ICDCS, PPoPP,IEEE TKDE, IEEE
TPDS, ACM TOPLAS.

**_Non-Volatile Hardware Transactional Memory: Advancements, Challenges, and Future Directions_**

_Abstract_: 

Transactional memory (TM) has emerged as a powerful paradigm to simplify concurrent programming. Nowadays, hardware-based TM (HTM) implementations are available in several mainstream CPUs (e.g., by ARM, Intel and IBM). Due to their hardware nature, HTM implementations spare the cost of software instrumentation and can efficiently detect conflicts by extending existing cache-coherency protocols. However, their cache-centric approach also
imposes a number of limitations that impact how effectively such systems can be used in practice. 
This talk investigates the challenges that arise when leveraging existing HTM systems in conjunction with another recent disruptive hardware technology, namely Non-Volatile Memory (NVM). NVM, such as Intel Optane DC, provide much higher density than existing DRAM, while attaining competitive performance and pre-serving DRAM’s byte addressability. However, the cache-centric approach adopted by existing HTM implementations raises a crucial problem when these are used in conjunction with NVM: since CPU caches are volatile, existing HTM fail to guarantee that data updated by committed transactions are atomically persisted to NVM. 
I will overview how this problem has been so far tackled in the literature, with a focus on solutions that do not assume ad-hoc hardware mechanisms not provided by current HTM implementations, but that rather rely on hardware-software co-design techniques to ensure consistency on unmodified existing HTM systems. I will conclude by presenting ongoing research directions that depart from state of the art approaches in a twofold way: i) they assume the availability of durable caches, i.e., systems equipped with additional power sources that ensure that cache contents can be safely persisted to NVM upon crashes; ii) they assume a weaker isolation levels at the TM level, namely Snapshot Isolation, which despite being more relaxed than the reference consistency model for TM systems (e.g., opacity), can still ensure correct execution of a wide range of applications while enabling new optimizations to boost the efficiency HTM applications operating on NVM.

---

### Accepted papers

Vittorio Cortellessa, Luigi Pomante and Vincenzo Stoico	**From UML/MARTE Specifications to ESL HW/SW Co-Design: Early Functional Verification and Timing Validation**

David Georg Reichelt, Stefan Kühne and Wilhelm Hasselbring	**Towards Solving the Challenge of Minimal Overhead Monitoring**

Murray Woodside	**Heuristic Derivation of a Fluid Model from a Layered Queueing Network**

Sebastian Frank, Julian Brott, Dominik Kesim, Heiko Holz, Matthias Eschhold and André van Hoorn	**dqualizer: Domain-Centric Runtime Quality Analysis of Business-Critical Application Systems**

_Proceedings_: https://dl.acm.org/doi/proceedings/10.1145/3578245
---

## Call for paper

We encourage contributions that help to discuss challenges on topics that are relevant in the performance community. In this edition, in particular, we would like to focus on the following:

 - Energy efficiency and sustainability
 - Controlled experiment design, data-driven experiments, and diagnostics in empirical studies
 - Data exchange and tools interoperability
 - Model learning and extraction techniques
 - Model validation and calibration
 - Cyber-Physical Systems (CPS) and digitization processes
 - Performance engineering processes encompassing humans in the loop
 - Adoption of performance engineering practices in industry

## Organizing Committee
 
 - Daniele Di Pompeo, University of L'Aquila, Italy
 - Michele Tucci, Charles University, Czech Republic

## Technical Program Committee

- Steffen Becker, University of Stuttgart, Germany
- J. Andres	Diaz-Pace, ISISTAN Research Institute, UNICEN University, Argentina
- Emilio Incerto, IMT School for Advanced Studies Lucca, Italy
- Tse-Hsun Peter Chen, Concordia University, Canada
- André	van Hoorn, University of Hamburg, Germany
- Catalina M. Lladó, University of the Balearic Islands, Spain
- Laura	Carnevali, University of Florence, Italy
- Murray Woodside, Carleton University, Canada
- Andre	Bondi, Software Performance and Scalability Consulting LLC, USA

## Important dates

| Deadline: Midnight (AoE)                      |     |
|:----------------------------------------------|:----|
| Paper Submission                              | ~~January 19~~ January 26, 2023 |
| Paper Notification of Acceptance              | February 13, 2023 |
| Camera-Ready Submission                       | February 20, 2023 |
| Workshop                                      | April 15, 2023 |

## Submission

Authors are invited to submit original, unpublished papers that are not being considered in any other venue. Papers should be in the ACM format. They should describe research results, experience, visions or new initiatives. This year, we accept submissions as full (8 pages), short (4 pages), and vision or work-in-progress (2 pages) papers. Page limits include references. Papers should be submitted via Easychair at

[EasyChair WOSP-C 2023](https://easychair.org/conferences/?conf=icpe2023) <br />
(by selecting the "author" role, then "New Submission", and then the WOSP-C 2023 track)

ACM templates may be found [here](https://www.acm.org/publications/proceedings-template). Presented papers will be published in the ICPE 2023 companion proceedings, which will be published by ACM and included in the ACM Digital Library. Authors are required to adhere to the ACM Policy and Procedures on Plagiarism, as well as to the ACM Policy on Prior Publication and Simultaneous Submissions. Concurrent submission of the same work to ICPE 2023 and to WOSP-C or any other ICPE 2023 workshop is not permitted.

_By submitting your article to an ACM Publication, you are hereby acknowledging that you and your co-authors are subject to all ACM Publications Policies, including ACM's new Publications Policy on Research Involving Human Participants and Subjects. Alleged violations of this policy or any ACM Publications Policy will be investigated by ACM and may result in a full retraction of your paper, in addition to other potential penalties, as per ACM Publications Policy._

_Please ensure that you and your co-authors obtain an ORCID ID, so you can complete the publishing process for your accepted paper.  ACM has been involved in ORCID from the start and we have recently made a commitment to collect ORCID IDs from all of our published authors.  The collection process has started and will roll out as a requirement throughout 2022.  We are committed to improve author discoverability, ensure proper attribution and contribute to ongoing community efforts around name normalization; your ORCID ID will help in these efforts._

## Contact

[wosp-c2023@easychair.org](mailto:wosp-c2023@easychair.org)

## Past WOSP-C editions

[WOSP-C 2022](https://wosp-c.github.io/wosp-c-22/)

[WOSP-C 2021](https://wosp-c-21.github.io/)

[WOSP-C 2020](https://wosp-c.github.io/wosp-c-20/)

[WOSP-C 2018](http://wosp-c.uib.es/)

[WOSP-C 2017](https://wosp-c.spec.org/)

[WOSP-C 2016](http://wosp-c.ipd.kit.edu/)

[WOSP-C 2015](http://wosp-c.ipd.kit.edu/wosp_c15/home/index.html)


---
location: agenda
head:
  title: SDSC Summer Institute Preliminary Agenda
---

* **Lesson material repository**: <https://github.com/sdsc/sdsc-summer-institute-2018>

## MONDAY, August 6th

| Time | **Track 1** _Auditorium_ | **Track 2** _Synthesis Center E-B143_ |
| ---  | --- | --- |
| 8:00 – 8:30AM | Registration, Coffee | |
| 8:30 – 10:15| **Welcome** Michael Norman, Director, SDSC <br/> **Orientation & Introductions** Bob Sinkovits, Director of Scientific Computing Applications, SDSC - Director of the Summer Institute <br/> **How to login to Comet and launch jobs** Mary Thomas, Computational Scientist, SDSC | |
| 10:15 - 10:30 | break | |
| 10:30 - 12PM | **Introduction to version control with `git` and Github** | **Advanced `git` & Github**, Andrea Zonca <br/> You should be already familiar with creating Pull Requests, merging and rebasing branches |
| 12:15 – 1:30 | Lunch at Café Ventanas | |
| 1:30 – 5:00 | **Understanding Comet file systems** Manu Shantharam, Senior Computational Scientist, SDSC <br/> **Understanding performance and obtaining hardware information** Bob Sinkovits <br/> **Introduction to Science Gateways** Subhashini Sivagnanam, Scientific Computing Specialist, SDSC <br/> **Virtual Cluster & Using containers (Singularity)** Trevor Cooper, High Performance Computing Systems Manager, SDSC | |
| 5:30 – 8:30PM | **Reception on 15th floor at The Village** | |

## TUESDAY, August 7th

| Time | **Track 1** _Auditorium_ | **Track 2** _Synthesis Center E-B143_ |
| --- | --- | --- |
| 8:00 – 8:30AM | Coffee | |
| 8:30 – 12:00PM | **Python for HPC** <br/> _Andrea Zonca, Senior Computational Scientist, SDSC_ <br/> In this session we will introduce four key technologies in the Python ecosystem that provide significant benefits for scientific applications run in supercomputing environments. Previous Python experience is recommended but not required. (1) The Jupyter Notebook allows users to execute code on a single compute node through a local browser for interactive data exploration and visualization. The Jupyter Notebook supports live Python code, explanatory text, LaTeX equations and plots in the same document. (2) IPython Parallel provides a simple, flexible and scalable way of running thousands of Python serial jobs by spawning IPython kernels (namely engines) on any HPC batch scheduler. (3) Numba makes it possible to run pure Python code on GPUs simply by decorating functions with the data types of the input and output arguments. Pure Python prototype code can be gradually optimized by pushing the most computationally intensive functions to the GPU without the need to implement code in CUDA or OpenCL. (4) Dask is a flexible parallel computing library that allows to build a distributed computation using simple operators and then let the library automatically handle distributing data, executing the computation hierarchically and gather back the results.  | **Machine Learning Overview** <br/> _Mai Nguyen, Lead for Data Analytics, SDSC_ <br/> _Paul Rodriguez, Research Analyst, SDSC_ <br/> Machine learning is an interdisciplinary field focused on the study and construction of computer systems that can learn from data without being explicitly programmed. Machine learning techniques can be used to uncover patterns in your data and gain insights into your problem. This session provides an overview of the fundamental machine learning algorithms and techniques used to explore, analyze, and leverage data to construct data-driven solutions applicable to any domain. Topics covered include the machine learning process, data exploration, data preparation, classification, and cluster analysis. Concepts and algorithms will be introduced, followed by exercises to allow hands-on experience using R and RStudio.  |
| 12:00 – 1:30 | Lunch at Café Ventanas | |
| 1:30 - 5:00 | **Performance Tuning** <br/> _Bob Sinkovits, Director for Scientific Computing Applications, SDSC_ <br/> This session is targeted at attendees who both do their own code development and need their calculations to finish as quickly as possible. We&#39;ll cover the effective use of cache, loop-level optimizations, force reductions, optimizing compilers and their limitations, short-circuiting, time-space tradeoffs and more. Exercises will be done mostly in C, but emphasis will be on general techniques that can be applied in any language.  | **Scalable Machine Learning**<br/>  _Mai Nguyen, Lead for Data Analytics, SDSC_ <br/> _Paul Rodriguez, Research Analyst, SDSC_ <br/> Machine learning is an integral part of knowledge discovery in a wide variety of applications. From scientific domains to social media analytics, the data that needs to be analyzed has become massive and complex. This session provides an introduction to approaches that can be used to perform machine learning at scale. Tools and procedures for executing machine learning techniques on HPC will be presented. Spark will also be covered. In particular, we will use Spark's machine learning library, MLlib, to demonstrate how distributed computing can be used to provide scalable machine learning. Please note: Knowledge of fundamental machine learning algorithms and techniques is required. (See description for Machine Learning Overview.) |


## WEDNESDAY, August 8th

| Time | **Track 1** _Auditorium_ | **Track 2** _Synthesis Center E-B143_ |
| --- | --- | --- |
| 8:00 – 8:30 | Coffee | |
| 8:30 – 12:00 | **Information Visualization**<br/>  _Amit Chourasia, Senior Visualization Scientist, SDSC_ <br/> This tutorial will provide a ground up understanding of information visualization concepts and how they can be leveraged to select and use effective visual idioms for different data types such spreadsheet data, geospatial, graph, etc.). Attendees will go through a set of hands on exercises to create designs, decode and fix problems in existing visualization. Practical guidelines for visualization will be discussed as well.  | **Deep Learning**<br/>  _Mai Nguyen, Lead for Data Analytics, SDSC_ <br/> _Paul Rodriguez, Research Analyst, SDSC_ <br/> Deep learning, a subfield of machine learning, has seen tremendous growth and success in the past few years.  Deep learning approaches have achieved state-of-the-art performance across many domains, including image classification, speech recognition, and biomedical applications. Deep learning makes use of models that are composed of many layers of interconnected processing units.  The many layers allow for a deep network to learn representations of data at multiple and increasingly complex and task-specific levels of abstraction, leading to automatic feature learning and excellent prediction performance.  This session provides an introduction to deep learning concepts and approaches.  Case studies utilizing deep learning will be presented, and hands-on exercises will be covered using Keras.  Please note:  Knowledge of fundamental machine learning concepts and techniques is required.|
| 12:00 – 1:30 | Lunch at Café Ventanas | |
| 1:30 – 1:45 | **Group photo** Meet at the staircases in front of the auditorium | |
| 1:45 - 4:30 | **Lightning Rounds** | |
| 4:30 - 5PM | **Data center tour** | |

## THURSDAY, August 9th

| Time | **Track 1** _Auditorium_ | **Track 2** _Synthesis Center E-B143_ |
| --- | --- | --- |
| 8:00 – 8:30 | Coffee | |
| 8:30 – 12:00 | **Scientific visualization with Visit** <br/>  _Amit Chourasia, Senior Visualization Scientist, SDSC_ <br/> This tutorial will provide a high level overview of scientific visualization techniques and their applicability for structured mesh based data (such as rectilinear grids). Attendees will follow along exercises in a hands-on manner to employ different types of techniques using VisIt software and also perform remote visualization on Comet. | **GPU Computing and Programming**<br/>  _Andreas Goetz, Research Scientist and Principal Investigator, SDSC_ <br/> This session provides an introduction to massively parallel computing with graphics processing units (GPUs). The use of GPUs is becoming increasingly popular across all scientific domains since GPUs can significantly accelerate time to solution for many computational tasks. Participants will be introduced to essential background of the GPU chip architecture and will learn how to program GPUs via the use of libraries, OpenACC compiler directives, and CUDA programming. The session will incorporate hands-on exercises for participants to acquire the skills to use and develop GPU aware applications.  |
| 12:00 – 1:30 | Lunch at Café Ventanas | |
| 1:30 – 5:00PM | **Data Science**<br/>  _Ilkay Altintas, Chief Data Science Officer, SDSC_ <br/> | **Parallel Computing using MPI & Open MP**<br/>  _Mahidhar Tatineni, User Services Manager, SDSC_ <br/> This session is targeted at attendees who are looking for a hands-on introduction to parallel computing using MPI and Open MP programming. The session will start with an introduction and basic information for getting started with MPI. An overview of the common MPI routines that are useful for beginner MPI programmers, including MPI environment set up, point-to-point communications, and collective communications routines will be provided. Simple examples illustrating distributed memory computing, with the use of common MPI routines, will be covered. The OpenMP section will provide an overview of constructs and directives for specifying parallel regions, work sharing, synchronization and data scope. Simple examples will be used to illustrate the use of OpenMP shared-memory programming model, and important run time environment variables Hands on exercises for both MPI and OpenMP will be done in C and FORTRAN. |
| 5:30 – 9:00PM | **Beach BBQ Dinner at La Jolla Shores Hotel** , _sweater or jacket recommended_ [8110 Camino Del Oro, La Jolla, CA 92037](https://www.google.com/maps/place/La+Jolla+Shores+Hotel/@32.8549788,-117.2581556,15z/data=!4m2!3m1!1s0x0:0x6e35c24121ff0362?sa=X&ved=0ahUKEwiqvO3JjbHSAhXIjlQKHdJ9CjgQ_BIIczAN) Shuttle provided from SDSC driveway |

## FRIDAY, August 10th

| Time | Title |
| ---  | --- |
| 8:00 – 8:30 | Coffee |
| 8:30 – 10 | **Introduction to Research Data Management Using Globus** _Rick Wagner, Globus Professional Services Manager, Globus_ |
| 10:15 - 11:45 | **SeedMe2: Creating data centric websites for researchers and research projects** <br/> _Amit Chourasia, Senior Visualization Scientist, SDSC_ <br/> Data is an integral part of scientific research. With a rapid growth in data collection and generation capability and an increasingly collaborative nature of research activities, data management and data sharing have become central and key to accomplishing research goals. Researchers today have variety of solutions at their disposal from local storage to Cloud based storage. However, most of these solutions focus on hierarchical file and folder organization. While such an organization is pervasively used and quite useful, it relegates information about the data such as description and collaborative notes about the data to external systems. This spread of information into different silos impedes the flow research activities.  In this tutorial, we will introduce and provide hands on experience with the NSF supported SeedMe2 platform, which provides a web-based data management and data sharing cyberinfrastructure. Attendees will learn how to setup and explore its capabilities and potential for practical use. |
| 12:00 – 12:15 | **Wrap up** |
| 12:15pm | **Adjourn** Thank you for attending we hope you enjoyed the week!_(To-go box lunches will be available)_ |

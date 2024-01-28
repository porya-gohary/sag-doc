# Welcome

## What is a schedule-abstraction graph and how does it work?
Schedule-abstraction graph (SAG) explores the space of possible decisions that a job-level fixed-priority (JLFP) scheduler can take when dispatching a set of jobs on processing resources. This decision space is explored by building a graph whose vertices represent the state of the resource (e.g., processor) after the execution of a set of jobs. The edges of this graph represent possible scheduling decisions that evolve the system states.

## Feature highlights
* support for both uniprocessor and multiprocessor systems
* support for dependent and independent jobs
* 

## Publications
* [1] [Mitra Nasri and Björn B. Brandenburg, "An Exact and Sustainable Analysis of Non-Preemptive Scheduling”, the Real-Time Systems Symposium (RTSS), 2017, pp. 1-12.](https://ieeexplore.ieee.org/document/8277276) 
* [2] [Mitra Nasri, Geoffrey Nelissen, and Björn B. Brandenburg, "A Response-Time Analysis for Non-preemptive Job Sets under Global Scheduling", the Euromicro Conference on Real-Time Systems (ECRTS), 2018, pp. 9:1-9:23.](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.ECRTS.2018.9)
* [3] [Mitra Nasri, Geoffrey Nelissen, and Björn B. Brandenburg, "Response-Time Analysis of Limited-Preemptive Parallel DAG Tasks under Global Scheduling", the Euromicro Conference on Real-Time Systems (ECRTS), 2019, pp. 21:1-21:23.](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.ECRTS.2019.21)
* [4] [Sayra Ranjha, Geoffrey Nelissen, Mitra Nasri, "Partial-Order Reduction in Reachability-based Response-Time Analyses," the IEEE Real-Time Systems Symposium (RTAS), 2022.](https://ieeexplore.ieee.org/abstract/document/9804591)
* [5] [Sayra Ranjha, Pourya Gohari, Geoffrey Nelissen, Mitra Nasri, "Partial-order reduction in reachability-based response-time analyses of limited-preemptive DAG tasks," Real-Time Systems, 2023, pp. 201–255](https://link.springer.com/article/10.1007/s11241-023-09398-x)

[//]: # (## Contributors)

[//]: # (<figure markdown>)

[//]: # (  ![]&#40;images/contr/bbb.jpg&#41;{ width="150"; style="border-radius:50%" })

[//]: # (  <figcaption></figcaption>)

[//]: # (</figure>)


## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

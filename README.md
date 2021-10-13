# Automated Generation and Evaluation of JMH Microbenchmark Suites from Unit Tests

This is a repository where you can get the replication package for the TSE paper entitled `"Automated Generation and Evaluation of JMH Microbenchmark Suites from Unit Tests"`. The replication package consists of experimental data and scripts for reproducing the data.

## Scripts

The scripts for reproducing the data can be found in the directory `Scripts`, which contains three sub-directories for addressing each of the three research questions:

### RQ1

Scripts related to calculating the **Relative Standard Deviations (RSD)** and the **Width of Relative Confidence Interval of means (RCIW)** of performance microbenchmarks. 

### RQ2

Scripts related to deploying performance mutation testing and calculating the **Performance Mutation Score** of performance microbenchmarks.

### RQ3

Scripts related to analyzing major factors affecting performance microbenchmarks' ability in detecting performance bugs.

## Data

The data can be found in the directory `Data`, which contains four sub-directories:

* Eclipse-collections: contains data for the Eclipse-collections project, see https://github.com/eclipse/eclipse-collections.
* RxJava: contains data for the RxJava project, see https://github.com/ReactiveX/RxJava.
* Zipkin: contains data for the RxJava project, see https://github.com/openzipkin/zipkin.
* Simulation: contains data for a preliminary analyze of the Performance Mutation Testing (PMT) framework.


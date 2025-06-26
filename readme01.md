# AI-Flow-Scheduling-Papers

## Table of Content

- [Awesome-DL-Scheduling-Papers](#Awesome-DL-Scheduling-Papers)
  <!-- - [Industrial Traces](#milestone-papers) -->
  - [Schedulers for DL Training](#Schedulers-for-DL-Training)
  - [Schedulers for DL Inference](#Schedulers-for-DL-Inference)
  - [Glossary of Terms](#Glossary-of-Terms)

<!-- ## Industrial Traces -->



## Schedulers for DL Training
| **Scheduler** | **Year** | **Series** | **Paper** | **Objective** | **Heter.** | **Elastic** | **AutoML** | **Code** |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Acme | 2024 | NSDI | [Paper](https://www.usenix.org/conference/nsdi24/presentation/hu) | ♣ | - | - | - | [Code](https://github.com/InternLM/AcmeTrace) |

`Symbols of Training Schedulers`:
| JCT | Utilization | Cost | Fairness | DDL | Accuracy |
|:---:|:---:|:---:|:---:|:---:|:---:|
| ♣ | ♠ | ♦ | ♥ | ✿ | ▲ |

<!-- JCT: ♣ Utilization: ♠ Cost: ♦ Fairness: ♥ DDL: ✿ Accuracy: ▲  -->

## Schedulers for DL Inference
| **Scheduler** | **Year** | **Series** | **Paper** | **Objective** | **Batch** | **Share** | **Cloud** | **Source Code** |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| SpotServe | 2024 | ASPLOS | [Paper](https://arxiv.org/abs/2311.15566) | ♦♥ | ✔ | - | ✔ | [Code](https://github.com/Hsword/SpotServe) |



`Symbols of Inference Schedulers`:
| Accuracy | Throughput | Latency| Cost | Utilization |
|:---:|:---:|:---:|:---:|:---:|
| ♣ | ♠ | ♦ | ♥ | ✿ |


## Glossary of Terms

| Terminology | Definition                                                  |
|-------------|-------------------------------------------------------------|
| JCT         | Job Completion Time (Job Finish Time - Job Submission Time) |
| Fairness    | a metric to assess whether resources are fairly shared among users or jobs                  |
| QoS         | Quality of Service                                          |
| DDL         | Deadline, a time point where DL job must be completed                                                   |
| SLO         | Service Level Objective                                     |

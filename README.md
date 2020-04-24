# TSG-models
This is a repository that holds all **PRISM** models extending the Task-Graph Scheduling problem to a concurrent stochastic game where the notion of Nash equilibrium is considered. These models were developed during my final year for my *MSci Project*. The models can be run using the **PRISM-games** tool which is available for download [here](http://www.prismmodelchecker.org/games/).

The models developed are described as follows:

## Zero-sum Models
*For these models one scheduler was used a variation of processors.*
1. The Basic 2 Processor Model
   * tg_csg_basic2.prism
1. The Basic 3 Processor Model
   * tg_csg_basic3.prism
1. The Basic 3 Processor Model, where *P3* is faster 
   * tg_csg_basic3_faster.prism
1. The Basic 3 Processor Model, where *P3* is slower
   * tg_csg_basic3_slower.prism
1. The 3 Processor Model with Failure
   * tg_csg_failure3.prism
1. The 3 Processor Model with Failure, where *P3* is faster
   * tg_csg_failure3_faster.prism
1. The 3 Processor Model with Failure, where *P3* is slower
   * tg_csg_failure3_slower.prism
1. The 3 Processor Model with Faults
   * tg_csg_faulty3.prism
1. Properties for zero-sum models
   * tg_csg.props

## Nonzero-sum Models
*For these models another scheduler was introduced in the Basic 3 Processor Model, the number of tasks each scheduler has to complete was changed.*
1. Model with Three Tasks
   * tg_csg_2sched_3tasks.prism
1. Model with Four Tasks
   * tg_csg_2sched_4tasks.prism
1. Properties for nonzero-sum models
   * tg_csg_2sched.props
 
The analysis and discussion for these models can be found [here](https://drive.google.com/file/d/1g5SNW8YZ8XpXGBG_OfVjx-vo7ISgpxHb/view?usp=sharing).

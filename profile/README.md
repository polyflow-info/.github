# polyflow.info

![Logo](profile/assets/Positive@2x.png)
## Polyflow Taskpool and Datapool

> A component library for building enterprise-wide process platforms with multiple process engines like Camunda Platform.

In the last years, we built different process applications on behalf of the customer several times. It turned out that some issues occurred every
time during the implementation.

These were:

* coping with performance issues if big amount of tasks is available
* creating high-performance custom queries for pre-loading process variables for tasks
* creating high-performance custom queries to pre-load business data associated with the process instance
* high-performance retrieving a list of tasks from several process engines
* repetitive queries with same result
* creating an archive view for business data items handled during the process execution
* creating an audit log of changes performed on business data items

![Polyflow Hero](profile/assets/polyflow-hero-530x406.png)

We decided to stop repetitive work and release an open-source library which builds a foundation for solving these problems.



## Expand Metrics

This file describes all built-in expanded and practical prometheus metrics for job workloads
in KubeDL, and difference kinds of workloads is classified by labels.

|    Metric Names     |   Description    |
|    ------------     |   -----------    |
|    kubedl_jobs_created{kind}  | Counts number of jobs created |  
|    kubedl_jobs_deleted{kind}  | Counts number of jobs deleted |
|    kubedl_jobs_successful{kind}  |  Counts number of jobs successfully finished  |
|    kubedl_jobs_failed{kind}      |   Counts number of jobs failed  |
|    kubedl_jobs_restarted{kind}   |   Counts number of jobs restarted  |
|    kubedl_jobs_running{kind}     |   Counts number of jobs currently running  |
|    kubedl_jobs_pending{kind}     |   Counts number of jobs currently pending  |
|    kubedl_jobs_launch_delay{kind, name, namespace, uid}  |  Histogram for recording launch delay duration(from job created to job running) of each job  |
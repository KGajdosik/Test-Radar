---
title:      "Jenkins"
ring:       adopt
quadrant:   platforms-and-operations
tags:       [Coding, DevOps, Testing, Tools]
---
Pipelines are the top-level component of continuous integration, delivery, and deployment.
Pipelines comprise:
Jobs, which define what to do. For example, jobs that compile or test code.
Stages, which define when to run the jobs. For example, stages that run tests after stages that compile the code.
Jobs are executed by runners. Multiple jobs in the same stage are executed in parallel, if there are enough concurrent runners.
If all jobs in a stage succeed, the pipeline moves on to the next stage.
If any job in a stage fails, the next stage is not (usually) executed and the pipeline ends early.
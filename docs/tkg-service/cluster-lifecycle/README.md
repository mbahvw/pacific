# TKG Service Cluster Lifecycle Docs

This section contains some very detailed documentation about how TKG Service Cluster Lifecycle works under the covers. 

These documents are designed to help troubleshoot any isues with TKG Service

1. [Cluster Lifecycle Creation Basics](creation-basics.md) explains in detail how all of the controllers and objects in TKG Service interoperate to stand up a Kubernetes Cluster
2. [Cluster Creation Milestones](creation-milestones.md) explains the key milestones to look for during TKG Service cluster creation and reasons why they might fail.
3. [Cluster Deletion](deletion.md) explains the way in which a cluster should be cleanly deleted and what to look for if it appear to have failed.

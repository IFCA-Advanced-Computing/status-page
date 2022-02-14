---
section: issue
title: "[Cloud] Failure launching new instances"
date: 2022-01-31T08:00:47.464Z
status: in_progress
pinned: top
current_severity: monitoring
max_severity: disrupted
duration: ""
resolved_on: 2022-02-14T11:00:20.523Z
affected:
  - OpenStack Cloud Public APIs
  - OpenStack Networking (Neutron)
  - OpenStack Compute (nova)
  - OpenStack Compute Nodes
twitterFeed: ""
enableComments: true
---
Since the last upgrade of the release versions of some components of OpenStack, it fails on launching new instances randomly with error:

Build of instance d47XXXXX aborted: Failed to allocate the network(s), not rescheduling.

We are debugging the system and trying to resolve it ASAP.
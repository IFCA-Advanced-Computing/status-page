---
section: issue
title: Ceph Upgrade
date: 2022-06-29T09:49:15.135Z
status: in_progress
pinned: top
current_severity: disrupted
max_severity: disrupted
duration: 4h
resolved_on: 2022-06-28T12:00:15.154Z
affected:
  - OpenStack Block Storage (cinder)
  - OpenStack Object Storage (Swift)
  - Ceph block storage
twitterFeed: ""
enableComments: true
---
Next Tuesday morning, June 28th, we will be upgrading the CEPH storage backend version (from mimic 13.x.x to nautilus 14.x.x). It is recommended that all those who store critical data on external volumes of cloud machines, as well as those who use the swift service to perform an external backup, to avoid data loss in case of an unscheduled failure during the upgrade procedure.
---
title: "Hardware Allocation"
classification: "INTERNAL"
weight: 30
---

## Cluster A (Control Plane)
- 3× Xeon E3-1275v5, 64GB RAM each
- ZFS replication (15 min)

## Server B (Execution Plane)
- 1× AMD EPYC, 24+ cores, 256GB RAM
- heavy I/O, compilation, public traffic

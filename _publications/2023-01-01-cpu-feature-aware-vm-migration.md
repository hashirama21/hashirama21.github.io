---
title: "CPU-Feature-Aware Virtual Machine Migration in Heterogeneous Environments"
collection: publications
category: manuscripts
permalink: /publication/2023-01-01-cpu-feature-aware-vm-migration
excerpt: "Proposed a per-application, dynamic approach for safe VM migration across heterogeneous CPU hosts, reducing the required CPU feature mask from 47 flags to 12 essential flags."
date: 2023-01-01
venue: 'Preprint, Polytechnique Yaoundé (ENSPY)'
paperurl: 'https://github.com/hashirama21/xen-cpu-aware-migration'
citation: 'Vincess Dongmo, Tchudjing Ruben, Nguekeng Marc Donald, Ngom Mbock Michel, Tsanga Zo Onyaba, Nnange Akume. (2023). &quot;CPU-Feature-Aware Virtual Machine Migration in Heterogeneous Environments.&quot; Preprint, Polytechnique Yaoundé.'
---

Migrating virtual machines (VMs) across physically heterogeneous hosts remains brittle when source and destination processors expose different CPU feature sets. We propose a *per-application, dynamic* approach: a C-based runtime profiler executes on the source Xen dom0, instruments the running guest (domU), and computes the minimal set of CPU features actually exercised by the target workload. A companion shell script validates this set by iteratively disabling each feature and verifying that the workload remains functional. Validated on two Intel hosts with differing micro-architectures using a PostgreSQL 12 OLTP benchmark, reducing the exposed flag count from 47 raw CPUID flags to 12 essential flags, demonstrating successful migration with zero application-level errors.

Open-source implementation: [github.com/hashirama21/xen-cpu-aware-migration](https://github.com/hashirama21/xen-cpu-aware-migration)

---
title: "Real-Time OS Integrity Monitoring with Tetragon"
description: "Monitor kernel modules and eBPF programs in real time to safeguard system integrity against threats."
layout: "features"
body_class: "td-home"

hero:
  title: "Operating System Integrity"
  intro: "Tetragon Operating System Integrity lets you observe kernel module operations, eBPF subsystem activity, and process injections⁠"
  videoID: "UBVTJ0LeXxc"

contentTitle: "Audit eBPF Subsystem Interactions and Kernel Modules"

tagline: "Tetragon empowers security teams to monitor host system changes"

features:
  - title: "Kernel Modules Audit Trail"
    description: "Track the loading and unloading of kernel modules, identifying responsible processes or containers."
    icon: "monitoring"
  - title: "eBPF Subsystem Observability"
    description: "Monitor eBPF program loads and interactions to detect suspicious activity and potential threats."
    icon: "telescope-green"
---

Modern containerized environments often rely on dynamic host system changes, such as loading kernel modules or modifying kernel parameters, to deliver necessary functionality. However, this same flexibility introduces significant security risks. Malicious actors can exploit these capabilities to load unauthorized kernel modules, alter system behavior, or hide their presence within the system. For security teams, the challenge lies in distinguishing legitimate activity from malicious manipulation of these critical kernel-level components.

Tetragon monitors the loading and unloading of kernel modules in real time, identifying the processes or containers responsible. It captures critical details such as whether a kernel module is signed, ensuring that only verified code is integrated into the kernel. Tetragon also keeps an eye on the eBPF subsystem, providing the observability to detect suspicious program loads or interactions. This comprehensive monitoring allows security teams to detect, investigate, and respond to potential threats swiftly, ensuring the integrity of the operating system while maintaining the agility that modern applications demand.

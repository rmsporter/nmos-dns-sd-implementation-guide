# AMWA INFO-004: NMOS Implementation Guide for DNS-SD \[Work In Progress\]

[![Lint Status](https://github.com/AMWA-TV/nmos-dns-sd-implementation-guide/workflows/Lint/badge.svg)](https://github.com/AMWA-TV/nmos-template/actions?query=workflow%3ALint)
[![Render Status](https://github.com/AMWA-TV//workflows/Render/badge.svg)](https://github.com/AMWA-TV/nmos-template/actions?query=workflow%3ARender)

This repository holds the source for this Implementation Guide, part of the family of [Networked Media Open Specifications](https://specs.amwa.tv/nmos) from the [Advanced Media Workflow Association](https://amwa.tv)

<!-- INTRO-START -->

### What does it do?

-  DNS Service Discovery (DNS-SD) provides a simple and flexible method to discover NMOS Registration and Discovery Server (RDS) Services.

### Why does it matter?

- The NMOS RDS provides information about NMOS nodes, devices, and APIs. There must be a common way to locate the RDS in order for an NMOS component to register itself for discovery by other NMOS components. 

### How does it work?

The examples in this Implementation Guide add records to a BIND9 DNS server such that the server responds to standardized queries with information that indicates:

- The fact that the DNS server provides Service Discovery
- Where the NMOS RDS may be found on the network


<!-- INTRO-END -->

## Getting started

See the list of documents below.

There is more information about the NMOS Specifications and their GitHub repos at <https://specs.amwa.tv/nmos>.

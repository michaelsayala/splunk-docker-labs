# Splunk Distributed Lab Ecosystem (Docker)

## Overview

This repository is a **Docker-based Splunk learning ecosystem** designed to simulate real-world **enterprise Splunk distributed architectures**.

It combines multiple labs into one cohesive environment to help you understand how Splunk components interact in production-like deployments.

These labs are built for **hands-on learning, certification preparation, and architecture practice**.

---

## Labs Included

This repository contains multiple modular Splunk environments:

### 1. [Indexer Cluster Lab](https://github.com/michaelsayala/splunk-idx-docker-lab)
Simulates a fully functional **Splunk Indexer Cluster** with Cluster Manager and multiple indexers.

### 2. [Search Head Cluster Lab](https://github.com/michaelsayala/splunk-shc-docker-lab)
Demonstrates a **Search Head Cluster architecture** with captain election and centralized app deployment.

### 3. [Deployment Server & Universal Forwarder Lab](https://github.com/michaelsayala/splunk-ds-uf-docker-lab)
Simulates **app deployment and data forwarding pipelines** using a Deployment Server and Universal Forwarders.

### 4. [Heavy Forwarder Lab](https://github.com/michaelsayala/splunk-hf-docker-lab)
Focuses on **data ingestion and forwarding into an Indexer Cluster**, including load balancing behavior.

### 5. [License Manager Lab](https://github.com/michaelsayala/splunk-lm-docker-lab)
Demonstrates **centralized Splunk licensing management** and license consumption by search components.

### 6. [Distributed Monitoring Console Lab](https://github.com/michaelsayala/splunk-dmc-docker-lab)
Provides a **centralized observability layer** for monitoring an entire Splunk distributed environment.

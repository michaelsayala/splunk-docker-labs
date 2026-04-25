# Splunk Distributed Lab (Docker)

## Overview

This repository provides a Docker-based Splunk lab environment that simulates a real-world distributed enterprise architecture.

It brings together multiple modular labs into a single, cohesive setup, allowing you to see how core Splunk components work together in a production-like environment.

The project is designed for hands-on learning, architecture understanding, and certification preparation, with a focus on practical, real-world scenarios.

---

## Labs Included

This repository includes the following modular Splunk environments:

### 1. [Indexer Cluster Lab](https://github.com/michaelsayala/splunk-idx-docker-lab)
Simulates a fully functional Splunk Indexer Cluster, including a Cluster Manager and multiple indexers for data replication and search availability.

### 2. [Search Head Cluster Lab](https://github.com/michaelsayala/splunk-shc-docker-lab)
Demonstrates a Search Head Cluster (SHC) setup, including captain election and centralized knowledge object and app deployment.

### 3. [Deployment Server & Universal Forwarder Lab](https://github.com/michaelsayala/splunk-ds-uf-docker-lab)
Models application deployment and data forwarding workflows using a Deployment Server and multiple Universal Forwarders.

### 4. [Heavy Forwarder Lab](https://github.com/michaelsayala/splunk-hf-docker-lab)
Focuses on data ingestion, parsing, and forwarding, including load balancing into an Indexer Cluster.

### 5. [License Manager Lab](https://github.com/michaelsayala/splunk-lm-docker-lab)
Shows how centralized licensing is managed and distributed across Splunk components in a distributed environment.

### 6. [Distributed Monitoring Console Lab](https://github.com/michaelsayala/splunk-dmc-docker-lab)
Provides a centralized monitoring solution for visibility into the health and performance of the entire Splunk deployment.

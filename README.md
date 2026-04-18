# Splunk Distributed Lab Ecosystem (Docker)

## Overview

This repository is a **Docker-based Splunk learning ecosystem** designed to simulate real-world **enterprise Splunk distributed architectures**.

It combines multiple labs into one cohesive environment to help you understand how Splunk components interact in production-like deployments.

These labs are built for **hands-on learning, certification preparation, and architecture practice**.

---

## Labs Included

This repository contains multiple modular Splunk environments:

### 1. Indexer Cluster Lab
Simulates a fully functional **Splunk Indexer Cluster** with Cluster Manager and multiple indexers.

### 2. Search Head Cluster (SHC) Lab
Demonstrates a **Search Head Cluster architecture** with captain election and centralized app deployment.

### 3. Deployment Server & Universal Forwarder Lab
Simulates **app deployment and data forwarding pipelines** using a Deployment Server and Universal Forwarders.

### 4. Heavy Forwarder Lab
Focuses on **data ingestion and forwarding into an Indexer Cluster**, including load balancing behavior.

### 5. License Manager Lab
Demonstrates **centralized Splunk licensing management** and license consumption by search components.

### 6. Distributed Monitoring Console (DMC) Lab
Provides a **centralized observability layer** for monitoring an entire Splunk distributed environment.

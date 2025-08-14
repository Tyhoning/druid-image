<p align="center">
  <h1 align="center">Druid Database</h1>
  <p align="center">
    <a href="README_ZH.md"><strong>简体中文</strong></a> | <strong>English</strong>
  </p>

## Table of Contents

- [Repository Introduction](#repository-introduction)  
- [Prerequisites](#prerequisites)  
- [Image Specifications](#image-specifications)
- [Getting Help](#getting-help)
- [How to Contribute](#how-to-contribute)

## Repository Introduction  
[Apache Druid](https://github.com/apache/Druid) is A high performance, real-time analytics database that delivers sub-second queries on streaming and batch data at scale and under load.  

**Core Features:**
1. Sub-second queries at any scale: Execute OLAP queries in milliseconds on high-cardinality and high-dimensional data sets with billions to trillions of rows without pre-defining or caching queries in advance.

2. High concurrency at the lowest cost: Build real-time analytics applications that supports 100s to 100,000s queries per second at consistent performance with a highly efficient architecture that uses less infrastructure than other databases.

3. Real-time and historical insights: Unlock streaming data potential through Druid's native integration with Apache Kafka and Amazon Kinesis as it supports query-on-arrival at millions of events per second, low latency ingestion, and guaranteed consistency.

**Architecture Design:**

![](./images/img001.png)

This project offers pre-configured [**Druid Database**](https://marketplace.huaweicloud.com/intl/hidden/contents/63b64c0b-e95a-4f5f-9029-92f0cc005505) images with Druid and its runtime environment pre-installed, along with deployment templates. Follow the guide to enjoy an "out-of-the-box" experience.

> **System Requirements:**
> - CPU: 2GHz or higher  
> - RAM: 4GB or more  
> - Disk: At least 40GB  

## Prerequisites  
[Register a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Specifications  

| Image Version                                                  | Description                                             | Notes |  
|----------------------------------------------------------------|---------------------------------------------------------|-------|  
| [Druid32.0-kunpeng-v1.0](https://github.com/HuaweiCloudDeveloper/Druid-image/tree/Druid32.0-kunpeng-v1.0) | Deployed on Kunpeng servers with Huawei Cloud EulerOS 2.0 64bit |  | 
| [Druid32.0-kunpeng-v1.0](https://github.com/HuaweiCloudDeveloper/Druid-image/tree/Druid32.0-kunpeng-v1.0) | Deployed on Kunpeng servers with Ubuntu24.04 64bit   |  |  

## Getting Help
- Submit an [issue](https://github.com/HuaweiCloudDeveloper/Druid-image/issues)
- Contact Huawei Cloud Marketplace product support

## How to Contribute
- Fork this repository and submit a merge request.
- Update README.md synchronously based on your open-source mirror information.

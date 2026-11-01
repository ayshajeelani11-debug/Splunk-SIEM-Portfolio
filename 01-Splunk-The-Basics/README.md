# Splunk: The Basics

## 1. Introduction

Splunk is a Security Information and Event Management (SIEM) platform used to collect, index, search, monitor, and analyze machine-generated data.

It helps security teams investigate events, identify suspicious activities, monitor systems, and detect potential security threats.

## 2. What is SIEM?

Security Information and Event Management (SIEM) is a security solution that collects and analyzes log data from different sources across an organization's IT infrastructure.

**Key functions of SIEM:**
- Log collection and centralization
- Security event monitoring
- Threat detection and investigation
- Alert generation
- Incident analysis

## 3. Splunk Architecture

Splunk uses different components to process and analyze machine-generated data.

### Forwarder
A Forwarder collects data from different sources, such as servers and endpoints, and forwards it to Splunk.

### Indexer
An Indexer receives incoming data, processes it, and stores it in indexes to make searching and analysis possible.

### Search Head
A Search Head provides the interface where users perform searches, analyze events, create reports, and investigate data.

### Basic Data Flow

```text
Data Sources
     |
     v
  Forwarder
     |
     v
   Indexer
     |
     v
  Search Head
     |
     v
Search and Analysis
```

## 4. Adding Data in Splunk

One of the basic tasks in Splunk is adding data so that it can be indexed and searched.

Splunk supports different data sources, including:
- Log files
- Network data
- Windows event logs
- System and application logs
- Other machine-generated data

### Practical Implementation

During the TryHackMe lab, I practiced the process of adding data to Splunk through its interface.

The following screenshots document the practical steps performed during the exercise.

### Step 1: Adding Data – Initial Stage

![Adding Data Step 1](Screenshots/Adding%20Data_1.png)

### Step 2: Adding Data – Configuration

![Adding Data Step 2](Screenshots/Adding%20Data_2.png)

### Step 3: Adding Data – Data Input Process

![Adding Data Step 3](Screenshots/Adding%20data_3.png)

### Step 4: Adding Data – Final Stage

![Adding Data Step 4](Screenshots/Adding%20Data_4.png)

## 5. Understanding Indexes and Events

### Index
An index is a storage location in Splunk where collected and processed data is organized.

### Event
An event is an individual record of activity or information collected from a data source.

Indexes help organize data and allow users to search specific datasets efficiently.

## 6. Practical Learning Outcomes

Through this lab, I gained an understanding of:

- Splunk fundamentals and its purpose in security monitoring.
- The role of Forwarders, Indexers, and Search Heads.
- How data is added to Splunk.
- The purpose of indexes and events.
- How centralized log management supports security investigations.

## 7. Lab Information

**Platform:** TryHackMe

**Room:** Splunk: The Basics

**Tool:** Splunk

**Interface:** Splunk Search & Reporting

**Category:** SIEM Fundamentals

## 8. Conclusion

This practical exercise helped me understand the fundamentals of Splunk and how machine-generated data can be collected, indexed, and analyzed.

It provided a foundation for further learning in SPL, log analysis, and security event investigation.

---

**Author:** Ayesha Jilani  
**Field:** Cybersecurity  
**Career Interest:** Junior SOC Analyst
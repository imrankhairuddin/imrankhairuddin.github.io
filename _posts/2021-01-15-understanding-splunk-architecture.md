---
title: "Understand the Splunk Architecture"
author: Imran Khairuddin
date: 2021-01-15 21:20:00 +0800
categories: [Blogging, Tutorial]
tags: [splunk]
---

### The are three main compenents in Splunk architecture: 

1. Search Head

Splunk Search Head which is a Graphical interface used for searching, analyzing and reporting. It provides GUI to user for prforming various operation. All the the data in the indexer can be search and query by search head using SPL known as Splunk Processing Language.

2. Indexer

Splunk Indexer is used for parsing and indexing the data. Splunk instance transforms the incoming data into events and stores it in indexes for performing search operations efficiently.

3. Forwarder

Splunk forwarder is used for data forwarding. This is where all the logs being collected. There are two different types of Splunk Forwarder. 

  Universal Forwarder

	  Universal forwarder is a simple companent that performs minimal processing on the incoming data or logs before forwarding them to indexer.

  Heavy Forwarder

	  Heavy forwarder can performs processing on the unnecessary data  that can save on bandwith, time and cost. Heavy forwarder taypically does parsing and indexing at the source the forwarding them to indeer which save a nlot of bandwith and storage.





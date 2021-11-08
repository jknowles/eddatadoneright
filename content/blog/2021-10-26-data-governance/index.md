---
title: Data governance
author: 'Jared Knowles'
date: '2021-10-26'
slug: data-governance
categories: []
tags: []
---

<style>
ul li {
  list-style: square;
  margin-left: 3em;
}

strong {
  font-weight:bold;
}
</style>

In EDDR Volume 2 we provide an introduction to data governance in chapter 5. 
This post summarizes one part of that chapter by describing the three data 
governance frameworks. 


### Lifecycle

The first framework is helpful when thinking about the current design focus 
of your data system. It is also helpful early in the development of a data 
system to help keep stakeholders organized around the current needs.

<figure>
<img src="/v2/EDDR2-Data-Systems-Development-Phase.png" alt="drawing" width="500" align="center"/>
</figure>

**Advantages**


* Helps focus on building a solid foundation
* Identifies the connection between good collections and later analytics


**Drawbacks**

* Mature data systems need to work on all these pieces at once
* Architecture and system integration challenges can rise to the top (see below)



### Roles and Responsibilities

This is a people/role centered framework that focuses on which levels of the 
organization. This helps individuals assess their role in the organization and 
begint to see the data governance obligations associated with that role. 

<figure>
<img src="/v2/EDDR2-Data-Systems-Roles-And-Responsibilities.png" alt="drawing" width="500" align="center"/>
</figure>

**Advantages**

- Divides and locates the work where responsibility and expertise sit
- Helps organize thinking about where decision making occurs depending on level 
of granularity
- Demonstrates that data governance is an organizational responsibility


**Drawbacks**

- A three-tier hierarchy may be too flat
- Just because it is written does not mean that reponsibility will cross levels



### Flow of Data

Data is always in motion in a data system. Every point where data is handed off 
or transitions is a point where data governance decisions occur and need to be 
applied. This frame focuses on individual data elements and traces their movement 
in the system as a way of identifying key governance questions. 


<figure>
<img src="/v2/EDDR2-The-Flow-Of-Data.png" alt="drawing" width="500" align="center"/>
</figure>


**Advantages**

- Puts the **data** in data governance
- Sheds light on the often under-analyzed collection process and data use process 
on each end
- Makes knowing the data pipeline an organizational activity and not an individual 
activity


**Drawbacks**

- Data flow discussions can often end with unhelpful conclusions, i.e. "the vendor is the problem"
- Mapping the flow of data for many elements can be very time-consuming


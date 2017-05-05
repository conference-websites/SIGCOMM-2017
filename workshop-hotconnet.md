---
layout: default
title: ACM SIGCOMM 2017 1st International Workshop on Hot Topics in Container Networking and Networked Systems (HotConNet'17)
group: Workshops

dates:
    - info: Submission deadline
      date: <del>March 24, 2017</del> March 31st, 2017 9:00pm PST
    - info: Acceptance notification
      date: <del>April 30, 2017</del>
    - info: Camera ready deadline
      date: May 29th, 2017 9:00pm PST

committees:
    - role: Workshop Co-Chairs
      people:
       - name:        Minlan Yu
         affiliation: Yale University
       - name:        Hongqiang Harry Liu
         affiliation: Microsoft Research


    - role: Technical Program Committee
      people:
       - name:        Deepak Bansal
         affiliation: Microsoft Azure
       - name:        Theophilus Benson
         affiliation: Duke
       - name:        Dongluo Chen
         affiliation: Docker
       - name:        Yang Chen
         affiliation: Fudan
       - name:        Bruce Davie
         affiliation: VMWare
       - name:        Haggai Eran
         affiliation: Mellanox
       - name:        Benjamin Hindman
         affiliation: Mesosphere
       - name:        Tim Hockin
         affiliation: Google
       - name:        Chi-Yao Hong
         affiliation: Google
       - name:        Charlie Hu
         affiliation: Purdue
       - name:        Ryan Huang
         affiliation: JHU
       - name:        Xin Jin
         affiliation: JHU
       - name:        Thomas Knauth
         affiliation: TU Dresden
       - name:        Jeongkeun Lee
         affiliation: Barefoot
       - name:        Ben Pfaff
         affiliation: VMWare
       - name:        Peter Pietzuch
         affiliation: Imperial College London
       - name:        George Porter
         affiliation: UCSD
       - name:        Wei Xu
         affiliation: Tsinghua
       - name:        Ennan Zhai
         affiliation: Yale
       - name:        Nicholas Zhang
         affiliation: Huawei
---

## {{ page.title }}

### Call For Papers

Containerization technology is being adopted quickly by the software industry because it offers fast deployment, good portability, and high resource efficiency to run large-scale and distributed systems. For example, many large Internet companies, e.g. Google, Yelp and AirBnB, etc., have intensively used containers to speed up the development of their applications and platform. The ecosystem of containerization is also rapidly growing. For instance, operating system providers like Microsoft and RedHat have released features to support Docker/container in Windows and Linux respectively; cloud providers like AWS, Azure and OpenStack all release their own services and solutions for containerized applications; there are about 400,000 public container images on Docker Hub with roughly 4~5 thousand new ones per week, and the number of pulls from Docker Hub reached 1 billion from Aug to Oct, 2016.

However, containerization is still in its early stage, and one of the major challenges it is facing is networking. Current container networking solutions mainly rely on the OS kernel to provide basic reachability and security among containers, while failing to meet various requirements needed by practical applications. For example, performance sensitive applications demand high networking performance (e.g. high bandwidth and low latency), while security sensitive applications usually rely on the network to implement firewalls, Intrusion detection system (IDS) or traffic scrubbers. Moreover, there are application demands for privacy, fairness, mobility, high availability, and so on and so forth. It is still challenging to provide the network functions above in container networking due to concerns such as scalability with the number of containers, containers portability, the underlying environments containers depend on (on physical machines or virtual machines) and the heterogeneity of end points (e.g. containers, VMs and physical machines).

#### Topics of Interest

Authors are encouraged to submit full papers describing original, previously unpublished, complete research, not currently under review by another conference or journal, addressing state-of-the-art research and development in all areas of container networking and networked systems.

- Large-scale containerized systems and applications
- Architecture of containerized applications and systems
- Measurement of containerized systems and applications
- Security and privacy in containerized systems and applications
- Measurement of containerized systems and applications
- User behavior analysis and modeling in containerized applications
- Software-defined container networking
- High Performance container networking
- Middleboxes for containerized systems and applications
- Network function virtualization in containerized systems and applications
- Containers in clouds and edge clouds
- Mobility of containers
- Containers for Internet of Things
- Experiences of containers in productions architectures

[Contact workshop co-chairs](mailto:minlan.yu@yale.edu,harliu@microsoft.com?subject=[HotConNet'17]){: data-role="button" class="button" }.

#### Submission Instructions

Papers must be submitted electronically. The length of papers must be no more than **6 pages**, including tables and figures, (in two-column, 10-point format) including references, following the provided [LaTeX style file](http://conferences.sigcomm.org/sigcomm/2016/doc/sig-alternate-10pt.cls). The cover page must contain an abstract of about 150 words, 3-5 keywords, name and affiliation of author(s) as well as the corresponding author's e-mail and postal address. Each submission will receive **at least three** independent blind reviews from the TPC. At least one of the authors of every accepted paper must register and present their work at the workshop. 

Paper registration and submission can be done via HotCRP at: [https://sigcomm17hotconnet.hotcrp.com/](https://sigcomm17hotconnet.hotcrp.com/).

### Important Dates

{% include dates2.html dates=page.dates %}

## Authors Take Note

**The official publication date is the date the proceedings are made available in the ACM Digital Library. This date may be up to *TWO WEEKS* prior to the first day of your conference. The official publication date affects the deadline for any patent filings related to published work.**

### Committees

{% include committees.html committees=page.committees %}

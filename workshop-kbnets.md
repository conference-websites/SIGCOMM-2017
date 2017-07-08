---
layout: default
title: ACM SIGCOMM 2017 Workshop on Kernel-Bypass Networks (KBNets'17)
group: Workshops

dates:
    - info: Submission deadline
      date: <del>March 24, 2017</del> <del>March 31, 2017</del>
    - info: Acceptance notification
      date: <del>April 30, 2017</del> <del>May 3, 2017</del>
    - info: Camera ready deadline
      date: May 26, 2017

committees:
    - role: Workshop Co-Chairs
      people:
       - name:        Mohammad Alizadeh
         affiliation: MIT
       - name:        Yibo Zhu
         affiliation: Microsoft Research

    - role: Technical Program Committee
      people:
       - name:        Aditya Akella
         affiliation: University of Wisconsin-Madison
         homepage:    http://pages.cs.wisc.edu/~akella/
       - name:        Adam Belay
         affiliation: MIT / Google
       - name:        Mosharaf Chowdhury
         affiliation: University of Michigan, Ann Arbor
         homepage:    http://www.mosharaf.com/
       - name:        Nandita Dukkipati
         affiliation: Google
         homepage:    https://research.google.com/pubs/author39115.html
       - name:        Dongsu Han
         affiliation: KAIST
         homepage:    http://ina.kaist.ac.kr/~dongsuh/
       - name:        Arvind Krishnamurthy
         affiliation: University of Washington
         homepage:    http://www.cs.washington.edu/people/faculty/arvind
       - name:        Vishal Misra
         affiliation: Columbia University
         homepage:    http://www.cs.columbia.edu/~misra/
       - name:        Costin Raiciu
         affiliation: University Politehnica of Bucharest
         homepage:    http://nets.cs.pub.ro/~costin/
       - name:        Shachar Raindel
         affiliation: Microsoft Azure
       - name:        Luigi Rizzo
         affiliation: Uni. Di Pisa / Google
         homepage:    http://info.iet.unipi.it/~luigi/
       - name:        Kun Tan
         affiliation: Huawei
       - name:        Eitan Zahavi
         affiliation: Mellanox
         homepage:    http://tx.technion.ac.il/~ezahavi/
       - name:        Ming Zhang
         affiliation: Alibaba
---

## {{ page.title }}

### Workshop Program

{% include program-online.html type="kbnets" %}

### Call For Papers

Kernel-Bypass Networks (including, but not limited to RDMA and DPDK) have recently drawn much attention from the research community and the industry. Emerging applications such as AI training, distributed storage systems, and software middle-boxes/NFV have been shown to benefit significantly from technologies that bypass the conventional OS network stack. At the same time, recent switch and NIC developments (e.g., RoCE) have paved the way to the large-scale deployment of KBNets.

We believe that our community must expedite the research on kernel bypass networks. There are significant open questions, for example, regarding the merits of different kernel bypass architectures, how to design control plane and management systems for KBNets, and how to deal with inherent problems such as congestion spreading and deadlocks in such networks. As importantly, much more work is needed to rethink how we design distributed systems and applications to fully take advantage of KBNets.

The ACM SIGCOMM Workshop on Kernel-Bypass Networks (KBNets’17) is organized with the goal of bringing together researchers from the networking, operating systems, and distributed systems communities to promote the development and evolution of kernel-bypass networks. We welcome submissions related to all aspects of KBNets and KBNets-based systems, including network/system architecture, design, implementation, simulation, modeling, analysis, and measurement. We highly encourage novel and innovative early stage work that will encourage discussion and future research on KBNets.

#### Topics of Interest

Topics include but are not limited to:

- Network transport for kernel-bypass networks
- Control plane for kernel-bypass networks
- Security issues regarding kernel-bypass networks
- Distributed systems that are based on kernel-bypass networks, e.g., AI training, distributed storage, database and in-memory caches
- Data center network architectures for kernel-bypass networks
- Virtualization for kernel-bypass networks
- NIC/switch hardware design for kernel-bypass networks
- Middle-boxes/NFV optimization with kernel-bypass networks
- Diagnosing and troubleshooting kernel-bypass networks
- Experiences and best-practices in deploying kernel-bypass networks
- Measurement and performance studies of kernel-bypass networks and applications
- Deployment strategies and backward compatibility with traditional network stacks
- Other approaches such as high performance OS data-plane architectures


[Contact workshop co-chairs](mailto:alizadeh@csail.mit.edu,yibzh@microsoft.com?subject=[KBNets'17]){: data-role="button" class="button" }.

#### Submission Instructions

Submissions must describe original, previously unpublished research, not currently under review by another conference or journal. Papers must be submitted electronically via the submission site. The length of papers must be no more than **6 pages**, including tables, figures __<red>and references, using the same template as SIGCOMM submission</red>__ ([SIGCOMM submission instructions](submission.html)).  The cover page must contain the name and affiliation of author(s) for **single-blind** peer reviewing by the program committee. Each submission will receive **at least three independent blind** reviews from the TPC. At least one of the authors of every accepted paper must register and present their work at the workshop.

Please submit your paper via [https://sigcomm17kbnets.hotcrp.com/](https://sigcomm17kbnets.hotcrp.com/).

### Important Dates

{% include dates2.html dates=page.dates %}

## Authors Take Note

**The official publication date is the date the proceedings are made available in the ACM Digital Library. This date may be up to *TWO WEEKS* prior to the first day of your conference. The official publication date affects the deadline for any patent filings related to published work.**

### Committees

{% include committees.html committees=page.committees %}

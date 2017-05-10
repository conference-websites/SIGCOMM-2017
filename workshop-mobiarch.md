---
layout: default
title: ACM SIGCOMM 2017 Workshop on Mobility in the Evolving Internet Architecture (MobiArch'2017)
group: Workshops

dates:
    - info: Submission deadline
      date: <del>March 17, 2017</del> <del>March 31, 2017</del>
    - info: Acceptance notification
      date: <del>April 28, 2017</del>
    - info: Camera ready deadline
      date: May 26, 2017

committees:
    - role: Workshop Co-Chairs
      people:
       - name:        Paolo Bellavista
         affiliation: University of Bologna
       - name:        Katherine Guo
         affiliation: Nokia Bell Labs

    - role: Steering Committee
      people:
       - name:        Jon Crowcroft
         affiliation: University of Cambridge
       - name:        Xiaoming Fu
         affiliation: University of Goettingen
       - name:        Katherine Guo
         affiliation: Bell Labs Research
       - name:        Michele Nogueira
         affiliation: Federal Univ. of Parana
       - name:        Stefano Secci
         affiliation: UPMC

    - role: Technical Program Committee
      people:
       - name:        Thomas Michael Bonhert
         affiliation: ZHAW
       - name:        Jiannong Cao
         affiliation: Hong Kong Polytechnical University
       - name:        Xu Chen
         affiliation: University of Goettingen
       - name:        Xiuzhen Cheng
         affiliation: George Washington University
       - name:        Aaron Yi Ding
         affiliation: Technical University of Munich
       - name:        Ashutosh Dutta
         affiliation: Columbia University
       - name:        Marco Fiore
         affiliation: CNR
       - name:        Xiaoming Fu
         affiliation: University of Goettingen
       - name:        Toru Hasegawa
         affiliation: Osaka University
       - name:        Pan Hui
         affiliation: HKUST/DT Innovation Laboratories
       - name:        Rittwik Jana
         affiliation: ATT
       - name:        Lito Kriara
         affiliation: Disney Research
       - name:        Jeremie Leguay
         affiliation: Huawei
       - name:        Wenzhong Li
         affiliation: Nanjing University
       - name:        Thomas Magedanz
         affiliation: Fraunhofer Fokus
       - name:        Tamer Nadeem
         affiliation: Old Dominion University
       - name:        Michele Nogueira
         affiliation: Federal University of Parana
       - name:        Kaushik Roy
         affiliation: Northeastern University
       - name:        Stefano Secci
         affiliation: UPMC
       - name:        Peter Steenkiste
         affiliation: CMU

---

## {{ page.title }}

### Call For Papers

We are living with exponential increase of mobile data traffic today due to the unprecedented growth of portable devices, Machine-to-Machine (M2M) communications, and user-generated content sharing; together with the growth of computing power of mobile devices, it is widely recognized that we are experiencing the transformation of the network infrastructure from a hardware-dominated landscape to an increasingly virtualized, software-defined, and cloud-based system. As these trends continue, a reexamination is urgently required for the architecture of the mobile-centric Internet. Particularly, there is a need to deal with new opportunities and challenges as a result of the support of massive amount of shared content and processing functionality, the availability of software defined architectures and of possibly dynamic/mobile virtualized network functions, the computational/storage support from both the cloud and edge/fog computing, and the emerging spectrum access techniques.

In particular, the explosion of user-generated data and the emergence of cloud-based mobile services are leading to the collection of vast amount of user mobility data as well as network measurement data. In this context, various networking challenges rise such as seamless IP mobility management, need for novel algorithms correlating user mobility and application usages, the online or offline exploitation of large amount of mobility and usage data from access networks and user devices, the possibility of offloading computing/storage tasks from mobile hosts to both the cloud and edge nodes, innovative algorithms correlating traffic offloading to content offloading and application offloading as a consequence of mobile data analysis, pattern inference and estimation, multi-connectivity technology exploitation for quality of service, extreme reliability in challenged scenarios with network function virtualization, etc.

To tackle these hard technical and organizational challenges, various issues need to be addressed, such as efficient mobility management and optimization, multi-homing, efficient transport over heterogeneous wireless access options, users’ incentives to reduce network congestion, incentives for network providers to deploy new/alternative mobile Internet infrastructures, incentives for service developers/providers to define new mobile services, efficient and quality-aware mobile multimedia content distribution, information-centric and mobility-aware networking solutions, collection and management of mobile M2M data in a 3-layer infrastructure with edge/fog computing and the cloud, new business models for mobile data, security and privacy, as well as related operational concerns and legal issues.


#### Topics of Interest

Within the above sketched perspective, we welcome submissions from both academia and industry that explore challenges in architectures, algorithms, protocols, middleware, and technologies in the current Internet or in the future clean-slate Internet. We focus on new network design for high performance mobile applications and services, efficient support of mobile contents, software-defined architectures, data-driven mobile network management, as well as cloud/fog-aware architecture and services.
We also encourage work-in-progress and position papers that describe highly original ideas, present new directions, or have the potential to generate insightful provocative discussion at the workshop.

We invite submissions in the following non-exhaustive list of topics:

- Architectures and protocols for mobility support at all layers of the Internet protocol stack, as well as cross-layer approaches
- Architectures and protocols for mobile edge/fog computing
- Architectures and protocols for the efficient integration of cyber-physical sensors/actuators, edge nodes, and the cloud, with offloading opportunities in the different layers
- Future Internet architecture for efficient mobility support
- Mobile network management and architecture design with data analysis and learning, in particular with reference to the technical challenges of big data and M2M data
- Software defined and/or cloud–assisted mobile networking
- Network virtualization in the mobile Internet architecture
- Impact of connected vehicles (and associated Vehicle-to-Vehicle/Vehicle-to-Infrastructure communications) on Internet architecture design
- Impact of device-to-device communications (e.g., WiFi Direct, LTE Direct, etc.) on Internet architecture design
- Mobile data sensing and fusion, in particular with reference to the technical challenges of big data and M2M data
- Impact of Information Centric Networking on mobile and wireless networks
- Cognitive networks design for mobile systems and applications
- Seamless mobility and mobility-prediction-enhanced techniques in heterogeneous networks
- Location management, positioning, and data management for wireless and mobility
- Accounting, access control, security, and privacy issues and their impact on the Internet architecture
- Social, economic, scalability, and deployment issues
- Large-scale pilots, deployment experiences, experimentation, and quantitative performance assessment of innovative mobile Internet architectures

[Contact workshop co-chairs](mailto:paolo.bellavista@unibo.it,katherine.guo@nokia-bell-labs.com?subject=[MobiArch'2017]){: data-role="button" class="button" }.

#### Submission Instructions

Submissions must be original, unpublished work, and not under consideration at another conference or journal. Submitted papers must be at most six (6) pages long, including all figures, tables, references, and appendices in two-column 10pt ACM format. Papers must include author names and affiliations for single-blind peer reviewing by the PC. Authors of accepted papers are expected to present their papers at the workshop. Accepted papers will be published in the ACM Digital Library.

Paper registration and submission can be done via HotCRP at: [https://sigcomm17mobiarch.hotcrp.com/](https://sigcomm17mobiarch.hotcrp.com/).

### Important Dates

{% include dates2.html dates=page.dates %}

## Authors Take Note

**The official publication date is the date the proceedings are made available in the ACM Digital Library. This date may be up to *TWO WEEKS* prior to the first day of your conference. The official publication date affects the deadline for any patent filings related to published work.**

### Committees

{% include committees.html committees=page.committees %}

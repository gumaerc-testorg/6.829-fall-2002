---
content_type: page
description: This section contains the background readings, the assigned readings,
  and the optional readings.
draft: false
learning_resource_types:
- Readings
ocw_type: CourseSection
title: Readings
uid: 065ed03c-b61c-e97b-68cc-671caa24bb9a
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---
The readings listed on this page are in three parts. First come the background readings. You will find them useful to get up to speed. Then come the assigned readings. Finally, we list several papers as optional readings, for you to learn more about specific topics. The schedule provides hints on when any given optional reading might be useful. All papers are named by shorthand names such as CK74.

## Background (will not be explicitly discussed in class)

**\[SRC84\]** Saltzer, J., D. Reed, and D. Clark. "End-to-end Arguments in System Design." {{% resource_link "b29636c5-aca3-445d-80c7-855f8e1a503c" "*ACM Transactions on Computer Systems (TOCS)*" %}} 2, no. 4 (1984): 195-206. (This paper is covered in 6.033.)

Ethernet paper.

**\[L0\]** Balakrishnan, H. "Single-link Communication." 6.829 Computer Networks Lecture Notes, Fall 2002. (Read this before or soon after first lecture.) ({{% resource_link "f3e7d4d9-bee7-f8d9-9ad0-d4b3cbae3e55" "PDF" %}})

## Assigned Readings (by Topic Area)

### Part I. Internetworking and Routing

**Internet Architecture**

**\[CK74\]** Cerf, V., and {{% resource_link "8d4e01f8-aa16-4173-9402-a9accc1789a9" "R. Kahn" %}}. "A Protocol for Packet Network Interconnection." {{% resource_link "25401d23-6619-43d7-9735-3ae16cb5eb4e" "*IEEE Transactions on Communications*" %}} COM-22 (1974): 637-648.

**\[Cla88\]** Clark, D. "Design Philosophy of the DARPA Internet Protocol." *Proc* {{% resource_link "69bd75c3-841b-43e3-9d68-f5eda03af375" "*ACM SIGCOMM*" %}} (August 1988): 106-114. Stanford, CA.

**\[Hin96\]** Hinden, R. "IP Next Generation Overview." *Comm of the ACM* 39, no. 6 (June 1996): 61-71.

**Unicast IP Forwarding and Routing**

**\[BCDP97\]** Brodnik, A., S. Carlsson, M. Degermark, and S. Pink. "{{% resource_link "b3383060-294c-4e9e-969b-ec1a801d5551" "Small Forwarding Tables for Fast Routing Lookups" %}}." *Proc* {{% resource_link "d0ff85ca-3804-4fca-baa7-3ad3b8a27f32" "*ACM SIGCOMM*" %}} (September {{% resource_link "5afb0f50-0041-4165-8a3a-1ff61ff610ff" "1997" %}}). Cannes, France.

**\[L4\]** Balakrishnan, H. "Wide-area Unicast Routing." 6.829 Computer Networks Lecture Notes, Fall 2002. ({{% resource_link "479e67f0-3ae6-82ec-5886-7664687a926e" "PDF" %}})

**Internet Routing in-the-Wild (Measurement)**

**\[Pax97\]** Paxson, V. "End-to-End Routing Behavior in the Internet." *IEEE/ACM Transactions on Networking* 5, no. 5 (October 1997): 601-615.

**Big Fast Routers**

**\[P+98\]** Partridge, C., et al. "A 50 Gb/s IP Router." *IEEE/ACM Transactions on Networking* 6, no. 3 (June 1998): 237-248.

**\[McK96\]** McKeown, N., M. Izzard, A. Mekkittikul, W. Ellersick, and M. Horowitz. "The Tiny Tera: A Packet Switch Core." *Proc Hot Interconnects* V (August 1996). Stanford University.

**Security Issues in the Internet Architecture**

**\[Bel89\]** Bellovin, Steven M. "Security Problems in the TCP/IP Protocol Suite ({{% resource_link "9d2ea782-3724-48f4-999b-448c3c76840c" "PDF" %}})." *Computer Communications Review* 2, no. 19 (April 1989): 32-48.

**\[Sno+01\]** Snoeren, A., C. Partridge, L. Sanchez, C. Jones, F. Tchakountio, S. Kent, and T. Strayer. "{{% resource_link "b10a427a-deea-4623-9c69-f03b7fddd658" "Hash-based IP Traceback" %}}." *Proc ACM SIGCOMM* (August {{% resource_link "bfd22335-79bc-4705-a25d-02fca6075cb4" "2001" %}}). San Diego, CA.

**Robustness**

**\[ASSW02\]** Anderson, T., S. Shenker, I. Stoica, and D. Wetherall. "Towards More Robust Internet Protocols." (July 2002).

## Part II. Resource Management

**End-to-End Congestion Control**

**\[JK88\]** Jacobson, V., and M. Karels. "Congestion Avoidance and Control." *Proc* {{% resource_link "69bd75c3-841b-43e3-9d68-f5eda03af375" "*ACM SIGCOMM*" %}} (August 1988). Stanford, CA.

**\[CJ89\]** Chiu, and D. M., and R. Jain. "Analysis of the Increase and Decrease Algorithms for Congestion Avoidance in Computer Networks." *Computer Networks and ISDN Systems* 17 (1989): 1-14.

**Router-Assisted Congestion Control, Active Queue Management, and Scheduling**

**\[FJ93\]** {{% resource_link "70538513-c8ce-4844-ac5f-cf6201781403" "Floyd, S." %}}, and V. Jacobson. "Random Early Detection Gateways for Congestion Avoidance." *IEEE/ACM Transactions on Networking* 1, no. 4 (August 1993): 397-413.

**\[KHR02\]** Katabi, D., M. Handley, and C. Rohrs. "{{% resource_link "97e79de8-00a4-430d-b9d6-b4de4c6f4757" "Congestion control for high bandwidth-delay product networks" %}}." *Proc* {{% resource_link "d0ff85ca-3804-4fca-baa7-3ad3b8a27f32" "*ACM SIGCOMM*" %}} (August 2002). Pittsburgh, PA.

**\[DKS90\]** Demers, A., S. Keshav, and {{% resource_link "9b2dd1f0-94d0-408b-89c7-e5b722cc0957" "S. Shenker" %}}. "Analysis and Simulation of a Fair Queueing Algorithm." *Internetworking: Research and Experience* 1, no. 1 (1990): 3-26. (If you like, you may also read the slightly older SIGCOMM '89 version.)

**\[SSZ98\]** {{% resource_link "f9e723ce-76c3-4a47-a544-25b9a88c0b51" "Stoica, I." %}}, {{% resource_link "9b2dd1f0-94d0-408b-89c7-e5b722cc0957" "S. Shenker" %}}, and {{% resource_link "d0ea3dd6-baf3-492a-9f68-a63172704c9f" "H. Zhang" %}}. "Core - Stateless Fair Queueing: Achieving Approximately Fair Allocations in High Speed Networks." *Proc* {{% resource_link "d0ff85ca-3804-4fca-baa7-3ad3b8a27f32" "*ACM SIGCOMM*" %}} (September {{% resource_link "c7c4d9c0-c9ce-4573-ba7e-f3c3717265d7" "1998" %}}). Vancouver, Canada. ASIN: B0006R9W38.

**Modeling and Measurement**

**\[JD02\]** Jain, M., and C. Dovrolis. "{{% resource_link "66e4fe40-b421-433e-a29b-bad37083289a" "End-to-end Available Bandwidth: Measurement Methodology, Dynamics, and Relation with TCP Throughput" %}}." *Proc* {{% resource_link "d0ff85ca-3804-4fca-baa7-3ad3b8a27f32" "*ACM SIGCOMM*" %}} (August 2002). Pittsburgh, PA.

**\[WGJPS02\]** Willinger, W., R. Govindan, S. Jamin, V. Paxson, and S. Shenker. "{{% resource_link "55afd877-ec17-4a34-9ee7-c80aff79c3df" "Scaling phenomena in the Internet: Critically examining criticality" %}}." *Proc Natl Acad Sci USA* 99, supplement 1 (February 19, 2002): 2573-2580.

**\[SPW02\]** Staniford, S., V. Paxson, and N. Weaver. "{{% resource_link "136da483-24e0-492a-9546-8facff32fb64" "How to 0wn the Internet in Your Spare Time" %}}." *Proc USENIX Security Symp* (August 2002). San Francisco, CA.

**Adaptive Applications and Internet QoS**

**\[CT90\]** Clark, D., and D. Tennenhouse. "Architectural Consideration for a New Generation of Protocols." *Proc* {{% resource_link "69bd75c3-841b-43e3-9d68-f5eda03af375" "*ACM SIGCOMM*" %}} (September 1990). Philadelphia, PA.

**\[BSR99\]** Balakrishnan, H., S. Seshan, and H. Rahul. "An Integrated Congestion Management Architecture for Internet Hosts." *Proc ACM SIGCOMM* (September {{% resource_link "2d6ca676-f1bd-42ba-aee4-38c99ffdb94a" "1999" %}}). Cambridge, MA.

**\[She95\]** Shenker, S. "Fundamental Design Issues for the Future Internet." *IEEE Journal on Selected Areas in Communications* 13, no. 7 (September 1995): 1176-1188.

**\[CSZ92\]** Clark, D., {{% resource_link "ed0503e1-7cc2-455d-92df-ebf9b1d805a3" "S. Shenker" %}}, and L. Zhang. "Supporting Real-Time Applications in an Integrated Services Packet Network: Architecture and Mechanisms." *Proc* {{% resource_link "69bd75c3-841b-43e3-9d68-f5eda03af375" "*SIGCOMM*" %}} *'92 (* August 1992). Baltimore, MD.

**\[CF98\]** Clark, D., and W. Feng. "Explicit Allocation of Best-Effort Packet Delivery Service." *IEEE/ACM Transactions on Networking* 6, no.4 (August 1998): 362-373.

## Part III. Network Services

**Wireless/Mobile Networking**

**\[BMJ+98\]** Broch, J., D. Maltz, {{% resource_link "7c2cdb8a-0c75-4c0d-b0fc-e1ee089c181e" "D. Johnson" %}}, Y. C. Hu, and J. Jetcheva. "A Performance Comparison of Multi-Hop Wireless Ad Hoc Routing Protocols." *Proc ACM MOBICOM* (August 1998). Dallas, TX.

**\[IGE00\]** Intanagonwiwat, C., {{% resource_link "f67c931d-bff6-4342-b6a7-1516f01ee906" "R. Govindan" %}}, and {{% resource_link "1b077b7d-15b1-43c8-bbc9-9828852ebf05" "D. Estrin" %}}. "{{% resource_link "28e9b933-6af8-4022-abfc-055557fd70e6" "Directed diffusion: A scalable and robust communication paradigm for sensor networks" %}}." *Proc ACM MOBICOM* (August 2000). Boston, MA.

**\[BDSZ94\]** Bharghavan, V., A. Demers, {{% resource_link "9b2dd1f0-94d0-408b-89c7-e5b722cc0957" "S. Shenker" %}}, and L. Zhang. "MACAW: A Media Access Protocol for Wireless LANs." *Proc* {{% resource_link "69bd75c3-841b-43e3-9d68-f5eda03af375" "*ACM SIGCOMM*" %}} (September 1994): 212-225. London, UK.

**\[BSK95\]** Balakrishnan, H., {{% resource_link "4a5fbc6b-c2e5-493b-837d-3613f605085d" "S. Seshan" %}}, and {{% resource_link "58b59d13-bde1-4737-9598-3bc8e773b4d2" "R. Katz" %}}. "Improving Reliable Transport and Handoff Performance in Cellular Wireless Networks." *ACM Wireless Networks* 1, no. 4 (December 1995).

**Naming: DNS**

**\[JSBM01\]** Jung, J., E. Sit, H. Balakrishnan, and R. Morris. "DNS Performance and the Effectiveness of Caching." *Proc ACM SIGCOMM Internet Measurement Workshop* (November 2001). San Francisco, CA. ({{% resource_link "d7507e71-b1cd-4163-a29e-a2d11fd78f46" "PDF" %}})

**Peer-to-Peer Networking, Distributed Hash Tables**

**\[SMKKB01\]** {{% resource_link "6ca24e52-50dc-4247-bbe3-1dca1e298410" "Stoica, I." %}}, R. Morris, D. Karger, M. Kaashoek, and H. Balakrishnan. "Chord: A Scalable Peer-to-peer Lookup Service for Internet Applications." *Proc* {{% resource_link "d0ff85ca-3804-4fca-baa7-3ad3b8a27f32" "*ACM SIGCOMM*" %}} (August {{% resource_link "bfd22335-79bc-4705-a25d-02fca6075cb4" "2001" %}}). San Diego, CA.

**\[BKKMS03\]** ———. Looking Up Data in P2P Systems, *Comm. of the ACM* (February 2003).

**\[CSWH00\]** Clarke, I., O. Sandberg, B. Wiley, and T. Hong. "Freenet: A Distributed Anonymous Information Storage and Retrieval System." *Proc ICSI Workshop on Design Issues in Anonymity and Unobservability* (July 2000). Berkeley, CA.

**Overlay Routing**

**\[ABKM01\]** {{% resource_link "80e4f79e-1263-4bc0-9aca-ee832386ccd3" "Andersen, D." %}}, H. Balakrishnan, M. Kaashoek, and R. Morris. "Resilient Overlay Networks." *Proc 18th ACM SOSP* (October 2001). Banff, Canada.

**\[Sto+02\]** {{% resource_link "6ca24e52-50dc-4247-bbe3-1dca1e298410" "Stoica, I." %}}, D. Adkins, S. Zhuang, S. Shenker, and S. Surana. "{{% resource_link "99d5dc61-b911-4722-bcb6-bd4cfd4c59bf" "Internet Indirection Infrastructure" %}}." *Proc* {{% resource_link "d0ff85ca-3804-4fca-baa7-3ad3b8a27f32" "*ACM SIGCOMM*" %}} (August 2002). Pittsburgh, PA.

**Multicast**

**\[MS97\]** Maufer, T., and C. Semeria. "Introduction to IP Multicast Routing." Internet-Draft, July 1997.

**\[F+97\]** {{% resource_link "7a8c1439-5dd8-4c4a-97ce-5eb355f51591" "Floyd, S." %}}, V. Jacobson, C. Liu, S. McCanne, and L. Zhang. "A Reliable Multicast Framework for Light-Weight Sessions and Application Level Framing." *IEEE/ACM Transactions on Networking* (1997).

**Optional Additional Readings and References**

**\[LABJ00\]** Labovitz, C., A. Ahuja, A. Bose, and F. Jahanian. "Delayed Internet Routing Convergence." *Proc* {{% resource_link "96f0264f-f717-4c91-8b9a-38c3e0cd5be2" "*ACM SIGCOMM*" %}} (September {{% resource_link "ca7a16c1-64b8-4f1c-88f4-5c4de1620523" "2000" %}}): 175-187. Stockholm, Sweden.

**\[Nor00\]** Norton, W. "Internet Service Providers and Peering." 2000.

**\[BV01\]** Baboescu, F., and G. Varghese. "Scalable Packet Classification." *Proc* {{% resource_link "d0ff85ca-3804-4fca-baa7-3ad3b8a27f32" "*ACM SIGCOMM*" %}} (August {{% resource_link "bfd22335-79bc-4705-a25d-02fca6075cb4" "2001" %}}). San Diego, CA.

**Network Protection**

**\[SWKA00\]** {{% resource_link "2415b6d6-1edb-4b51-b923-86dd74abd6b7" "Savage, S." %}}, {{% resource_link "64a6f9be-4fa6-4b70-8a4d-74ee327e0207" "D. Wetherall" %}}, {{% resource_link "04c420e9-2e38-4e92-8b4e-62405709190c" "A. Karlin" %}}, and {{% resource_link "e5d09f6f-adc2-4e01-b150-d715ee3a1ec8" "T. Anderson" %}}. "Practical Network Support for IP Traceback." *Proc ACM SIGCOMM* September {{% resource_link "84a714ca-663d-431b-9b96-94a3647e65f7" "2000" %}}. Stockholm, Sweden. ({{% resource_link "84a714ca-663d-431b-9b96-94a3647e65f7" "PDF" %}})

**Reliable Transport and Congestion Control**

**\[FF96\]** Floyd, S., and K. Fall. "A Simulation Comparison of Tahoe, Reno, and SACK TCP." *ACM SIGCOMM CCR* (1996).

**\[FF99\]** {{% resource_link "d6982e61-6d8d-4ebf-a6a0-c14151a6a108" "Floyd, S." %}}, and K. Fall. "{{% resource_link "862a0d91-79e8-40aa-9a1e-1acbaddc589c" "Promoting the Use of End-to-End Congestion Control in the Internet" %}}." *IEEE/ACM Transactions on Networking* 7, no. 4 (August 1999): 458-472.

**\[RJ90\]** Ramakrishnan, K. K., and R. Jain. "A Binary Feedback Scheme for Congestion Avoidance in Computer Networks." {{% resource_link "b29636c5-aca3-445d-80c7-855f8e1a503c" "*ACM Transactions on Computer Systems (TOCS)*" %}} 8, no. 2 (May 1990): 158-181.

**\[FHPW01\]** Floyd, S., M. Handley, J. Padhye, and J. Widmer. "Equation-Based Congestion Control for Unicast Applications." *Proc* {{% resource_link "d0ff85ca-3804-4fca-baa7-3ad3b8a27f32" "*ACM SIGCOMM*" %}} (August {{% resource_link "ca7a16c1-64b8-4f1c-88f4-5c4de1620523" "2000" %}}). Stockholm, Sweden. ({{% resource_link "7455203b-693f-438c-b4f6-c3daeca1d698" "PDF" %}})

**\[BB01\]** Bansal, D., and H. Balakrishnan. "Binomial Congestion Control Algorithm." *Proc IEEE INFOCOM* (April 2001). Anchorage, AK.

**\[SEW01\]** Spring, N., D. Ely, D. Wetherall, S. Savage, and T. Anderson. "Robust ECN Signaling." *Proc International Conf on Network Protocols* (November 2001). Riverside, CA.

**Unicast Routing**

**\[Huitema96\]** Huitema, C. *Routing in the Internet*. Upper Saddle River, NJ: Prentice Hall, January 15, 2000. ISBN: 0130226475. (Search for Huitema on the Prentice Hall site.)

**\[LMJ97\]** Labovitz, C., R. Malan, and F. Jahanian. "{{% resource_link "0a17e9ca-2728-4376-bd23-ee47b5e3f0ee" "Internet Routing Instability" %}}." *Proc* {{% resource_link "d0ff85ca-3804-4fca-baa7-3ad3b8a27f32" "*ACM SIGCOMM*" %}} (September {{% resource_link "5afb0f50-0041-4165-8a3a-1ff61ff610ff" "1997" %}}). Cannes, France.

**\[Stewart99\]** Stewart, J. *BGP4 Inter-Domain Routing in the Internet*. Reading, MA: Addison-Wesley, January 1999. ISBN: 0201379511.

**\[Tsu88\]** Tsuchiya, P. "The Landmark Hierarchy: A New Hierarchy for Routing in Very Large Networks." *Proc ACM SIGCOMM* (August 1988): 35-42. Stanford, CA.

**Adaptive and Network-Aware Applications**

**\[PM95\]** {{% resource_link "bff1ea47-2419-4475-bf4f-9bc3f69662b7" "Padmanabhan, V." %}}, and J. Mogul. "Improving HTTP Latency." *Computer Networks and ISDN Systems* 28 (December 1995): 25-35.

**\[RHE99\]** Rejaie, R., {{% resource_link "42e38899-dd65-4d02-ad7c-e06b48f515e1" "M. Handley" %}}, and {{% resource_link "1b077b7d-15b1-43c8-bbc9-9828852ebf05" "D. Estrin" %}}. "{{% resource_link "178e40e2-f521-45a0-9ae7-6aac2b838e91" "Quality Adaptation for Congestion Controlled Video Playback over the Internet" %}}." {{% resource_link "2d6ca676-f1bd-42ba-aee4-38c99ffdb94a" "*Proc ACM SIGCOMM*" %}} (September 1999).

**Traffic Engineering, Flow Modeling**

**\[Elw01\]** Elwalid, A., C. Jin, S. Low, and I. Widjaja. "MATE: MPLS Adaptive Traffic Engineering." *Proc IEEE INFOCOM* (2001). Anchorage, AK.

**\[EV02\]** Estan, C., and G. Varghese. "{{% resource_link "25b460a5-b9b8-4e72-8321-e4afaec7f013" "New directions in traffic measurement and accounting" %}}." *Proc* {{% resource_link "d0ff85ca-3804-4fca-baa7-3ad3b8a27f32" "*ACM SIGCOMM*" %}} (August 2002). Pittsburgh, PA.

**Multicast Routing/Transport**

**\[DC90\]** Deering, S., and {{% resource_link "f60e934f-efdf-4017-91b8-5f97fff7fd4a" "D. Cheriton" %}}. "Multicast Routing in Datagram Internetworks and Extended LANs." {{% resource_link "b29636c5-aca3-445d-80c7-855f8e1a503c" "*ACM Transactions on Computer Systems (TOCS)*" %}} 8, no. 2 (May 1990): 85-110.

**\[DE+94\]** Deering, S., {{% resource_link "1b077b7d-15b1-43c8-bbc9-9828852ebf05" "D. Estrin" %}}, D. Farinacci, V. Jacobson, C. G. Liu, and L. Wei. "An Architecture for Wide-Area Multicast Routing." *Proc* {{% resource_link "69bd75c3-841b-43e3-9d68-f5eda03af375" "*ACM SIGCOMM*" %}} (September 1994). London, UK.

**\[HC99\]** Holbrook, H., and D. Cheriton. "IP Multicast Channels: EXPRESS Support for Large-scale Single-source Applications." *Proc* {{% resource_link "a2bd6333-1489-4701-b8df-a3a36b20629d" "*ACM SIGCOMM*" %}} (September {{% resource_link "2d6ca676-f1bd-42ba-aee4-38c99ffdb94a" "1999" %}}). Cambridge, MA.

**\[MJV96\]** McCanne, S., V. Jacobson, and {{% resource_link "95bcb19c-a923-4421-abe0-02018cbe3ab3" "M. Vetterli" %}}. "Receiver-driven Layered Multicast." *Proc* {{% resource_link "69bd75c3-841b-43e3-9d68-f5eda03af375" "*ACM SIGCOMM*" %}} (August 1996). Stanford, CA.

**\[Pap98\]** Papadopoulos, C. "{{% resource_link "5487beb8-e12f-4ab4-a697-25f2a61a6acc" "An Error Control Scheme for Large-Scale Multicast Applications" %}}." *Proc IEEE INFOCOM '98* (March 1998). San Francisco, CA.

**\[BTW94\]** Turletti, T., and I. Wakeman. "Scalable Feedback Control for Multicast Video Distribution in the Internet." *Proc* {{% resource_link "69bd75c3-841b-43e3-9d68-f5eda03af375" "*ACM SIGCOMM*" %}} (September 1994). {{% resource_link "f7200220-4790-48ff-8ca5-e9997b942148" "London" %}}, UK.

**Wireless Protocols**

**\[Joh96\]** {{% resource_link "7c2cdb8a-0c75-4c0d-b0fc-e1ee089c181e" "Johnson, D." %}} "Scalable Support for Transparent Mobile Host Internetworking." Chapter 3 in *Mobile Computing.* Edited by T. Imielinski and H. Korth. Kluwer Academic Publishers, 1996, pp. 103-128.

**\[SB00\]** Snoeren, A., and H. Balakrishnan. "An End-to-End Approach to Host Mobility." *Proc* {{% resource_link "6feb05aa-ff11-498b-8b7c-2a425c6d93eb" "*ACM MOBICOM*" %}} (August 2000). Boston, MA.

**\[She96\]** Shepard, T. J. "A Channel Access Scheme for Large Dense Packet Radio Networks." *Proc ACM SIGCOMM* (August 1996). Stanford, CA.

**\[J+01\]** Li, J., C. Blake, D. De Couto, H. Lee, and R. Morris. "Capacity of Wireless Ad Hoc Networks." *Proc* {{% resource_link "e856da16-f1ae-4a7c-88c7-f5294862ed79" "*ACM MOBICOM*" %}} (July 2001). Rome, Italy.

**\[CJBM01\]** Chen, B., K. Jamieson, H. Balakrishnan, and R. Morris. "Span: An Energy-Efficient Coordination Algorithm for Topology Maintenance in Ad Hoc Wireless Networks." *Proc* {{% resource_link "e856da16-f1ae-4a7c-88c7-f5294862ed79" "*ACM MOBICOM*" %}} (July 2001). Rome, Italy.

## Naming

**\[MD88\]** Mockapetris, P., and K. Dunlap. "Development of the Domain Name System." *Proc* {{% resource_link "69bd75c3-841b-43e3-9d68-f5eda03af375" "*ACM SIGCOMM*" %}} (August 1988). {{% resource_link "8b857d9c-78af-493a-a55b-d1537de29e06" "Stanford" %}}, CA.

## Web Caching

**\[FCAB98\]** Fan, L., P. Cao, J. Almeida, and A. Broder. "{{% resource_link "e06caefc-4004-4788-8e27-f658a8a5a860" "Summary Cache: A Scalable Wide-Area Cache Sharing Protocol" %}}." {{% resource_link "7df49ab4-86ca-4c2b-a64e-f2bda96c1b95" "*Proc SIGCOMM '98*" %}} (September 1998): 254-265. Vancouver, Canada.

## Introducing New Services: Overlays v. Active Networks

**\[W99\]** {{% resource_link "64a6f9be-4fa6-4b70-8a4d-74ee327e0207" "Wetherall, D." %}} "Active network vision and reality: Lessons from a capsule-based system." *Proc* {{% resource_link "8756cef2-870e-4103-be7b-403f815eaa5f" "*17th SOSP*" %}} December 1999. Kiawah Island, SC.

**Modeling and Measurement**

**\[Pax97\]** Paxson, V. "{{% resource_link "2996312b-bf3b-4644-8001-2ad3b2939ff4" "End-to-End Internet Packet Dynamics" %}}." *Proc* {{% resource_link "d0ff85ca-3804-4fca-baa7-3ad3b8a27f32" "*ACM SIGCOMM*" %}} (September 1997): 139-152. Cannes, France.

**\[Bol93\]** Bolot, J. C. "End-to-End Packet Delay and Loss Behavior in the Internet." *Proc* {{% resource_link "69bd75c3-841b-43e3-9d68-f5eda03af375" "*ACM SIGCOMM*" %}} (August 1993). San Francisco, CA.

**\[LTWW94\]** Leland, W. E., M. S. Taqqu, W. Willinger, and D. V. Wilson. "On the Self-Similar Nature of Ethernet Traffic." *IEEE/ACM Transactions on Networking* 2, no. 1 (February 1994): 1-15.

Paper on Topology Modeling.
# Deep-learning-for-Network-Traffic-classification
Multiclass classification using deep learning

In a typical network, the traffic through the network is heterogeneous and consists of flows from multiple applications and utilities. Many of these applications are unique and have their own requirements with respect to network parameters such as delay, jitter, etc. Unless these requirements are met, the quality and usability of these applications will be severely compromised. While meeting these requirements in a Local Area Network (LAN) with its huge bandwidth might be easy, it usually is a challenge to meet them on the WANs, which have bandwidth constraints.

Thus, traffic management on the WANs must exist in order to properly prioritize different applications across the limited WAN bandwidth and ensure that these requirements are met. In addition, a proper understanding of the applications and protocols in the network traffic is essential for any network manager to implement appropriate security policies. In a real network, user perception also matters. Although a user application might allow large delays or jitter, the user might be very sensitive to long wait times. Managing network traffic thus requires a judicious balance of all these priorities.

Anomaly-based intrusion detection techniques are valuable methodology to detect both known as well as unknown/new attacks, so they can cope with the diversity of the attacks and the constantly changing nature of network attacks. There are many problems need to be considered in anomaly-based network intrusion detection system (NIDS), such as ability to adapt to dynamic network environments, unavailability of labelled data, false positive rate. 


In contrast, in this study, a deep learning based approach is proposed which does automatic feature extraction and classification in layer by layer of neural networks. This technique aims to learn a good feature representation from a large amount of data.  Also the streaming data has noise, so to handle this stacked denoising auto-encoder will be used. Further the network traffic classification will be done using DNN model of tensor flow and python and to train this model a UNSW network traffic dataset will be used. In anomaly-based NIDS above improvements would lead to better classification accuracy.


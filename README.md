# Anomaly-Detection-Using-GMPM-to-Implement-IDS

**Abstract:** Network intrusion detection systems (NIDS) play a crucial role in identifying and mitigating potential cybersecurity threats by detecting attacks and anomalous patterns in network traffic. This paper explores the use of anomaly detection algorithms to pinpoint unusual behavior or outliers in network traffic, generating timely alarms to prevent security issues. While Gaussian Mixture Models (GMMs) have conventionally been employed for probabilistic-based anomaly detection in NIDS, our proposal advocates for the utilization of multiple simple GMMs to model individual features.

Furthermore, we introduce an asymmetric voting scheme that consolidates individual anomaly detectors to enhance overall detection capabilities. To validate our approach, we conduct experiments using the NSL dataset. Normal behavior models are constructed exclusively from samples labeled as normal in the dataset, and our proposal is evaluated against the official NSL testing set.

The results demonstrate the effectiveness of our approach, yielding a Fl-score exceeding 0.9, thereby outperforming both supervised and unsupervised proposals.

**Keywords:** Intrusion Detection, Gaussian Mixture Model, Voting

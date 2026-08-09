# Research on the Effectiveness of Machine Learning Methods for Detecting Botnets that Use the Fast-Flux Technique

The work covered the features of the functioning of botnets that use the fast-flux technique, which ensures the masking of the botnet management infrastructure and complicates their detection and blocking by traditional means of protection. The principles of the functioning of single-flux and double-flux are analyzed, auxiliary mechanisms of this type of attack in DNS traffic are identified, and network characteristics that can be used to detect such botnets are considered, in particular, the number and frequency of IP address changes, the geographical distribution of autonomous systems and countries of origin of IP addresses, Time-To-Live parameters and other indicators.

The object of the study is the process of detecting botnets that use the fast-flux technique based on the analysis of DNS traffic and network characteristics. The subject of the study is the effectiveness of using machine learning models to detect fast-flux domains.

The paper implements an experimental study of machine learning methods for classifying fast-flux domains. In particular, the effectiveness of logistic regression and isolation forest models was investigated, their comparative analysis was performed for three categories of quality metrics, and the advantages and limitations of each approach were determined. In order to combine high classification accuracy and the ability to detect anomalous samples, two variations of the hybrid (cascade) model were proposed, which combine the advantages of the algorithms under study.

Used tools and data:
- [Anaconda Navigator](https://www.anaconda.com/products/navigator)
- [Jupyter Notebook](https://jupyter.org)
- [IPtoASN](https://iptoasn.com)
- [CTU-13-Malware-Botnet-54](https://mcfp.felk.cvut.cz/publicDatasets/CTU-Malware-Capture-Botnet-54/)
- [CTU-13-Malware-Botnet-46](https://mcfp.felk.cvut.cz/publicDatasets/CTU-Malware-Capture-Botnet-46/)

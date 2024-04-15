# Datasets to be used in bootstrapping the Robocop IDS: 
1. [MACCDC2012](http://www.netresec.com/?page=MACCDC):
  - This dataset provides a comprehensive collection of network traffic logs generated using Bro (now known as Zeek) and Snort. It includes various types of logs such as FTP, DNS, HTTP, SSL, and more. The dataset covers a range of activities from scanning and reconnaissance to exploitation and post-exploitation. It offers a diverse set of labeled data that can be valuable for training Robocop to detect different stages of an attack lifecycle

2. Bro/Zeek logs generated from various Threatglass samples: [Part 1](https://drive.google.com/drive/folders/1VbEFcYEHbJVhpqBGruCGVF1JV8rcE07Q) [Part 2](https://drive.google.com/drive/folders/16d-t64pDmjOcVj4HDAGGWhRsNmSGt7IU) [Part 3](https://drive.google.com/drive/folders/1rX58LxBglYW72TVLQWOKdy9vnDkDuDqi) 
  - This dataset contains exploit kits and benign traffic, providing a mix of malicious and normal network activity. Although the data is unlabeled, it can be used to enhance the diversity of the training data and help Robocop learn to distinguish between malicious and benign traffic patterns.

3. [Comprehensive, Multi-Source Cyber Security Events](https://csr.lanl.gov/data/cyber1/):
  - This dataset includes authentication, DNS, process, and flow data, offering a comprehensive view of network and system events. It can help train the IDS system to correlate events across different data sources and identify complex attack patterns.

4. [MIT 1999 DARPA Intrusion Detection Evaluation Data Set](http://www.ll.mit.edu/mission/communications/cyber/CSTcorpora/ideval/data/1999data.html) and [MIT 1998 DARPA Intrusion Detection Evaluation Data Set](http://www.ll.mit.edu/mission/communications/cyber/CSTcorpora/ideval/data/1998data.html):
  - These labeled datasets contain network and system data, including attack and non-attack scenarios. They are widely used benchmarks for evaluating IDS systems and can help assess the performance of trained models.

5. [Malware Traffic Analysis](http://malware-traffic-analysis.net/):
  - This site provides labeled exploit kits and phishing emails, which can be used to train the IDS system to detect specific types of malicious network traffic and email-based threats.

6. [The Malware Capture Facility Project](https://mcfp.weebly.com/the-ctu-13-dataset-a-labeled-dataset-with-botnet-normal-and-background-traffic.html):
  - The published long-runs of malware, including network information and the labeled CTU-13 dataset, can provide valuable insights into malware behavior and help train the IDS system to detect malicious network activity.
    
9.  [EMBER Dataset](https://github.com/elastic/ember) [in depth description](https://arxiv.org/abs/1804.04637):
  - Although this dataset focuses on PE files rather than network traffic, it can still be useful for training Robocop's machine learning models. The dataset includes features and labels from 1.1 million benign and malicious PE files, along with a trained model. We can leverage this dataset to enhance Robocop's ability to detect malicious files or incorporate file-based analysis into the IDS pipeline.

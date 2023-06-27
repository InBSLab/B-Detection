# B-Detection
A boosting Long Short-Term Memory (LSTM) Autoencoder for detecting MEC services’ runtime reliability anomalies based on distribution dissimilarity evaluation. B-Detection adopts an LSTM Autoencoder as the base anomaly detector that can capture normal reliability data stream distribution features. To better model the distribution characteristics of MEC services’ historical reliability streaming data and ensure the real-time performance of anomaly detection model, B-Detection employs a dynamic weight-based reservoir sampling algorithm to sample normal reliability data for model training. It also employs a boosting algorithm to dynamically modify the sampling of normal reliability data and to retrain the detection model according to the detection performance.

***Please refer to the following paper for a detailed description of the B-Detection approach:

[1] Lei Wang, Shuhan Chen, Feifei Chen, Qiang He, and Jiyuan Liu, "B-Detection: Runtime Reliability Anomaly Detection for MEC Services with Boosting LSTM Autoencoder," IEEE Transactions on Mobile Computing, 2023. DOI: 10.1109/TMC.2023.3262233. (early access article)
***IF YOU ARE INSPIRED BY THIS SOURCE CODE IN PUBLISHED RESEARCH, PLEASE CITE THE ABOVE PAPER. THANKS!

***IF YOU ARE INSPIRED BY OUR TECHNIQUE FOR YOUR COMMERCIAL USED SYSTEMS, COULD PLEASE LET US KNOW? THANKS!

# deepLNCrnaPredictor
## A Deep learning model for the prediction of long non-coding RNAs from RNA-seq data

The significant role of long non-coding RNAs (lncRNAs) in various cellular functions, such as gene imprinting, immune response, embryonic pluripotency, tumorogenesis, and genetic regulations, has been widely studied and reported in recent years. Several experimental and computational methods involving genome-wide search and screenings of ncRNAs are being proposed utilizing sequence features-length, occurrence, and composition of bases with various limitations. The proposed classifier, Deep Neural Network (DNN) is fast and an accurate alternative for the identification of lncRNAs as compared to other existing classifiers. The information content stored in k-mer pattern has been used as a sole feature for the DNN classifier using manually annotated training datasets from LNCipedia and RefSeq database, obtaining accuracy of 98.8 %, sensitivity of 98.98 %, and specificity of 97.19 %, respectively, on test dataset. In k-mer k=6 gives the optimal results for the model. This classification framework was also tested on known human genome dataset, and the framework has successfully identified known lncRNAs with 98% accuracy rate.

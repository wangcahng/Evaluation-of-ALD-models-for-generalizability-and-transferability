Evaluating the generalizability and transferability of acoustic leak detection models for water distribution networks
'''
Acoustic Leak Detection (ALD) plays a pivotal role in ensuring the operational safety of water distribution networks (WDNs). However, the cross-domain deployment of single-scenario ALD models is significantly hindered by environmental heterogeneity (pipe materials and diameters, etc.) and data scarcity in practical WDNs. This study presents the first systematic investigation into the generalizability and transferability of ALD models across multi-source WDNs through comprehensive cross-domain evaluation. The results show that: (1) The global model trained on the multi-region WDNs exhibits better generalization ability with an average accuracy improvement of about 2% compared to the local model. (2) Fine Tuning strategy achieves high transfer performance (96.8% and 96.2% accuracy for cross-material and cross-diameter scenarios respectively), outperforming Direct Transfer and Feature Extraction methods. (3) Transfer asymmetry correlates with spectrogram feature compatibility, where metal-to-nonmetal and large-to-small diameter transfers exhibit enhanced adaptability through broader source-domain frequency coverage. (4) Target-domain data requirements with the Fine Tuning strategy can be reduced by 50% while maintaining superior accuracy compared to source-domain local models. These findings advance AI-driven ALD techniques from a single-scenario-specific perspective to more mature applications of multi-scenario-universal.
'''
python = 3.8.7 
TensorFlow-gpu = 2.5.0 
numpy = 1.22.0 
pandas = 1.2.5 
librosa = 0.10.2 
scikit-learn = 1.3.2

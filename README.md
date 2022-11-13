Pancreatic cancer is a highly malignant cancer type with a high mortality rate. As no obvious symptoms are associated with this cancer type, most of the diagnoses are made when the patients are already in a late stage. In this work, we propose an automated method for effective early diagnosis of pancreatic cancer based on multiple instance learning with contrast-enhanced CT images. In this method, diagnosis stability and generalizability were improved through shape normalization based on anatomical structures as well as instance-level contrastive learning. Specifically, anatomically-guided shape normalization were developed to reconstruct the pancreatic regions of interest by spatial transformations, account for larger tumor parts in these regions, and hence enhance the extraction of pancreatic features. Moreover, instance-level contrastive learning was employed to aggregate different types of tumor features within the multiple instance learning framework. This learning approach can maintain the tumor feature integrity and enhance the diagnosis stability. Finally, a balance-adjustment strategy was designed to alleviate the class imbalance problem caused by the scarcity of tumor samples. Extensive experimental results demonstrated remarkable performance of our method when conducted cross-validation on an in-house dataset with 310 patients and independent test on two unseen datasets (a private test set with 316 and a publicly-available test set with 281). The proposed strategies also led to significant improvements in generalizability. Besides, the clinical significance of the proposed method was further verified through two independent test results in which tumors smaller than 2 cm in diameter were identified at accuracies of 80.9% and 90.1%, respectively. Overall, our method provides a potentially successful tool for early diagnosis of pancreatic cancer.
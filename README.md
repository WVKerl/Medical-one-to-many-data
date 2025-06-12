# Medical Multi-Document Retrieval Dataset

## Overview

The Medical Multi-Document Retrieval Dataset is a curated benchmark for training and evaluating dense retrievers in medical question-answering scenarios. Unlike traditional one-to-one retrieval datasets, each clinical query in this collection is associated with **multiple** relevant documents covering complementary aspects of the case. This “one-to-many” structure more closely mirrors real-world clinical workflows, where comprehensive answers often require integrating evidence on symptoms, diagnostics, treatments and follow-up care from different guideline sections.

The dataset covers three major specialties:

- **General Medicine**: broad, cross-disciplinary clinical scenarios  
- **Cardiology**: multi-step evidence integration in complex cardiac cases  
- **Dermatology**: fine-grained symptom recognition and lesion classification  

In total, the dataset comprises **3 054** unique clinical queries, each paired with **1–5** relevant document segments drawn from peer-reviewed guidelines, government reports, and academic publications.




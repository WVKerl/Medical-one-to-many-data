# Medical Multi-Document Retrieval Dataset

## Overview

The Medical Multi-Document Retrieval Dataset is a curated benchmark for training and evaluating dense retrievers in medical question-answering scenarios. Unlike traditional one-to-one retrieval datasets, each clinical query in this collection is associated with **multiple** relevant documents covering complementary aspects of the case. This “one-to-many” structure more closely mirrors real-world clinical workflows, where comprehensive answers often require integrating evidence on symptoms, diagnostics, treatments and follow-up care from different guideline sections.

The dataset covers three major specialties:

- **General Medicine**: broad, cross-disciplinary clinical scenarios  
- **Cardiology**: multi-step evidence integration in complex cardiac cases  
- **Dermatology**: fine-grained symptom recognition and lesion classification  

In total, the dataset comprises **3 052** unique clinical queries, each paired with **1–5** relevant document segments drawn from peer-reviewed guidelines, government reports, and academic publications.




## Test Dataset Overview

This project includes a medical multiple-choice question test set extracted from three professional physician question banks. All questions are single-choice questions with five options (A–E) in JSON Lines format, with one record per line. The fields are described as follows:

- **question** (string): question stem  
- **options** (object): 5 key-value pairs, with keys `“A”`, `“B”`, `“C”`, `‘D’`, `“E”`, and values corresponding to the option text
- **answer** (string): Correct option label (`“A”`–`“E”`)

### Test Set Overview

| Test Set              | File Name                            | Number of Questions |  
|--------------------|------------------------------------|----------|  
| Cardiovascular Internal Medicine         | `Cardiovascular test.jsonl`        | 97       |  
| General Medicine/Basic Consultation  | `General medical examination.jsonl`| 98       |  
| Dermatology             | `Skin test.jsonl`                  | 120      |  

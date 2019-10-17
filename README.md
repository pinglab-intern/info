

### Project : Disease normalization for heart failure and atherosclerosis pathologies.

  When diseases are mentioned in biomedical documents, they may be referred to by a variety of names or terms.
  Our goal in examining numerous documents, however, demands finding conceptual similarities among them.
  How may we link these terms to a consistent vocabulary or set of concepts?
  (This is a combination of two tasks: named entity recognition and concept linking.
  Historically, this was done by combinations of dictionary lookup and rule-based methods.
  But we now have machine-learning and embedding-based models which offer distinct accuracy and flexibility advantages.)
  Tools such as DNorm (PMID: 23969135; see also BANNER, PMID: 18229723) can perform this normalization with general biomedical language.
  
- How well do these tools work with our target subject?
- How accurately can they normalize disease concepts within clinical language (i.e., that in clinical case reports, or CCRs)?
- How may we adapt the underlying methods to best perform disease normalization within CCRs?
- The concepts that tools like DNorm link to may not be the most useful or specific for our intended use cases.
- Can we adapt these methods to link terms to different sets of concepts (e.g., ICD-11)?
 
#### TO DO:
1. Learn how to label terminology within HF CCRs (and label a set of HFpEF CCRs) and learn NLP basics (Harry, David assists) Week 1-2
2. Apply disease term normalization (DNorm) to CCR text (Harry) Week 3
3. Begin familiarization with ICD-11 and linking relevant disease concepts to ICD-11 codes (Harry, Dibakar) Week 4,6
4. Visualize the relationships between diseases and ICD-11 codes for a set of HF CCRs (Dibakar, David) Week 7-9
 
#### Further Reading:
* NCBI Disease Corpus - Doğan et al. (2014) PMID: 24393765
* A (recent) review of biomedical NER - Song et al. (2018) PMID: 30396340
* Familiarity with UMLS resources (https://www.nlm.nih.gov/research/umls/index.html)
* Familiarity with ICD-11 (https://icd.who.int/icd11refguide/en/index.html)
 
### Project:  Building cardiovascular knowledge graphs using the CaseOLAP pipeline.

  Knowledge graphs (KGs) are intuitive data structures for organizing biomedical observations.
  These heterogeneous graphs represent the relationships between varied clinical and experimental phenomena.
  In our group, we recognize two distinct types of datasets contributing to KGs:
    structured knowledge (i.e., that defined by curated knowledge bases), and
    loosely structured or unstructured information (i.e., single sets of real-world observations from clinical or experimental studies).
  Our overall goal is to construct methods for organizing this information in an automated manner.
  At present, however, the most efficient way to do so is manually.
  Manual KG assembly allows for strict control over data curation standards.
  
  - What challenges may we encounter in manual assembly of KGs defining cardiovascular phenomena from both clinical and experimental documents?
  - Which curated knowledge bases may contribute the most informative concepts to a cardiovascular KG?
  - What may a cardiovascular KG tell us that a traditional database may not?
 
  TO DO:
-  Become familiar with the CaseOLAP pipeline (Dibakar) - Week 1
-  Assemble documents from PubMed (on drugs sensitive to oxidative stress) (Dibakar) Week 2
-  Identify drug-disease relationships (Dibakar/David) - Week 3-4
-  Learn how to manually create KG from drug-disease relationships and integrate with knowledgebases (Reactome) (Harry) Week 6-9
 
##### Further Reading:
- Our group's recent paper/video on CaseOLAP phrase mining - Sigdel et al. (2019) PMID: 30855564
- Individualized Knowledge Graphs - Ping et al. (2017) PMID: 28360346


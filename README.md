Automated Detection of Cognitive Biomarkers in Clinical Text
Project Summary
This repository contains a computational framework for identifying linguistic indicators of cognitive health. The project bridges the gap between psycholinguistic theory and clinical diagnostics by automating the measurement of structural complexity in patient speech and writing.

Technical Methodology
1. Natural Language Processing (NLP)
The pipeline utilizes the spaCy library for deep linguistic parsing. Raw text samples are processed to identify part-of-speech (POS) tags and syntactic dependencies, moving beyond simple keyword matching to analyze the underlying structure of the discourse.

2. Feature Extraction
The model quantifies cognitive load through three primary metrics:

Lexical Diversity: Calculation of the Type-Token Ratio (TTR) to assess vocabulary breadth.

Morphological Analysis: Evaluation of mean word length as a proxy for lexical sophistication.

Syntactic Density: Measuring the ratio of content words (nouns/verbs) to functional words to determine informational weight.

3. Classification Architecture
Extracted features are fed into a Random Forest Classifier. This ensemble learning approach was chosen for its ability to handle high-dimensional linguistic data and provide insight into feature importance, which is critical for clinical interpretability.

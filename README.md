# JPPB
JPPB: A Japanese Patient Phrase Bank for symptom normalization, providing both hard-label and soft-label mappings between patient expressions and medical concepts.

JPPB (Japanese Patient Phrase Bank) is a phrase-level resource for normalizing patient-generated symptom expressions into standardized medical concepts.

Unlike traditional dictionaries that assume one-to-one mappings, JPPB captures the inherent ambiguity of patient language by providing both:

- HardLabel.csv: one-to-one mappings between expressions and canonical terms
- SoftLabel.csv: one-to-many mappings with probabilistic scores

This design enables ambiguity-aware normalization and supports robust medical NLP applications in Japanese.

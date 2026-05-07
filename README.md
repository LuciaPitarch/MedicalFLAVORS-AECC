# MedicalFLAVORS-AECC
Repository related to the paper "Medical-FLAVORS-AECC: Spanish oncological metaphors dataset" accepted at CL4H@LREC 2026.

Abstract: Metaphors play a central role in cancer narratives, helping patients and practitioners articulate complex experiences and technical concepts. While cancer metaphors in English have been extensively studied, Spanish remains underexplored in this regard, despite its global importance and rich cultural variation. This paper presents a new dataset of Spanish cancer metaphors designed to address these gaps. The resource comprises 74 annotated instances drawn from diverse forum posts, with detailed documentation of lexical units, contextual versus basic meanings, and inter-annotator agreements. To construct the dataset, we adapted the Metaphor Identification Procedure (MIP) for Spanish medical discourse, proposing methodological refinements to challenges such as defining lexical units or domain-specific Basic Meaning labels.

The repository contains:
- Original annotation guidelines (in Spanish). The summarized English version can be found in the paper.
- Sample of the annotated dataset (three posts), with the labels proposed by two independent annotators.
- Curated uniword vocabulary of metaphor vehicles with Basic, Contextual Meaning, and, Target Domain annotations. (Note: Lemmatization was done using Spacy's 'es_core_news_md'.
- Curated multiword vocabulary. If found in the Dictionary or in SketchEngine the source is provided. (Note: some overlap --Around 100 entries-- exists with uniword vocab, given some uniword might also appear in Frame or Semantic Role constructions).
- Additional lists of Multiword Expressions related to cancer (light verb and modal verb constructions).
   

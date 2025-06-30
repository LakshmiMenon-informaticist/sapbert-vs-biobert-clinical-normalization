# sapbert-vs-biobert-clinical-normalization
Comparing SapBERT and BioBERT for clinical term normalization to SNOMED CT using cosine similarity and terminology mapping accuracy.
# SapBERT vs. BioBERT for Clinical Terminology Normalization

This project evaluates two state-of-the-art biomedical language models — **SapBERT** and **BioBERT** — on their ability to normalize ambiguous clinical inputs to standardized SNOMED CT concepts.

## 🧠 Background

Standardized clinical vocabularies like **SNOMED CT** are essential for:
- Interoperability in healthcare systems
- Accurate decision support
- Cohort identification and data analytics

However, clinical text often includes misspellings, abbreviations, and unstructured phrases. This project tackles the normalization challenge using language model-based semantic similarity.

## 🔍 Objective

Compare **SapBERT** and **BioBERT** in mapping ambiguous clinical terms to the correct SNOMED CT concepts using:
- Cosine similarity of embeddings
- Exact match accuracy

## 🛠️ Tools & Libraries

- **Hugging Face Transformers**
- **scikit-learn** (cosine similarity)
- **Pandas** and **Matplotlib**
- **Google Colab** (runtime)

## 📁 Files

- `fuzzy_terms.csv`: List of ambiguous clinical input terms
- `snomed_subset.csv`: Reference SNOMED CT concepts (code + name)
- `bert_fuzzy_matching_results.csv`: Results with match outcomes and similarity scores

## 📈 Key Results

- **SapBERT** achieved more accurate matches to correct concepts.
- **BioBERT** had higher average similarity but missed semantic precision.

> Semantic similarity is not the same as terminological correctness.

## 📊 Visualizations

- Accuracy bar chart by model
- Term-wise similarity scatterplot


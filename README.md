# Mimamsa Transformer Experiments

This repository contains the paper, experiment notebook, and datasets for a project on Mīmāṃsā philosophy of language and transformer architectures.

The accompanying paper, *Connected Denotation and Contextual Representation: Prābhākara Sentence Semantics as Empirical Hypothesis in Transformer Architectures*, studies whether the classical Mīmāṃsā debate between anvitābhidhāna and abhihitānvaya can be placed in productive dialogue with modern transformer models. The central claim is that the Mīmāṃsā conditions of ākāṅkṣā, yogyatā, and sannidhi can be mapped onto distinguishable aspects of transformer computation and used to generate testable empirical hypotheses.

Using BERT, GPT-2, and LLaMA 3.1 8B, the project examines four questions: syntactic expectancy, semantic fitness, contiguity, and polysemy. Across these studies, the results support a contextual and relational account of meaning more strongly than a strictly sequential model in which words first carry independent meaning and only later combine.

## Repository Structure

### Paper
- `paper/Connected_Denotation_Final_Draft.pdf`

### Notebook
- `notebook/mimamsa_transformer_experiments_v5.ipynb`
- `notebook/mimamsa_notebook_colab.pdf`

### Data
- `data/passages_merged_0_312.jsonl`
- `data/sannidhi_1000_token_dataset.jsonl`
- `data/yogyata_minpairs_llama3_final.jsonl`
- `data/polysemy_templates_final_balanced.csv`

## Studies

### Study 1: Ākāṅkṣā
Tests whether obligatory syntactic dependencies are preferentially tracked in attention and whether those relations are causally robust under arc knockout.

### Study 2: Yogyatā
Examines semantic fitness through minimal pairs and activation patching to identify where compatible and incompatible continuations are distinguished.

### Study 3: Sannidhi
Measures how attention and retrieval degrade with distance, treating contiguity as both an architectural boundary and a graded empirical effect.

### Study 4: Polysemy
Tracks how BERT representations shift from lexical identity toward contextual sense across layers in order to test competing predictions about meaning constitution.

## Models
- BERT-base-uncased
- GPT-2
- LLaMA 3.1 8B

## Files in This Repository
The notebook contains the full experimental pipeline, and the datasets provide the inputs used across the four studies. The PDF notebook is included as a static readable version of the computational workflow.
The `paper/` directory contains the research paper.

## License
The notebook and repository materials are released under the MIT License.

The datasets in the `data/` directory are provided for research and scholarly use. 

## Citation
If this repository is used in research, please cite the associated paper.

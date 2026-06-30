# Rethinking Value Identification as Annotation Agreement: Evaluating LLMs as Human-like Value Annotators

## Overview

This repository contains the code accompanying the paper:

**"Rethinking Value Identification as Annotation Agreement: Evaluating LLMs as Human-like Value Annotators"**

accepted at the **[Fourth International Workshop on Value Engineering in AI (VALE 2026)](https://vale2026.iiia.csic.es/)**, affiliated with **[IJCAI-ECAI 2026](https://2026.ijcai.org/)**.

The project investigates whether Large Language Models (LLMs) behave similarly to human annotators in the task of value-based argument analysis. Rather than focusing solely on classification performance, this work evaluates agreement structures, label distributions and interpretative biases between LLM-generated annotations and human annotations.

---

## Repository Structure

* `requirements.txt`
  List of dependencies required to run the notebooks.

* `experimental_code.ipynb`
  Main notebook for: dataset processing and LLM-based annotation generation

* `evaluations.ipynb`
  Notebook for: evaluation of agreement with human annotations, generating plots and figures, computing aggregate metrics and performing qualitative and quantitative analysis

---

## Dataset

This work uses the **Webis-ArgValues-22** dataset:

https://zenodo.org/records/6855004

Originally introduced in [Identifying the Human Values Behind Arguments](https://aclanthology.org/2022.acl-long.306/) (Kiesel et al., ACL 2022).

The dataset contains over 5,000 arguments annotated with **54 fine-grained human values**, organized within a hierarchical taxonomy. In this project, we focus on the USA test split.

Please refer to the original dataset publication for annotation guidelines and licensing details.

---

## Setup

Clone the repository and install dependencies:

```bash
pip install -r requirements.txt
```

---


## License

This repository is released under the **MIT License**.

Note: The dataset used in this project is subject to its own licensing terms. Please consult the original dataset source for details.

---

## Citation

If you use this code or build upon this work, please cite the paper as follows:

```bibtex
@inproceedings{pending2026value_annotation,
  title={Rethinking Value Identification as Annotation Agreement: Evaluating LLMs as Human-like Value Annotators},
  author={Gutiérrez-Mandingorra, Ana and Benlloch-Blasco, Isabel and Botti, Vicente and Heras, Stella and Palanca, Javier},
  booktitle={Proceedings of the Fourth International Workshop on Value Engineering in AI (VALE 2026)},
  year={2026},
  note={Pending publication}
}
```

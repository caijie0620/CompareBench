# CompareBench

**Project Page:**
- [CompareBench Project Page](https://caijie0620.github.io/CompareBench/) — overview, method, results, and dataset links

---

CompareBench is a benchmark for evaluating **visual comparison reasoning** in vision-language models (VLMs), covering four tasks: quantity, temporal, geometric, and spatial. The benchmark contains 1,200 A-D multiple-choice QA pairs across four sub-benchmarks:

- CompareTallyBench: 600 quantity-comparison questions
- CompareGeometryBench: 200 geometric-comparison questions
- CompareSpatialBench: 100 spatial-comparison questions
- CompareTemporalBench: 300 temporal-comparison questions

The release is organized with two supporting resources:

- [TallyBench (2,000 counting images with QA)](https://huggingface.co/datasets/qiuzhangTiTi/TallyBench)  
- [OmniCaps (516 historical images + 100 celebrity images + 100 landmark images)](https://huggingface.co/datasets/qiuzhangTiTi/OmniCaps)  

TallyBench supports the quantity split, OmniCaps supports the temporal split, and the geometry/spatial splits use dedicated A-D annotations.

The benchmark dataset is available here:  
- [CompareBench (1,200 QA pairs)](https://huggingface.co/datasets/qiuzhangTiTi/CompareBench)

---

## Contents

- `prompts.yaml`: Standardized instruction templates for TallyBench and all four CompareBench sub-benchmarks.
- Benchmark datasets (links above).
- Project page source (`index.html`).

---

📌 Paper: *CompareBench: A Benchmark for Visual Comparison Reasoning in Vision–Language Models* (ACCV 2026 submission)  
📂 Project page and prompts are maintained in this repository; benchmark datasets are hosted on Hugging Face.

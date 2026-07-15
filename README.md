# Awesome Legal Tasks

A curated list of open-source legal NLP tasks and benchmarks.

Part of the [ACE-EXP](https://github.com/TAU-Express/ace-exp) legal-AI evaluation project.

## Contents

- [Tasks](#tasks)
- [Contributing](#contributing)
- [License](#license)

## Tasks

| Name | Task type | Dataset(s) | Metric | Source |
|---|---|---|---|---|
| LexGLUE | 7 English legal NLU tasks (classification + MCQ) | — | micro-F1 / macro-F1; accuracy | https://huggingface.co/datasets/coastalcph/lex_glue |
| LEXTREME | 11 datasets / 18 configs; classification + NER | — | Harmonic-mean aggregate; per-task F1 | https://huggingface.co/datasets/joelniklaus/lextreme |
| LegalBench | 162 tasks; 6 reasoning types (IRAC) | — | Task-specific accuracy / F1 / balanced acc | https://huggingface.co/datasets/nguha/legalbench |
| LawBench | 20 tasks; 3 cognitive tiers | — | Accuracy, F1, ROUGE | https://github.com/open-compass/LawBench |
| LAiW | 14 tasks; 3 ability levels (BIR/LFI/CLA) | — | Accuracy, F1, generation metrics | https://github.com/Dai-shen/LAiW |
| LexEval | 23 tasks; LexCog cognitive taxonomy (6 abilities) | — | Task-specific accuracy / F1 | https://huggingface.co/datasets/CSHaitao/LexEval |
| IL-TUR | 8 tasks (NER, rhetorical role, LJP, retrieval, summ, MT) | — | Task-specific (F1, ROUGE, IR) | https://huggingface.co/datasets/Exploration-Lab/IL-TUR |
| LBOX Open | Corpus + classification + LJP + summarization | — | Accuracy/F1, regression, ROUGE | https://huggingface.co/datasets/lbox/lbox_open |
| KBL | Knowledge (510) + reasoning (288) + bar exam (2,510) | — | Accuracy | https://github.com/lbox-kr/kbl |
| ArabLegalEval | Multitask QA / entailment / classification | — | Accuracy, F1 | https://aclanthology.org/2024.arabicnlp-1.20/ |
| LegalAgentBench | 300 agent tasks; 17 corpora; 37 tools; multi-hop | — | Task success rate + progress rate | https://github.com/CSHaitao/LegalAgentBench |
| LexSumm / LexT5 | 8 English legal summarization datasets | — | ROUGE + abstraction/faithfulness error taxonomy | https://github.com/TUMLegalTech/LexSumm-LexT5 |
| MLEB | 10 datasets; retrieval + zero-shot classification + QA | — | nDCG@k, Recall@k, MRR | https://github.com/isaacus-dev/mleb |
| TW-LegalBench | MCQ across 6 legal domains | — | Accuracy | https://huggingface.co/datasets/lianghsun/tw-legal-benchmark-v1 |


## Sources & Acknowledgments

Entries in this list were seeded in part from:

- [maastrichtlawtech/awesome-legal-nlp](https://github.com/maastrichtlawtech/awesome-legal-nlp)
- [CSHaitao/Awesome-LegalAI-Resources](https://github.com/CSHaitao/Awesome-LegalAI-Resources)
- [thunlp/LegalPapers](https://github.com/thunlp/LegalPapers)
- [Jeryi-Sun/LLM-and-Law](https://github.com/Jeryi-Sun/LLM-and-Law)
- [ZhitianHou/LLMs4LegalAI](https://github.com/ZhitianHou/LLMs4LegalAI)
- [czyssrs/LLM_X_papers](https://github.com/czyssrs/LLM_X_papers)
- [Liquid-Legal-Institute/Legal-Text-Analytics](https://github.com/Liquid-Legal-Institute/Legal-Text-Analytics)
- [openlegaldata/awesome-legal-data](https://github.com/openlegaldata/awesome-legal-data)
- [hecongqing/Awesome-LLM4Law](https://github.com/hecongqing/Awesome-LLM4Law)
- [chen-friedman/awesome-legaltech](https://github.com/chen-friedman/awesome-legaltech)
- [dalinvip/Awesome-Law-NLP-Research-Work](https://github.com/dalinvip/Awesome-Law-NLP-Research-Work)

## Contributing

PRs welcome. Each entry must link back to its backing dataset(s) in [awesome-legal-datasets](https://github.com/TAU-Express/awesome-legal-datasets) where applicable.

## License

This list (the curation itself) is released under [CC0](https://creativecommons.org/publicdomain/zero/1.0/).

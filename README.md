<p align="center">
  <img heith=350 width=350 src="https://github.com/DavideNapolitano/QG_ITA/blob/main/images/QA.png">
</p>


# QG_ITA
Question Generator for the Italian Language.

## Description
Develop a Question Generation model for customers surveys.

## Related Works
Today, in the SOTA, the focus is placed mainly on the Question Answering task. As a consequence, few researches have been conducted during the latest years.
For this reason, I collect existing models and approaches available for Question Generation and, in addition, I place some focus on Question Answering models based on LLMs. 
Indeed, LLMs QA models are already capable of providing some questions during the conversations, making them suitable for some analysis and research for the QG task.


### Existing models and papers for QG
- https://huggingface.co/iarfmoose/t5-base-question-generator - https://github.com/AMontgomerie/question_generator
- https://github.com/microsoft/unilm/tree/master/unilm
- https://huggingface.co/voidful/context-only-question-generator
- https://cs230.stanford.edu/projects_fall_2020/reports/55771015.pdf
- https://www.questgen.ai/
- https://github.com/ramsrigouthamg/Questgen.ai
- https://github.com/KristiyanVachev/Question-Generation
- https://gpt-index.readthedocs.io/en/latest/examples/evaluation/QuestionGeneration.html
- https://amontgomerie.github.io/2020/07/30/question-generator.html
- https://arxiv.org/pdf/1909.05017.pdf
- https://telrp.springeropen.com/articles/10.1186/s41039-021-00151-1

### Question Answering
- https://huggingface.co/docs/transformers/main/tasks/question_answering
- https://github.com/stevezheng23/xlnet_extension_tf
- https://github.com/openai/openai-cookbook/tree/main/examples
- https://medium.com/@murtuza753/using-llama-2-0-faiss-and-langchain-for-question-answering-on-your-own-data-682241488476
- https://deci.ai/blog/fine-tune-llama-2-with-lora-for-question-answering/

### Other
- https://arxiv.org/pdf/2307.07164.pdf
- https://arxiv.org/pdf/2306.04508v1.pdf
- https://betterprogramming.pub/building-context-aware-question-answering-systems-with-llms-b6f2b6e387ec
- https://www.linkedin.com/pulse/multi-hop-question-answering-llms-knowledge-graphs-wisecube/
- https://www.wisecube.ai/blog/combining-large-language-models-and-knowledge-graphs/
- https://arxiv.org/abs/2309.00841
- https://github.com/artitw/text2text
- https://github.com/Karthick47v2/question-generator
- https://github.com/huggingface/transformers/issues/4399


## Datasets
Today, all the existing datasets are for the QA task. However, this is not an issue since the two elements can be inverted to be suitable for QG: Q->A <-> A->Q.
Following, I collect existing Italian and Multi-lingual QA datasets. Moreover, I also collect some datasets on Survey and Conversations, since related to our project, by taking into consideration that some additional steps will be required since all of them are in the English language.

### QA Dataset
- SQUaD-IT: https://huggingface.co/datasets/squad_it - http://sag.art.uniroma2.it/demo-software/squadit/
- mMARCO: https://github.com/unicamp-dl/mMARCO
- BELEBELE: https://huggingface.co/datasets/facebook/belebele
- Mintaka: https://github.com/amazon-science/mintaka
- MultiQA: https://github.com/sebastianruder/emnlp2021-multiqa-tutorial
- XTreme: https://huggingface.co/datasets/xtreme
- XCopa: https://huggingface.co/datasets/xcopa
- mFAQ: https://huggingface.co/datasets/clips/mfaq
- https://paperswithcode.com/datasets?task=question-answering&lang=italian&page=1

Summary: https://nlpprogress.com/english/question_answering.html

Collection: 
- https://parl.ai/docs/tasks.html#qa-tasks
- https://nlpprogress.com/english/question_answering.html
- https://arxiv.org/abs/2206.15030

### Survey:
- https://www.pewresearch.org/internet/datasets/
- https://datacatalog.worldbank.org/search/dataset/0037947/Enterprise-Surveys
- https://mics.unicef.org/surveys

### Conversational:
- https://arxiv.org/abs/2205.06907
- http://aclanthology.lst.uni-saarland.de/W19-4101.pdf
- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10280565/
- https://dl.acm.org/doi/abs/10.1145/3539618.3591883

## Metrics
Here some metrics are collected. They are commonly used for QA and text matching.

- https://arxiv.org/pdf/2211.01482.pdf
- ROUGE-L, BLEU, METEOR, Sentence Mover's Similarity, BERTScore

## Others
Addition material about LLMs for the QA task.

DeepMind presentation: https://docs.google.com/presentation/d/1cML2FBrevPF0BtQu5QH_BL3dUbfn0egYyhTbOgwqlbA/edit?ref=ruder.io#slide=id.p1

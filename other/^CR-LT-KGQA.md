# CR-LT-KGQA

**CR-LT-KGQA**<sup>[[1]](#myfootnote1)</sup> is a Knowledge Graph Query Answering dataset with Natural Language queries targeted on long-tail Wikidata entities, answering which requires commonsense reasoning and is submitted to SIGIR'24. The dataset contains two subsets targetting two different tasks: (i) Question Answering subset containing 200 questions based on StrategyQA dataset and (ii) Claim Verification subset containing 150 claims based on Creak dataset.

The format of the dataset is in JSON, where each entry contains a query (a question or a claim), the answer, anchor KG entities mentioned in the query and their respective Wikidata QID, an inference rule, relevant KG triples, reasoning steps and the relevant KG triples to each step, and finally the set of reasoning skills and strategies required to answer the query.
 

## References
<a name="myfootnote1">[1]</a> Guo, Willis and Toroghi, Armin and Sanner, Scott. [CR-LT-KGQA: A Knowledge Graph Question Answering Dataset Requiring Commonsense Reasoning and Long-Tail Knowledge](https://arxiv.org/pdf/2403.01395) arXiv preprint arXiv:2403.01395. 2024.

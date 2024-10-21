# Comparing Template-based and Template-free Language Model Probing 

## Paper 

* Comparing Template-based and Template-free Language Model Probing 

## Code 

Code will be added soon! Stay tuned. 

## LIPID Dataset 

In the meantime, we provide the LIPID dataset (tempLate-free bIomedical ProbIng Dataset), a collection of 88,666 template-free prompts from PubMed abstracts. 

The dataset is split into two portions: chemicals and genes. 

* Chemicals: 46,827 chemical-related prompts and 1870 unique chemical entities 

* Genes: 41,839 gene-related prompts and 2591 unique gene entities

If you use the data or paper in your work please cite us:

@inproceedings{shaier-etal-2024-comparing,
    title = "Comparing Template-based and Template-free Language Model Probing",
    author = "Shaier, Sagi  and
      Bennett, Kevin  and
      Hunter, Lawrence  and
      von der Wense, Katharina",
    editor = "Graham, Yvette  and
      Purver, Matthew",
    booktitle = "Proceedings of the 18th Conference of the European Chapter of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = mar,
    year = "2024",
    address = "St. Julian{'}s, Malta",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.eacl-long.46",
    pages = "766--776",
    abstract = "The differences between cloze-task language model (LM) probing with 1) expert-made templates and 2) naturally-occurring text have often been overlooked. Here, we evaluate 16 different LMs on 10 probing English datasets {--} 4 template-based and 6 template-free {--} in general and biomedical domains to answer the following research questions: (RQ1) Do model rankings differ between the two approaches? (RQ2) Do models{'} absolute scores differ between the two approaches? (RQ3) Do the answers to RQ1 and RQ2 differ between general and domain-specific models? Our findings are: 1) Template-free and template-based approaches often rank models differently, except for the top domain- specific models. 2) Scores decrease by up to 42{\%} Acc@1 when comparing parallel template-free and template-based prompts. 3) Perplexity is negatively correlated with accuracy in the template-free approach, but, counter-intuitively, they are positively correlated for template-based probing. 4) Models tend to predict the same answers frequently across prompts for template-based probing, which is less common when employing template-free techniques.",
}
# Neural Mining of Persian Short Argumentative Texts
First Persian (Farsi) Short Argumentative Text Coprus 
## About
This repository contains "Persian argumentative microtext corpus" (PAMT) and the code related to the paper "Neural Mining of Persian Short Argumentative Texts" (M.Yeghaneh Abkenar, M.Stede). Here is the link to the original corpus in German and English:
https://github.com/peldszus/arg-microtexts.

If you are using our corpus for research purposes, please cite the following paper:


# Argumentation mining in Persian
Argumentation mining (AM) is concerned with extracting arguments from texts and classifying the elements (e.g.,
claim and premise) and relations between them, as well as creating an argumentative structure. A significant
hurdle to research in this area for the Persian language is the lack of annotated corpora. This paper introduces the
first argument-annotated corpus in Persian and thereby the possibility of expanding argumentation mining to this
language. The starting point is the English argumentative microtext corpus part 1 (AMT) (Peldszus and Stede, 2015),
and we built the Persian variant by machine translation and careful post-editing of the output. We call this corpus
Persian argumentative microtext (PAMT). Moreover, we present the first results for Argumentative Discourse Unit
(ADU) classification for Persian, which is considered to be one of the main subtasks of argumentation mining. We
determine the ADUs and their types (claim vs. premise) by two methods: (i) span categorization using the deep
learning model of spaCy Version 3.0 (a CNN model on top of Bloom embedding with attention), and (ii) a neural
sequence tagger. The results that we obtain with the second approach are comparable to those achieved on the
same subtask in AMT and its other translations


In case you use the PAMT, Please cite this paper. 
```
@inproceedings{abkenar2024neural,
  title={Neural Mining of Persian Short Argumentative Texts},
  author={Abkenar, Mohammad Yeghaneh and Stede, Manfred},
  booktitle={Proceedings of the 2nd Workshop on Resources and Technologies for Indigenous, Endangered and Lesser-resourced Languages in Eurasia (EURALI)@ LREC-COLING 2024},
  pages={30--35},
  year={2024}
}

```

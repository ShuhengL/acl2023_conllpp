# Datasets

## Details of the Datasets
Here we upload three datasets used in our paper.

```conllpp.txt``` is the CoNLL++ dataset that we annotated following the CoNLL-2003 NER task ([Tjong Kim Sang and De Meulder, 2003](https://aclanthology.org/W03-0419/)). As the each line in the original CoNLL-2003 dataset is in the format of ```{word} {POS} {Chunk} {NER}``` and many models developing on this dataset process these files assuming this format, we have the word start and end indices in place of the POS and chunk tags.

```conll_prime/``` includes our CoNLL-2003' dataset, compiling and respliting the CoNLL-2003 dataset into the new train (```eng.train```), dev (```eng.testa```) and test (```eng.testb```) sets.

```non_tabular_conll/``` includes the same CoNLL-2003 train (```eng.train```) and dev (```eng.testa```) sets, but a new test set (```eng.testb```) which we manually removed the tabular data included in the original CoNLL-2003 test set.

## Annotation Guidelines

We also include the annotation guidelines
```annotation_guidelines```  we used to annotate the CoNLL++ dataset. This is a modified list of guidelines from the [CoNLL-2003 shared task](https://www.clips.uantwerpen.be/conll2003/ner/annotation.txt), with a few added categories under each tag.
# T100-PAN2022
This repo contains data and code for our submission to the PAN@CLEF2022 task on Irony and Stereotype Spreaders Detection. 
For a detailed description of our model, please see the paper "T100: A modern classic ensemble to profile irony and stereotype spreaders" by M.Siino et al.

## Task Description 
"With irony, language is employed in a figurative and subtle way to mean the opposite to what is literally stated. In case of sarcasm, a more aggressive type of irony, the intent is to mock or scorn a victim without excluding the possibility to hurt. Stereotypes are often used, especially in discussions about controversial issues such as immigration or sexism and misogyny. At PAN’22, we will focus on profiling ironic authors in Twitter. Special emphasis will be given to those authors that employ irony to spread stereotypes, for instance, towards women or the LGTB community. The goal will be to classify authors as ironic or not depending on their number of tweets with ironic content. Among those authors we will consider a subset that employs irony to convey stereotypes in order to investigate if state-of-the-art models are able to distinguish also these cases. Therefore, given authors of Twitter together with their tweets, the goal will be to profile those authors that can be considered as ironic. "

## Code
The following code can be executed on Google Colab.

* T100_SVM_LR_ISS2022_MLC_CrossPredictions_ModelNB.ipynb

## BIBTEX
@inproceedings{siino2022T100,
  title={T100: A modern classic ensemble to profile irony and stereotype spreaders},
  author={Siino, Marco and Ilenia, Tinnirello and La Cascia, Marco},
  booktitle={CEUR Workshop Proceedings},
  volume={3180},
  pages={2666-2674},
  year={2022},
  organization={CEUR}
}

## Useful Links
* [Description paper](http://ceur-ws.org/Vol-3180/paper-221.pdf)
* [Official website](https://pan.webis.de/clef22/pan22-web/author-profiling.html) of the task

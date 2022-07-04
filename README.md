# NLP-for-Telugu-Language

In this github repo, the code for each of research papers are placed as zip folders.

we crawled our corpus of 63,78,180 sentences. Besides, we added the available Telugu Wikipedia dump of 16,37,408 sentences (at the time we created the corpus). The total Telugu corpus has 80,15,588 sentences. The Telugu corpus (this we converted to wx notation for our experimental use), can be downloaded from the below link:
https://iiitaphyd-my.sharepoint.com/:t:/g/personal/mounika_marreddy_research_iiit_ac_in/EXCQvtPr0XRJoj6YW7Ue-tIBB29bltzCLxBRCyPD4CwvQQ?e=Zlbp8k


If anyone want train/test/validation split of the datasets that I mentioned in my papers, please refer the below hugging face link:
https://huggingface.co/mounikaiiith
The hugging face link consists of five different Telugu datasets.
1. Telugu sentiment dataset - The dataset contains 34,142 sentences. We considered three labels as "positive", "negative", and "neutral". The data is divided as 70%-training, 20%-testing, 10%-validation split.
2. Telugu emotion dataset - The dataset contains 34,142 sentences. We considered five basic labels as "happy", "sad", "anger", "fear", and "no emotion". The data is divided as 70%-training, 20%-testing, 10%-validation split.
3. Telugu hatespeech dataset - The dataset contains 34,142 sentences. We considered two labels as as "yes" and "no". The data is divided as 70%-training, 20%-testing, 10%-validation split.
4. Telugu sarcasm dataset - The dataset contains 34,142 sentences. We considered two labels as as "yes" and "no". The data is divided as 70%-training, 20%-testing, 10%-validation split.
5. Telugu clickbait dataset - The dataset contains 112,657 headline sentences. We considered two labels as "yes" and "no". The data is divided as 70%-training, 20%-testing, 10%-validation split.

If anyone want to use the pretrained feature representations that we developed from scratch on Telugu language, please refer the below hugging face links:

https://huggingface.co/ltrctelugu

https://huggingface.co/subbareddyiiit - the Telugu models are named with prefix "Te".


# citations for using the datasets

For using the three class sentiment, five class emotion, sarcasm, and hatespeech Telugu datasets, do cite the below journal

@article{marreddy2022resource,
  title={Am I a Resource-Poor Language? Data Sets, Embeddings, Models and Analysis for four different NLP tasks in Telugu Language},
  author={Marreddy, Mounika and Oota, Subba Reddy and Vakada, Lakshmi Sireesha and Chinni, Venkata Charan and Mamidi, Radhika},
  journal={Transactions on Asian and Low-Resource Language Information Processing},
  publisher={ACM New York, NY}
}

For using the clickbait Telugu dataset, do cite the below paper

@inproceedings{marreddy2021clickbait,
  title={Clickbait Detection in Telugu: Overcoming NLP Challenges in Resource-Poor Languages using Benchmarked Techniques},
  author={Marreddy, Mounika and Oota, Subba Reddy and Vakada, Lakshmi Sireesha and Chinni, Venkata Charan and Mamidi, Radhika},
  booktitle={2021 International Joint Conference on Neural Networks (IJCNN)},
  pages={1--8},
  year={2021},
  organization={IEEE}
}

For using the two class sentiment, four class emotion, sarcasm, and hatespeech Telugu datasets, do cite the below paper

@article{marreddy2022multi,
  title={Multi-Task Text Classification using Graph Convolutional Networks for Large-Scale Low Resource Language},
  author={Marreddy, Mounika and Oota, Subba Reddy and Vakada, Lakshmi Sireesha and Chinni, Venkata Charan and Mamidi, Radhika},
  journal={arXiv preprint arXiv:2205.01204},
  year={2022}
}

# citations for using the Telug pretrained embeddings.
@article{marreddy2022resource,
  title={Am I a Resource-Poor Language? Data Sets, Embeddings, Models and Analysis for four different NLP tasks in Telugu Language},
  author={Marreddy, Mounika and Oota, Subba Reddy and Vakada, Lakshmi Sireesha and Chinni, Venkata Charan and Mamidi, Radhika},
  journal={Transactions on Asian and Low-Resource Language Information Processing},
  publisher={ACM New York, NY}
}

For using the clickbait Telugu dataset, do cite the below paper
@inproceedings{marreddy2021clickbait,
  title={Clickbait Detection in Telugu: Overcoming NLP Challenges in Resource-Poor Languages using Benchmarked Techniques},
  author={Marreddy, Mounika and Oota, Subba Reddy and Vakada, Lakshmi Sireesha and Chinni, Venkata Charan and Mamidi, Radhika},
  booktitle={2021 International Joint Conference on Neural Networks (IJCNN)},
  pages={1--8},
  year={2021},
  organization={IEEE}
}




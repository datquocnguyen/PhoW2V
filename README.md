# PhoW2V: Pre-trained Word2Vec syllable and word embeddings for Vietnamese

PhoW2V provides collections of pre-trained Word2Vec syllable- and word-level embeddings for Vietnamese, that were pre-trained on a 20GB corpus of Vietnamese texts and used for our EMNLP-2020 Findings work ["A Pilot Study of Text-to-SQL Semantic Parsing for Vietnamese"](https://www.aclweb.org/anthology/2020.findings-emnlp.364/): 

	@inproceedings{phow2v_vitext2sql,
	    title     	= {{A Pilot Study of Text-to-SQL Semantic Parsing for Vietnamese}},
	    author    	= {Anh Tuan Nguyen and Mai Hoang Dao and Dat Quoc Nguyen},
	    booktitle   = {Findings of the Association for Computational Linguistics: EMNLP 2020},
	    year      	= {2020},
	    pages       = {4079--4085}
	}  

|Pre-trained embeddings| Syllable/Word | Embedding size | Download mirror |
|--|--|--|--|
| [PhoW2V_syllables_100dims](https://public.vinai.io/word2vec_vi_syllables_100dims.zip) | Syllable-level | 100 | [Mirror](https://drive.google.com/drive/folders/1NZhZFYbcwKzLpvvGdJUdPbwEVdVW4E3j?usp=drive_link) |
| [PhoW2V_syllables_300dims](https://public.vinai.io/word2vec_vi_syllables_300dims.zip) | Syllable-level | 300 | [Mirror](https://drive.google.com/drive/folders/1NZhZFYbcwKzLpvvGdJUdPbwEVdVW4E3j?usp=drive_link) |
| [PhoW2V_words_100dims](https://public.vinai.io/word2vec_vi_words_100dims.zip) | Word-level | 100 | [Mirror](https://drive.google.com/drive/folders/1NZhZFYbcwKzLpvvGdJUdPbwEVdVW4E3j?usp=drive_link) |
| [PhoW2V_words_300dims](https://public.vinai.io/word2vec_vi_words_300dims.zip) | Word-level | 300 | [Mirror](https://drive.google.com/drive/folders/1NZhZFYbcwKzLpvvGdJUdPbwEVdVW4E3j?usp=drive_link) |


By downloading the PhoW2V embeddings, USER agrees:

- To use PhoW2V for research or educational purposes only.
- Not to distribute PhoW2V or part of PhoW2V in any original or modified form.
- To cite our EMNLP-2020 Findings paper above when PhoW2V is employed to help produce published results.


#### Note
- Users should perform Vietnamese tone normalization on downstream tasks' data as this pre-process was also applied to the 20GB pre-training corpus of Vietnamese texts. A Python script for Vietnamese tone normalization is available at [HERE](https://github.com/VinAIResearch/BARTpho/blob/main/VietnameseToneNormalization.md).



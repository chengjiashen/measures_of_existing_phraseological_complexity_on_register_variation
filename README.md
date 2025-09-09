This repository contains the Python scripts used in Study I. The aim of Study I is to investigate the extent to which existing measures of phraseological complexity (e.g., Paquot, 2019) can be applied within the framework of register variation.

types_tokens_ratios.py: This script extracts word combinations based on amod, advmod, and dobj grammatical relations from texts belonging to two expert registers: editorials and research journals. It further employs a moving-window approach (e.g., Vandeweerd et al., 2023), using windows of 300 words with increments of 10 words, to reduce potential biases arising from differences in text length. The script outputs summary statistics of the averaged types, tokens, and type–token ratios across moving windows for each individual text.

txt_split.py: This scrip splits the txt files into manageable subfiles that can be easily processed with spaCy. The splitted txt files are approximately 500kb large.

refernce_corpora_processing: This script extracts lemmas and two-word occurrences of amod, advmod, and dobj dependency relationships from any reference corpora.

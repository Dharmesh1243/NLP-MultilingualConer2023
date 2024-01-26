# NLP-MultilingualConer2023
Named entity recognition(NER) is a sub-task in
the field of NLP(Natural Language Processing). To be more
specific NER is the text classification task in which a piece of
the text is classified as their corresponding categories(person
names, organisation names, etc). Basically, it involves two core
tasks: tokenizing and labelling a piece of the information
written in the human-readable languages. This field poses some
challenges when it comes to recognizing the entities in different
domains, for example, medical or creative names with more
than one language. In this paper, we are representing our
robust
and high performance achieving ensemble
Multilingual-NER system using RemBERT, mBERT,
xlm-r(base version) transformer based multilingual models for
12 languages( total 36 base models), and to improve the quality
of the predictions, we used weighted mean ensemble method
for probabilities. In this paper, we present our
Multilingual-NER system trained on the MultiCoNER-II
database which consists of 12 different languages with complex
named entities in various domains such as CW(creative works,
group, location, medical, person, and product)[1]. Moreover, to
evaluate our ensemble Multilingual-NER system, we used
evaluation metrics such as precision, recall, and f1 scores,
micro-f1 scores.

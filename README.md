# NLP Deliverable
This repository contains the code and resources of the NLP deliverable of the course on Intelligent Systems at Escuela Técnica Superior de Ingenieros Informáticos (Universidad Politécnica de Madrid). The objectives of the work are to analyze the patterns in sarcastic and non-sarcastic Reddit comments and to build models to classify them. 

# Contents
- **Code.** The deliverable was developed in R. The repository contains the R notebook `NLPsarcasm.Rmd` with all the analyses.
- **Data.** The dataset contains over 1 million Reddit comments divided in sarcastic and non-sarcastic. Sarcasm was identified and labeled after the tag `\s`, often used by Reddit users to indicate that their post is sarcastic. The authors of the dataset are Mikhail Khodak, Nikunj Saunshi and Kiran Vodrahalli for their article [*A Large Self-Annotated Corpus for Sarcasm*](https://arxiv.org/abs/1704.05579) and can be found [here](https://nlp.cs.princeton.edu/SARC/0.0/). I have used the file `main/train-balanced.csv` for all the work. In this repository, it is located at `input/train-balanced-sarcasm.csv`.

# Instructions to run the code
As the source code is an `.Rmd` file, you just need to download (or clone) the repository and run each chunk of code in the notebook. I have used RStudio for that, but any other environment that supports R Markdown should work. The dependencies needed are:
- tidyverse
- utf8
- spacyr
- wordcloud
- RColorBrewer
- tm
- quanteda
- quanteda.textplots
- quanteda.textmodels
- caret

# Acknowledgements
~~~
@unpublished{SARC,
  authors={Mikhail Khodak and Nikunj Saunshi and Kiran Vodrahalli},
  title={A Large Self-Annotated Corpus for Sarcasm},
  url={https://arxiv.org/abs/1704.05579},
  year=2017
}
~~~

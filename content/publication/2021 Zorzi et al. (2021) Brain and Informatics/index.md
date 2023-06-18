---
# author_notes:
# - Equal contribution
# - Equal contribution
authors:
- Marco Zorzi
- Michele de Filippo de Grazia
- admin
- Alberto Testolin
date: "2021-01-01"
doi: "10.1007/978-3-030-86993-9_20"
featured: false
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false
projects: [FCnet]
publication: 'In *Brain Informatics: 14th International Conference, BI 2021*, Virtual Event, September 17–19, 2021, Proceedings 14 (pp. 211-222). Springer International Publishing.'
publication_short: ""
publication_types:
- "1"
publishDate: "2021"
#slides: example
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus
#   ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.
tags: 
- stroke
- structural connectome
- disconnections
- machine learning
- feature extraction
- dimensionality reduction
- predictive modeling
- FCnet
title: "Assessment of machine learning pipelines for prediction of behavioral deficits from brain disconnectomes"
#url_code: https://www.frontiersin.org/articles/10.3389/fpsyg.2013.00190/full
#url_dataset: ""
url_pdf: uploads/papers/2021 Zorzi et al. (2021) Brain and Informatics.pdf
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---

Recent studies have shown that brain lesions following stroke can be probabilistically mapped onto disconnections of white matter tracts, and that the resulting “disconnectome” is predictive of the patient’s behavioral deficits. Disconnectome maps are sparse, high-dimensional 3D matrices that require unsupervised dimensionality reduction followed by supervised learning for prediction of the associated behavioral data. However, the optimal machine learning pipeline for disconnectome data still needs to be identified. We examined four dimensionality reduction methods at varying levels of compression and used the extracted features as input for cross-validated regularized regression to predict the associated language and motor deficits. Features extracted by Principal Component Analysis and Non-Negative Matrix Factorization were found to be the best predictors, followed by Independent Component Analysis and Dictionary Learning. Optimizing the number of extracted features improved predictive accuracy and greatly reduced model complexity. Moreover, the choice of dimensionality reduction technique was found to optimally combine with a specific type of regularized regression (ridge vs. LASSO). Overall, our findings represent an important step towards an optimal pipeline that yields high prediction accuracy with a small number of features, which can also improve model interpretability.
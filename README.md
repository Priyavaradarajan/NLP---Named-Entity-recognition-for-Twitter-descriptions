# NLP-Named-Entity-recognition-for-Twitter-descriptions

Interested in the subject of Named Entity Recognition, this study deals with the descriptions of Twitter handles and attempt to retrieve useful information from it.
This information would in turn be used to identify key characteristics of 2 major news channels’(CNN and Fox News) audiences.

To tackle the recognition of named entities, 3 diﬀerent approaches were considered:
• Existing NLP packages for NER to automatically classify entities
• Dictionary-based method matching known words with their assigned entity name.
• Machine learning Approach using CRF (Conditional Random Fields) and Random forests algorithms

Based on the results below inference was made.
Named Entity Recognition is very dependent on the context and models can hardly generalize to diﬀerent cases. This is probably why custom models trained on case-speciﬁc data performed very well compared to the approaches tried in the ﬁrst instance (out-of-the-box NER models) in the project analysis. To tackle any new problem statement with regards to entity recognition, it may therefore be relevant to adopt a combination of dictionary-based tagging followed with building customised models using machine learning with existing algorithms. Also, the model developed in this context of entity recognition applied to diﬀerent analysis like analysis of job descriptions might perform the same or bad. Hence with named recognition more research might be required on developing models using machine learning or any other approaches that would suﬃce all scenarios.

More details on the project and the codes in python and R are available in the repository

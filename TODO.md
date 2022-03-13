**NLP - Project Option 1**

---------------------

**Goal:** improve our L2R model for the MS-MARCO task we did for the IR project

- Using neural text representation techniques to obtain new features for L2R model
  - Features that capture the semantic relation between queries and passages

**How:** using pre-trained word embeddings (see [Brightspace page](https://brightspace.tudelft.nl/d2l/le/content/400612/Home) for resources)

- Glove
- fastText
- contextual embeddings:
  - DistilBERT
  - ALBERT

**Task:** 
- Compare results from our IR project and analyse the difference with these models
  - Error analysis
    - Do we observe an improvement over the original L2R performance, if so how much?
    - Are there any differences you observe between using word embeddings and contextual embeddings?
    - Do we observe any differences using embeddings pre-trained on different corpora?
    - For all of the above, what are the topics (queries) that you have observed the difference in performance and can you explain the difference?
      - Provide both examples and qualitative results!

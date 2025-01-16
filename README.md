# Beyond-Accuracy-on-Medical-Imaging

Machine Vision Components (MVCs) using Machine Learning (ML) have shown promising results in the field of medical imaging for tasks such as diagnosis, segmentation, and classification. For successful integration into the healthcare domain, it is crucial to assess the reliability and safety of the MVCs being deployed. However, the industry lacks precise definitions of what it means for an ML-based MVC to be "correct." In 2022, Hu et al (https://arxiv.org/abs/2202.03930). introduced a promising definition of a reliability requirement for generic MVCs, using human performance as a baseline. The definition is as follows: "if the changes in an image do not affect a human's decision, neither should they affect the MVC's".

In this paper, we explore how this definition of reliability can be applied to the medical image classification space. We develop a pipeline to assess the reliability of an ML-based MVC focused on mole classification, used in the context of an early detection smartphone app. Specifically, we provide:

- Three realistic image transformations that reflect typical consumer usage scenarios
- A cost-effective methodology to phrase the question in a way that allows gathering data for establishing the "prediction-preservation" baseline for mole classification in the absence of trained medical professionals. 
- Human performance data on a range of transformations that can impact their perception of mole images.
- An evaluation of the MVC's performance in mole classification using this adapted reliability framework.

Finally, we discuss the limitations and shortcomings of our approach in applying the above definition of reliability to the medical imaging domain. 
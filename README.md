# Professional Machine Learning Engineer

Certification exam guide

Version: **05/05/2022** 

by [ruslanmv](https://github.com/ruslanmv)

#### Section 1: Framing ML problems



1.1 Translating business challenges into ML use cases. Considerations include:

  a. Choosing the best solution (ML vs. non-ML, custom vs. pre-packaged [e.g., AutoML, Vision API]) based on the business requirements 

  b. Defining how the model output should be used to solve the business problem

  c. Deciding how incorrect results should be handled

  d. Identifying data sources (available vs. ideal)

1.2 Defining ML problems. Considerations include:

  a. Problem type (e.g., classification, regression, clustering)

  b. Outcome of model predictions

  c. Input (features) and predicted output format

1.3 Defining business success criteria. Considerations include:

  a. Alignment of ML success metrics to the business problem

  b. Key results

  c. Determining when a model is deemed unsuccessful

1.4 Identifying risks to feasibility of ML solutions. Considerations include: 

  a. Assessing and communicating business impact

  b. Assessing ML solution readiness

  c. Assessing data readiness and potential limitations

  d. Aligning with Google’s Responsible AI practices (e.g., different biases)



#### Section 2: Architecting ML solutions



2.1 Designing reliable, scalable, and highly available ML solutions. Considerations include:

  a. Choosing appropriate ML services for the use case (e.g., Cloud Build, Kubeflow)

  b. Component types (e.g., data collection, data management)

  c. Exploration/analysis

  d. Feature engineering

  e. Logging/management

  f. Automation

  g. Orchestration

  h. Monitoring

  i. Serving

2.2 Choosing appropriate Google Cloud hardware components. Considerations include:

  a. Evaluation of compute and accelerator options (e.g., CPU, GPU, TPU, edge devices) 

2.3 Designing architecture that complies with security concerns across sectors/industries. 

Considerations include:

  a.Building secure ML systems (e.g., protecting against unintentional exploitation of data/model, hacking)

  b. Privacy implications of data usage and/or collection (e.g., handling sensitive data such as Personally Identifiable Information [PII] and Protected Health Information [PHI])



#### Section 3: Designing data preparation and processing systems



3.1 Exploring data (EDA). Considerations include:

  a. Visualization

  b. Statistical fundamentals at scale

  c. Evaluation of data quality and feasibility

  d. Establishing data constraints (e.g., TFDV)

3.2 Building data pipelines. Considerations include:

  a. Organizing and optimizing training datasets

  b. Data validation

  c. Handling missing data

  d. Handling outliers

  e. Data leakage

3.3 Creating input features (feature engineering). Considerations include:

  a. Ensuring consistent data pre-processing between training and serving

  b. Encoding structured data types

  c. Feature selection

  d. Class imbalance

  e. Feature crosses

  f. Transformations (TensorFlow Transform)



#### Section 4: Developing ML models



4.1 Building models. Considerations include:

  a. Choice of framework and model

  b. Modeling techniques given interpretability requirements

  c. Transfer learning

  d. Data augmentation

  e. Semi-supervised learning

  f. Model generalization and strategies to handle overfitting and underfitting

4.2 Training models. Considerations include:

  a. Ingestion of various file types into training (e.g., CSV, JSON, IMG, parquet or databases, Hadoop/Spark)

  b. Training a model as a job in different environments

  c. Hyperparameter tuning

  d. Tracking metrics during training

  e. Retraining/redeployment evaluation

4.3 Testing models. Considerations include:

  a. Unit tests for model training and serving

  b. Model performance against baselines, simpler models, and across the time dimension

  c. Model explainability on Vertex AI

4.4 Scaling model training and serving. Considerations include:

  a. Distributed training

  b. Scaling prediction service (e.g., Vertex AI Prediction, containerized serving)



#### Section 5: Automating and orchestrating ML pipelines



5.1 Designing and implementing training pipelines. Considerations include:

  a. Identification of components, parameters, triggers, and compute needs (e.g., Cloud Build, Cloud Run)

  b. Orchestration framework (e.g., Kubeflow Pipelines/Vertex AI Pipelines, Cloud Composer/Apache Airflow)

  c. Hybrid or multicloud strategies

  d. System design with TFX components/Kubeflow DSL 

5.2 Implementing serving pipelines. Considerations include:

  a. Serving (online, batch, caching)

  b. Google Cloud serving options

  c. Testing for target performance

  d. Configuring trigger and pipeline schedules

5.3 Tracking and auditing metadata. Considerations include:

  a. Organizing and tracking experiments and pipeline runs

  b. Hooking into model and dataset versioning

  c. Model/dataset lineage



#### Section 6: Monitoring, optimizing, and maintaining ML solutions



6.1 Monitoring and troubleshooting ML solutions. Considerations include:

  a. Performance and business quality of ML model predictions

  b. Logging strategies

  c. Establishing continuous evaluation metrics (e.g., evaluation of drift or bias)

  d. Understanding Google Cloud permissions model

  e. Identification of appropriate retraining policy

  f. Common training and serving errors (TensorFlow)

  g. ML model failure and resulting biases

6.2 Tuning performance of ML solutions for training and serving in production. 

Considerations include:

  a. Optimization and simplification of input pipeline for training

  b. Simplification techniques 
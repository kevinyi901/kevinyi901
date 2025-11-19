# About Me
👋 About Me

Hi, I’m Kevin Yi — a Principal Data Engineer with a background as a U.S. Army officer and civil engineer, now focused on data science, machine learning, and large-scale data systems. I’m currently pursuing my Master of Information and Data Science at UC Berkeley, where I’m working on projects in predictive modeling, distributed computing, and AI applications at scale.

I specialize in designing and automating real-time data pipelines, building machine learning models that drive actionable insights, and creating dashboards and monitoring systems that ensure reliability in mission-critical environments. My experience spans defense, engineering, and enterprise analytics, and I enjoy tackling problems where technology directly impacts operations and decision-making.

I’m passionate about combining technical depth with leadership experience to help organizations use data more effectively.

# Projects
In my time at MIDS, I have had the opportunity to work on several projects. Most work is ongoing, but here are some of the completed projects that I can share with you:

<details>
<summary>Legal Document Retrieval RAG Pipeline with GPU-Accelerated Search</summary>
<ul>
<li><strong>Type:</strong> RAG Model</li>
<li><strong>Description:</strong>  
Designed and deployed a production-ready Retrieval-Augmented Generation (RAG) pipeline for querying legal documents across multiple jurisdictions. Built a Docker-containerized API service on AWS EC2 (GPU-enabled) that integrates Pinecone vector database, LLaMA 3.1 8B language model with 4-bit quantization, and cross-encoder reranking for high-accuracy document retrieval. Implemented dual search modes: baseline dense embedding search and hybrid search combining dense/sparse embeddings with reranking. Pipeline processes natural language queries, applies multi-dimensional filters (location, legal tags, readability metrics), and generates CSV exports with LLM-generated summaries for frontend integration. Optimized for GPU efficiency with persistent model caching, reducing query time from 15 minutes to 30 seconds after initial load.</li>
<li><strong>Technology:</strong> Python, Docker, AWS EC2 (GPU), Pinecone Vector DB, LLaMA 3.1 8B, Hugging Face Transformers, Flask REST API, CUDA, 4-bit Quantization, Pandas, Git</li>
<li><strong>Key Features:</strong> Hybrid dense/sparse search, Cross-encoder reranking, GPU optimization, REST API, Multi-filter support, CSV export, Model caching</li>
<li><strong>Links to the repository:</strong> [https://github.com/kevinyi901/rag-pipeline]</li>
</ul>
</details>


<details>
<summary> Food delivery company customer and distribution site analytics</summary>
<ul>
<li><strong>Course:</strong> Data Engineering</li>
<li><strong>Description:</strong>  
Project 1: Data Wrangling to load sales data from a third-party sales channel with preliminary analytics. Used AWS and a Docker cluster running Anaconda and PostgreSQL.  
Project 2: Created a Neo4J graph database for the Bay Area BART system to identify future distribution locations for a food delivery service. Used Graph Path to identify the shortest path from a central supply store to distribution nodes, a centrality algorithm to determine the most influential BART station to service existing customers, and a community detection algorithm to identify BART station communities. Identified additional BART station locations for future store expansion.</li>
<li><strong>Technology:</strong> SQL, Python, NoSQL Graph Database, Linux CLI, Docker Containers, Graph Path, Centrality, Community Detection Algorithms</li>
<li><strong>Links to the repository:</strong> [https://github.com/kevinyi901/W205_DataEngineering]</li>
</ul>
</details>


<details>
<summary>A/B Experimental Design and Testing of Emoji Effects on Facebook Marketplace Sales Negotiation</summary>
<ul>
<li><strong>Course:</strong> Experiments and Causal Inference</li>
<li><strong>Description:</strong>  
Project 1: A project conducting an A/B testing on the effects of emojis on seller's willingness to reduce price on Facebook Marketplace.</li>
<li><strong>Technology:</strong> R Studio, T-Test, A/B Testing, Multi-Variate Linear Regression</li>
<li><strong>Links to the repository:</strong> [https://github.com/kevinyi901/W241]</li>
</ul>
</details>


<details>
<summary>Training and Testing ML and AI Models for Sentiment Classification</summary>
<ul>
<li><strong>Course:</strong> Applied Machine Learning</li>
<li><strong>Description:</strong>  
Project 1: Model training and comparisons for Movie sentiment classification using one hot encoding, logistic regression with embedding, Convolutional Neural Network, Hyperparameter tuned Convolutional Neural Network,
            Feature Extraction Distill-Bert-SST2 Transformer, Fine Tuned Distill-Bert-SST2 Transformer
</li>
<li><strong>Technology:</strong> Python, Numpy, TensorFlow, Neural Network and Transformer Models for NLP</li>
<li><strong>Links to the repository:</strong> [https://github.com/kevinyi901/W207]</li>
</ul>
</details>

<details>
<summary>Predicting U.S. Domestic Airline Departure Delays Using Multiclass Classification with Graph-Based and Weather-Enriched Features</summary>
<ul>
<li><strong>Course:</strong> Machine Learning at Scale</li>
<li><strong>Description:</strong>  
Predict domestic U.S. commercial airline departure delays (≥15 minutes) two hours prior to departure, framed as a multiclass classification problem (Early, On-Time, Delayed).</li>
<li><strong>Technology:</strong> Databricks, Spark, Logistic Classification </li>
<li><strong>Links to the repository:</strong> [https://github.com/kevinyi901/W261_Final]</li>
</ul>
</details>


<details>
<summary>Hypothesis Testing and Multiple Variable Large Sample Linear Regression</summary>
<ul>
<li><strong>Course:</strong> Statistics for Data Science</li>
<li><strong>Description:</strong>  
Project 1: A project exploring, visualizing, and conducting hypothesis testing on whether Republican voters or Democrat voters have more difficulty voting.  
Project 2: A project evaluating if one's occupation impacts the amount of hours worked weekly using general census data.</li>
<li><strong>Technology:</strong> R Studio, T-Test, Classical Linear Model Assumption Testing, Multi-Variate Linear Regression</li>
<li><strong>Links to the repository:</strong> [https://github.com/kevinyi901/W203_Statistics]</li>
</ul>
</details>

<details>
<summary>Exploratory Data Analysis of Colon and Lung Cancer</summary>
<ul>
<li><strong>Course:</strong> Introduction to Data Science Programming</li>
<li><strong>Description:</strong> A project cleaning, exploring, and visualizing 2008-2019 data from the CDC to identify racial, geographical, and gender trends in lung and colon cancer in America.</li>
<li><strong>Technology:</strong> Python, Pandas, Plotly, Matplotlib, Seaborn</li>
<li><strong>Links to the repository:</strong> [https://github.com/kevinyi901/W200]</li>
</ul>
</details>

<details>
<summary>Experimental Research Design Report</summary>
<ul>
<li><strong>Course:</strong> Research Design and Applications for Data Analysis</li>
<li><strong>Description:</strong> A project developing a research design report that will produce valuable and actionable insight for predicting grocery product sales using existing prediction models and social media data.</li>
<li><strong>Links to the repository:</strong> [https://github.com/kevinyi901/W201]</li>
</ul>
</details>

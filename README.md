# Awesome Kedro [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome#readme) 

<div align="center"><img width="500" src="kedro_banner.png" alt="kedro logo"></div>

> An opinionated Python framework for creating reproducible, maintainable and modular data science code.

[![Python version](https://img.shields.io/badge/python-3.7%20%7C%203.8%20%7C%203.9%20%7C%203.10-blue.svg)](https://pypi.org/project/kedro/)
[![PyPI version](https://badge.fury.io/py/kedro.svg)](https://pypi.org/project/kedro/)
[![Conda version](https://img.shields.io/conda/vn/conda-forge/kedro.svg)](https://anaconda.org/conda-forge/kedro)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/kedro-org/kedro/blob/main/LICENSE.md)
[![Slack Organisation](https://img.shields.io/badge/slack-chat-blueviolet.svg?label=Kedro%20Slack&logo=slack)](https://slack.kedro.org)
[![Slack Archive](https://img.shields.io/badge/slack-archive-blueviolet.svg?label=Kedro%20Slack%20)](https://linen-slack.kedro.org/) 
![CircleCI - Main Branch](https://img.shields.io/circleci/build/github/kedro-org/kedro/main?label=main)
![Develop Branch Build](https://img.shields.io/circleci/build/github/kedro-org/kedro/develop?label=develop)
[![Documentation](https://readthedocs.org/projects/kedro/badge/?version=stable)](https://docs.kedro.org/)
[![OpenSSF Best Practices](https://bestpractices.coreinfrastructure.org/projects/6711/badge)](https://bestpractices.coreinfrastructure.org/projects/6711)
[![Monthly downloads](https://static.pepy.tech/badge/kedro/month)](https://pepy.tech/project/kedro)
[![Total downloads](https://static.pepy.tech/badge/kedro)](https://pepy.tech/project/kedro)

## Contents

- [Awards and highlights](#awards-and-highlights)
- [Blog posts](#blog-posts)
- [Companies using Kedro](#companies-using-kedro)
- [Example projects](#example-projects)
- [Kedro plugins](#kedro-plugins)
- [Videos](#videos)
  - [Intros](#intros)
  - [Howtos](#howtos)


## Awards and highlights
* Kedro won [Best Technical Tool or Framework for AI](https://awards.ai/the-awards/previous-awards/the-4th-ai-award-winners/) in the 2019 Awards AI competition 
* Kedro documentation won a merit award for the 2020 [UK Technical Communication Awards](https://uktcawards.com/announcing-the-award-winners-for-2020/). 
* The Kedro framework is listed on the 2020 [ThoughtWorks Technology Radar](https://www.thoughtworks.com/radar/languages-and-frameworks/kedro) and the 2020 [Data & AI Landscape](https://mattturck.com/data2020/). 
* Kedro has received an [honorable mention in the User Experience category in Fast Company’s 2022 Innovation by Design Awards](https://www.fastcompany.com/90772252/user-experience-innovation-by-design-2022).

## Blog posts

In no particular order:

- [Official Kedro blog](https://blog.kedro.org)
- [Building and Managing Data Science Pipelines with Kedro](https://neptune.ai/blog/data-science-pipelines-with-kedro)
- [Deploying Kedro Pipelines to Apache Airflow](https://www.astronomer.io/guides/airflow-kedro)
- [Writing your first kedro Nodes](https://waylonwalker.com/kedro-your-first-nodes/)
- [Setting Parameters in kedro](https://waylonwalker.com/kedro-parameters/)
- [Add New Dependencies to Your Kedro Project](https://waylonwalker.com/kedro-new-dependencies/)
- [Running your Kedro Pipeline from the command line](https://waylonwalker.com/kedro-run/)
- [Kedro Virtual Environment](https://waylonwalker.com/kedro-environment/)
- [Kedro Pipeline Create](https://waylonwalker.com/kedro-pipeline-create/)
- [Kedro Install](https://waylonwalker.com/kedro-install/)
- [Kedro Git Init](https://waylonwalker.com/kedro-git-init/)
- [Kedro New](https://waylonwalker.com/kedro-new/)
- [What is Kedro](https://waylonwalker.com/what-is-kedro/)
- [How I Kedro](https://waylonwalker.com/how-i-kedro/)
- [Incremental Versioned Datasets in Kedro](https://waylonwalker.com/kedro-incremental-versioned-datasets/)
- [Productionizing ML Pipelines with Airflow, Kedro, and Great Expectations](https://airflowsummit.org/sessions/2021/productionizing-ml-pipelines-with-airflow-kedro-great-expectations/)
- [Change Data Capture With Kedro and Dolt](https://www.dolthub.com/blog/2021-06-16-kedro-dolt-plugin/)
- [Applying data engineering to applications with Kedro](https://www.nearform.com/blog/applying-data-engineering-to-applications-with-kedro/)
- [Running Machine Learning Pipelines with Kedro, Kubeflow and Airflow](https://getindata.com/blog/running-machine-learning-pipelines-kedro-kubeflow-airflow/)
- [Introducing Kedro: Yetunde Dada, Principal Product Manager at QuantumBlack](https://mattturck.com/kedro/)
- [Standardization of End-to-End Data Pipeline for AI Project Using Kedro](https://www.lftechnology.com/blog/ai-pipeline-kedro/)
- [Using Kedro pipelines to train Amazon SageMaker models](https://aws.amazon.com/blogs/opensource/using-kedro-pipelines-to-train-amazon-sagemaker-models/)
- [Kedro 6 Months In](https://lou.dev/blog/2020/kedro/)
- [Jungle Scout case study: Kedro, Airflow, and MLFlow use on production code](https://junglescouteng.medium.com/jungle-scout-case-study-kedro-airflow-and-mlflow-use-on-production-code-150d7231d42e)
- [Building a Production-Level Data Pipeline Using Kedro](https://opendatascience.com/building-a-production-level-data-pipeline-using-kedro/)
- [Designing a "Router" for kedro](https://waylonwalker.com/blog/designing-kedro-router)
- [Power is nothing without control](https://towardsdatascience.com/power-is-nothing-without-control-aa43523745b6)
- [Start small and grow big MLOps2020](https://speakerdeck.com/chck/sok-xiao-sakushi-meteda-kikuyu-terumlops2020)
- [Get Started with Machine Learning Pipelines at Kedro](https://qiita.com/noko_qii/items/2395d3a3dbcd9410e5e7)
- [Mid Meet Py - Ep.14 - Interview with Waylon Walker](https://dev.to/midmeetpy/mid-meet-py-ep-14-interview-with-waylon-walker-2h01)
- [How to find datasets in your kedro catalog](https://dev.to/waylonwalker/how-to-find-datasets-in-your-kedro-catalog-5a4b)
- [How Kedro handles your inputs](https://dev.to/waylonwalker/how-kedro-handles-your-inputs-162i)
- [Post mortem debugging sessions with Kedro hooks](https://zainp.com/kedro-debugging-hooks/)
- [Start small and grow big MLOps2020](https://cyberagent.ai/blog/research/12898/)
- [Create Configurable Kedro Hooks](https://dev.to/waylonwalker/create-configurable-kedro-hooks-4k34)
- [What's an example use case of Kedro?](https://www.softwaredaily.com/topic/kedro/question/5ecd36859f3c7b002d7dc16f)
- [Make Notebook Pipeline with Kedro+Papermill ](https://qiita.com//hrappuccino/items/584c22c3cd5a2f0247d8)
- [25 Hot New Data Tools and What They DON’T do](https://towardsdatascience.com/25-hot-new-data-tools-and-what-they-dont-do-31bf23bd8e56)
- [Kedro Hooks Intro - creating the kedro-preflight hook](https://dev.to/waylonwalker/creating-the-kedro-preflight-hook-29f2)
- [Next Generation Data Science and Data Engineering Frameworks](https://medium.com/@will_flwrs/python-data-engineering-tools-the-next-generation-354e00f2f060)
- [Understanding best-practice Python tooling by comparing popular project templates](https://medium.com/@jonas.r.kemper/understanding-best-practice-python-tooling-by-comparing-popular-project-templates-6eba49229106)
- [A story using the Kedro pipeline library](http://socinuit.hatenablog.com/entry/2020/02/08/210423)
- [Transparent data flow with Kedro](https://medium.com/@mapmeld/transparent-data-flow-with-kedro-eba842de4eb2)
- [Comparison of Python pipeline packages: Airflow, Luigi, Metaflow, Kedro & PipelineX](https://medium.com/@Minyus86/comparison-of-pipeline-workflow-packages-airflow-luigi-gokart-metaflow-kedro-pipelinex-5daf57c17e7)
- [Kedro in Jupyter Notebooks On Google GCP Dataproc](https://medium.com/@zhongchen/kedro-in-jupyter-notebooks-on-google-gcp-dataproc-31d5f45ad235)
- [Building a Pipeline with Kedro for an ML Competition](https://medium.com/mhiro2/building-pipeline-with-kedro-for-ml-competition-63e1db42d179)
- [Using Kedro and MLflow Deploying and versioning data pipelines at scale](https://medium.com/@QuantumBlack/deploying-and-versioning-data-pipelines-at-scale-942b1d81b5f5)
- [Ship Faster With An Opinionated Data Pipeline Framework Episode** 100](https://www.dataengineeringpodcast.com/kedro-data-pipeline-episode-100/)
- [Some cool open-source Python packages for Machine Learning](https://aetperf.github.io/2019/07/11/Some-cool-open-source-Python-packages-for-Machine-Learning.html)
- [Kedro: A New Tool For Data Science ](https://towardsdatascience.com/kedro-prepare-to-pimp-your-pipeline-f8f68c263466)
- [Standardization of End-to-End Data Pipeline for AI Project Using Kedro](https://www.lftechnology.com/blog/ai-pipeline-kedro/)
- [The latest and greatest in Kedro — We’re growing our community](https://quantumblack.medium.com/the-latest-and-greatest-in-kedro-were-growing-our-community-c868825b0cb4)
- [Kedro-Airflow 0.4.0 — Orchestrating Kedro Pipelines with Airflow](https://medium.com/quantumblack/kedro-airflow-0-4-0-orchestrating-kedro-pipelines-with-airflow-23fb1283f24d)
- [Beyond the Notebook and into the Data Science Framework Revolution](https://medium.com/quantumblack/beyond-the-notebook-and-into-the-data-science-framework-revolution-a7fd364ab9c4)
- [Element AI uses Kedro to apply research and develop enterprise AI models](https://medium.com/quantumblack/element-ai-uses-kedro-to-apply-research-and-develop-enterprise-ai-models-bbbf2e3ff722)
- [Introducing Kedro Hooks](https://medium.com/quantumblack/introducing-kedro-hooks-fd5bc4c03ff5)
- [Getting Started with Kedro](https://medium.com/quantumblack/getting-started-with-kedro-67edcc316f6a)
- [Introducing Kedro](https://medium.com/quantumblack/introducing-kedro-the-open-source-library-for-production-ready-machine-learning-code-d1c6d26ce2cf)
- [Deploying and Versioning Data Pipelines at Scale](https://medium.com/quantumblack/deploying-and-versioning-data-pipelines-at-scale-942b1d81b5f5)
- [Kedro hands-on](https://towardsdatascience.com/kedro-hands-on-build-your-own-demographics-atlas-pt-2-building-footprints-classification-8c48060e5c1a) Build your own demographics atlas. Pt. 2: building footprints classification
- [Kedro (Python template for production-quality ML data pipelines)](https://wilsonmar.github.io/kedro/)
- [Enhance your kedro experiences with these tips](https://towardsdatascience.com/enhance-your-kedro-experiences-with-these-tips-3036c3b7564)
- [Kedro: The Best Python Framework for Data Science!!](https://jlgjosue.medium.com/kedro-the-best-python-framework-for-data-science-fda6d8503646)
- [kedro-in-6-months](https://towardsdatascience.com/kedro-6-months-in-138c27aed13b)
- [Deploying a Recommendation System the Kedro Way](https://itstherealdyl.com/2022/03/29/deploying-a-recommendation-system-the-kedro-way/)
- [Efficient Data Sharing in Data Science Pipelines on Kubernetes](https://medium.com/cncf-vineyard/efficient-data-sharing-in-data-science-pipelines-on-kubernetes-bb42d36c739)
- [Deep Learning with Azure: PyTorch distributed training done right in Kedro](https://getindata.com/blog/deep-learning-with-azure-pytorch-distributed-training-done-right-kedro/)
- [Running Machine Learning Pipelines with Kedro, Kubeflow and Airflow ](https://getindata.com/blog/running-machine-learning-pipelines-kedro-kubeflow-airflow/)
- [Running Kedro… everywhere? Machine Learning Pipelines on Kubeflow, Vertex AI, Azure and Airflow](https://getindata.com/blog/running-kedro-everywhere-machine-learning-pipelines-kubeflow-vertex-ai-azure-airflow/)

For more:
- [#kedro](https://dev.to/t/kedro) tag on dev.to


## Companies using Kedro

There are Kedro users across the world, who work at start-ups, major enterprises and academic institutions like [Absa](https://www.absa.co.za/),
[Acensi](https://acensi.eu/page/home),
[Advanced Programming Solutions SL](https://www.linkedin.com/feed/update/urn:li:activity:6863494681372721152/),
[AI Singapore](https://makerspace.aisingapore.org/2020/08/leveraging-kedro-in-100e/),
[AMAI GmbH](https://www.am.ai/),
[Augment Partners](https://www.linkedin.com/posts/augment-partners_kedro-cheat-sheet-by-augment-activity-6858927624631283712-Ivqk),
[AXA UK](https://www.axa.co.uk/),
[Belfius](https://www.linkedin.com/posts/vangansen_mlops-machinelearning-kedro-activity-6772379995953238016-JUmo),
[Beamery](https://medium.com/hacking-talent/production-code-for-data-science-and-our-experience-with-kedro-60bb69934d1f),
[Caterpillar](https://www.caterpillar.com/),
[CRIM](https://www.crim.ca/en/),
[Dendra Systems](https://www.dendra.io/),
[Element AI](https://www.elementai.com/),
[GetInData](https://getindata.com/blog/running-machine-learning-pipelines-kedro-kubeflow-airflow),
[GMO](https://recruit.gmo.jp/engineer/jisedai/engineer/jisedai/engineer/jisedai/engineer/jisedai/engineer/jisedai/blog/kedro_and_mlflow_tracking/),
[Indicium](https://medium.com/indiciumtech/how-to-build-models-as-products-using-mlops-part-2-machine-learning-pipelines-with-kedro-10337c48de92),
[Imperial College London](https://github.com/dssg/barefoot-winnie-public),
[ING](https://www.ing.com),
[Jungle Scout](https://junglescouteng.medium.com/jungle-scout-case-study-kedro-airflow-and-mlflow-use-on-production-code-150d7231d42e),
[Helvetas](https://www.linkedin.com/posts/lionel-trebuchon_mlflow-kedro-ml-ugcPost-6747074322164154368-umKw),
[Leapfrog](https://www.lftechnology.com/blog/ai-pipeline-kedro/),
[McKinsey & Company](https://www.mckinsey.com/alumni/news-and-insights/global-news/firm-news/kedro-from-proprietary-to-open-source),
[Mercado Libre Argentina](https://www.mercadolibre.com.ar),
[Modec](https://www.modec.com/),
[Mosaic Data Science](https://www.youtube.com/watch?v=fCWGevB366g),
[NaranjaX](https://www.youtube.com/watch?v=_0kMmRfltEQ),
[NASA](https://github.com/nasa/ML-airport-taxi-out),
[NHS AI Lab](https://nhsx.github.io/skunkworks/synthetic-data-pipeline),
[Open Data Science LatAm](https://www.odesla.org/),
[Prediqt](https://prediqt.co/),
[QuantumBlack](https://medium.com/quantumblack/introducing-kedro-the-open-source-library-for-production-ready-machine-learning-code-d1c6d26ce2cf),
[ReSpo.Vision](https://neptune.ai/customers/respo-vision),
[Retrieva](https://tech.retrieva.jp/entry/2020/07/28/181414),
[Roche](https://www.roche.com/),
[Sber](https://www.linkedin.com/posts/seleznev-artem_welcome-to-kedros-documentation-kedro-activity-6767523561109385216-woTt),
[Société Générale](https://www.societegenerale.com/en),
[Telkomsel](https://medium.com/life-at-telkomsel/how-we-build-a-production-grade-data-pipeline-7004e56c8c98),
[Universidad Rey Juan Carlos](https://github.com/vchaparro/MasterThesis-wind-power-forecasting/blob/master/thesis.pdf),
[UrbanLogiq](https://urbanlogiq.com/),
[Wildlife Studios](https://wildlifestudios.com),
[WovenLight](https://www.wovenlight.com/) and
[XP](https://youtu.be/wgnGOVNkXqU?t=2210).


## Example projects

- [Churn Prediction with Kedro](https://github.com/laizaparizotto/churn-prediction-kedro) by [Laíza Parizotto](https://github.com/laizaparizotto), a project that tackles a data science challenge of predicting customer churn for a fictional financial institution, using Kedro to build an effective pipeline for a production-ready machine learning model.
- [Response Recommendation System for BarefootLaw](https://github.com/dssg/barefoot-winnie-public) by Kasun Amarasinghe, Carlos Caro, Nupoor Gandhi and Raphaelle Roffo, an extensive Data Science for Social Good (DSSG) at Imperial College London project that recommends responses to law related queries
- [Augury](https://github.com/tipresias/augury) by [Craig Franklin](https://github.com/cfranklin11), machine-learning functionality for predicting AFL match results in the Tipresias app
- [CausalLift](https://github.com/Minyus/causallift) by [Yusuke Minami](https://github.com/Minyus), a Python package for Uplift Modeling in real-world business
- [PipelineX](https://github.com/Minyus/pipelinex) by [Yusuke Minami](https://github.com/Minyus), a Python package to develop pipelines for rapid Machine/Deep Learning experimentation using Kedro and MLflow. Example projects using PyTorch, Pandas, and OpenCV are available.
- [kedro-mlflow-example](https://github.com/tgoldenberg/kedro-mlflow-example) by [Tom Goldenberg](https://github.com/tgoldenberg), a project that demonstrates how to integrate MLflow with a Kedro codebase
- [kedro-wdbc-tf](https://github.com/abhinavsp0730/kedro-wdbc-tf) by [Abhinav Prakash](https://github.com/abhinavsp0730), this project uses a Kedro template to create Deep Learning workflow. The model training was done with TensorFlow  against the wdbc (Breast Cancer) dataset.
- [twitter-sentiment-analysis](https://github.com/aviagarwal1212/twitter-sentiment-analysis/blob/main/README.md) by [Avi Agarwal](https://github.com/aviagarwal1212), a project that demonstrates how to use Kedro to train and evaluate an NLP-based machine learning model.
- [Anomaly Detection Pipeline with Kedro](https://github.com/kennethleungty/Anomaly-Detection-Pipeline-Kedro) by [Kenneth Leung](https://github.com/kennethleungty), a project that demonstrates how to use Kedro for fraud detection on credit card transaction data using an Isolation Forest machine learning model.

## [Kedro plugins](https://docs.kedro.org/en/stable/extend_kedro/plugins.html)

- [find-kedro](https://github.com/WaylonWalker/find-kedro) - Automatically construct pipelines using pytest style pattern matching.
- [kedro-accelerator](https://github.com/deepyaman/kedro-accelerator/) - Speeds up pipelines by parallelizing I/O in the background.
- [kedro-airflow](https://pypi.org/project/kedro-airflow/) - Makes it easy to deploy Kedro projects to Airflow.
- [kedro-airflow-k8s](https://github.com/getindata/kedro-airflow-k8s) - Enables running a Kedro pipeline with Airflow on a Kubernetes cluster.
- [kedro-argo](https://pypi.org/project/kedro-argo/) - Converts Kedro pipelines to Argo pipelines.
- [kedro-auto-catalog](https://github.com/WaylonWalker/kedro-auto-catalog) - A configurable replacement for kedro catalog create that allows you to create default dataset types other than `MemoryDataset`.
- [kedro-azureml](https://github.com/getindata/kedro-azureml) - Enables running a Kedro pipeline with Azure ML Pipelines service.
- [kedro-dataframe-dropin](https://github.com/mzjp2/kedro-dataframe-dropin) - Lets you swap out pandas datasets for modin or RAPIDs equivalents for specialised use to speed up your workflows (e.g on GPUs).
- [kedro-datasets](https://github.com/kedro-org/kedro-plugins/tree/main/kedro-datasets) - A collection of Kedro data connectors.
- [kedro-docker](https://pypi.org/project/kedro-docker/) - Makes it easy to package Kedro projects with Docker.
- [kedro-dolt](https://www.dolthub.com/blog/2021-06-16-kedro-dolt-plugin/) - Allows you to expand the data versioning abilities of data scientists and engineers
- [kedro-great](https://github.com/tamsanh/kedro-great) - The easiest way to integrate Kedro and Great Expectations.
- [kedro-grpc-server](https://pypi.org/project/kedro-grpc-server/) - Creates a gRPC server for your kedro pipelines.
- [kedro-kubeflow](https://github.com/getindata/kedro-kubeflow) - Lets you run and schedule pipelines on Kubernetes clusters using Kubeflow Pipelines.
- [kedro-mlflow](https://pypi.org/project/kedro-mlflow/) - Allows usage of MLFlow in Kedro projects.
- [kedro-neptune](https://github.com/neptune-ai/kedro-neptune) - Integration of Kedro with Neptune.ai.
- [kedro-pandas-profiling](https://pypi.org/project/kedro-pandas-profiling/) - "Profiles" data in the catalog.
- [kedro-partitioned](https://github.com/ProjetaAi/kedro-partitioned) - Extends the functionality on processing partitioned data.
- [kedro-sagemaker](https://github.com/getindata/kedro-sagemaker) - Enables running a Kedro pipeline with Amazon SageMaker service.
- [kedro-snowflake]([https://github.com/getindata/kedro-sagemaker](https://github.com/getindata/kedro-snowflake)) - Enables to run full Kedro pipelines in Snowflake.
- [kedro-static-viz](https://github.com/WaylonWalker/kedro-static-viz) - Generates a static Kedro-Viz site (HTML, CSS, JS)
- [kedro-viz](https://pypi.org/project/kedro-viz/) - Helps visualise Kedro data and analytics pipelines.
- [kedro-vertexai](https://github.com/getindata/kedro-vertexai) - Enables running a Kedro pipeline with Vertex AI Pipelines service.
- [kedro-wings](https://pypi.org/project/kedro-wings/) - Automatically creates catalog entries to simplify Kedro pipeline writing.- [more-kedro](https://pypi.org/project/more-kedro/) - (Hook) library for on the fly typing and validation of parameter dictionaries and default value backed data loading.
- [steel-toes](https://pypi.org/project/steel-toes/) - Prevent changing downstream catalog data on your teammates while developing in parallel.
- [vineyard-kedro](https://pypi.org/project/vineyard-kedro) - Custom `DataSet` and `Runner` which enables sharing intermediate data between tasks in Kedro pipelines using Vineyard, a cloud-native in-memory object manager.

For more:
- [kedro-plugin](https://github.com/topics/kedro-plugin) topic on GitHub

## Videos
### Intros
- [What is Kedro? Why is it useful? A Non-Technical Intro to Kedro](https://www.youtube.com/watch?v=dAtZiyQeN8Y) - An intro for management people.
- [PyConUS 20201 - Reproducible and maintainable data science code with Kedro](https://www.youtube.com/watch?v=JLTYNPoK7nw)
- [Principled Data Science Workflows](https://youtu.be/Dx2vG6qmtPs)
- [Production-level data pipelines that make everyone happy using Kedro](https://youtu.be/OFObles2CJs)
- [Kedro - Nubank ML Meetup](https://youtu.be/clBgxmDsSjI) (Portuguese)
- [Data Science Best Practices con Kedro](https://youtu.be/_0kMmRfltE) (Spanish)

### Howtos
- [Refactor your Jupyter notebooks using Kedro](https://www.youtube.com/watch?v=qClSGY6B0r0)
- [Introduction to Kedro training with Joel Schwarzmann](https://www.youtube.com/watch?v=NU7LmDZGb6E)
- [Creating Shared Catalogs for your Kedro Projects on GitHub](https://www.youtube.com/watch?v=GwSj64Uqnhk)
- [Deployable REST Enabled Data Pipelines with Flask, Docker, Kedro](https://www.youtube.com/watch?v=z7MIq-B4hPA)
- [How to begin writing tests for your Pipelines](https://www.youtube.com/watch?v=3pF0lZfmvOM)
- [How To Customize Your Kedro CLI Options](https://www.youtube.com/watch?v=euuXz6RLKVE)
- [How to Get/Write Data from/to a SQL Database](https://www.youtube.com/watch?v=24_Acr0oLaQ) - Use `pandas.SQLTableDataSet` or `pandas.SQLQueryDataSet`.
- [How to Lazily Evaluate Chunks of a Big Pandas DataFrame](https://www.youtube.com/watch?v=cbZ4cxCtLZc)
- [How to Setup PySpark for your Kedro Pipeline](https://www.youtube.com/watch?v=vYBMpPZep6E)
- [Kedro Great: Use Great Expectations with Ease!](https://www.youtube.com/watch?v=VY_AO0__oIE) - Show how to use kedro-great to e.g. validate data container meta data (columns, etc.).
- [Run machine learning pipelines on ❄ Snowflake using Kedro 🔧 MLOPS TUTORIAL](https://www.youtube.com/watch?v=mUyD2fJRvRU)
- [Kedro + PyTorch. MLOps TUTORIAL by Marcin Zabłocki](https://www.youtube.com/watch?v=u2hRsCSDcQ8)
- [Kedro + AWS SageMaker TUTORIAL](https://www.youtube.com/watch?v=yXIdz4kNMc8)
- [How to run Kedro pipelines on Azure ML Pipelines service? - MLOPS TUTORIAL - Marcin Zabłocki](https://www.youtube.com/watch?v=w_9RzYpGplY)

For more:
- [@kedro-python on YouTube](https://www.youtube.com/@kedro-python)

### News
- [Kedro Community Update - April 2023](https://www.youtube.com/watch?v=ACwLKx8TEXc) - Kedro 0.18.7, new `OmegaConfigLoader`, experiment tracking in Kedro Viz, improvements in Databricks workflow, and more.
- [Let's look at Kedro 0.17.0!](https://www.youtube.com/watch?v=AVX31IVbpoE)
- [Kedro 0.16.0 was just Released!](https://www.youtube.com/watch?v=HxU6SL14jc4) - Release notes (features) of Kedro 0.16.0 explained.


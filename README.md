# Awesome Kedro [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome#readme) 

<div align="center"><img width="500" src="kedro_icon_no-type_whitebg.svg" alt="kedro logo"></div>

> A framework for creating reproducible, maintainable and modular data science code.

## Contents

- [Plugins](#plugins)
- [Utilities](#utilities)
- [Blog posts](#blog-posts)
- [Videos](#videos)
- [Documentation](#documentation)
- [Community](#community)

## [Plugins](https://kedro.readthedocs.io/en/stable/07_extend_kedro/05_plugins.html)

- [kedro-accelerator](https://github.com/deepyaman/kedro-accelerator/) - Speeds up pipelines by parallelizing I/O in the background.
- [kedro-airflow](https://pypi.org/project/kedro-airflow/) - Makes it easy to deploy Kedro projects to Airflow.
- [kedro-argo](https://pypi.org/project/kedro-argo/) - Converts Kedro pipelines to Argo pipelines.
- [kedro-docker](https://pypi.org/project/kedro-docker/) - Makes it easy to package Kedro projects with Docker.
- [kedro-grpc-server](https://pypi.org/project/kedro-grpc-server/) - Creates a gRPC server for your kedro pipelines.
- [kedro-mlflow](https://pypi.org/project/kedro-mlflow/) - Allows usage of MLFlow in Kedro projects.
- [kedro-pandas-profiling](https://pypi.org/project/kedro-pandas-profiling/) - "Profiles" data in the catalog.
- [kedro-viz](https://pypi.org/project/kedro-viz/) - Helps visualise Kedro data and analytics pipelines.
- [kedro-wings](https://pypi.org/project/kedro-wings/) - Automatically creates catalog entries to simplify Kedro pipeline writing.

## Utilities

- [find-kedro](https://pypi.org/project/find-kedro/) - CLI tool ẃhich finds nodes for pipelines.
- [more-kedro](https://pypi.org/project/more-kedro/) - (Hook) library for on the fly typing and validation of parameter dictionaries and default value backed data loading.
- [steel-toes](https://pypi.org/project/steel-toes/) - Prevent changing downstream catalog data on your teammates while developing in parallel.

## Blog posts

- [kedro-in-scripts](https://waylonwalker.com/kedro-in-scripts/) - Getting started with Kedro in a single script
- [kedro-silence](https://waylonwalker.com/kedro-silence/) - Setting all kedro logs for clean output
- [pipeline-registry](https://waylonwalker.com/kedro-pipeline-registry/) - Converting from hooks.py to pipeline_registry, what you need to know.
- [minimal-pipeline](https://waylonwalker.com/minimal-kedro-pipeline/) - The minimal pipeline package (just pipeline no catalog or runner)
- [kedro-pickle](https://waylonwalker.com/kedro-pickle/) - How to use Kedro when your data is not a table.
- [reasons-to-kedro](https://waylonwalker.com/reasons-to-kedro/) - Reasons to consider using Kedro.
- [whats-new-in-kedro-166](https://waylonwalker.com/whats-new-in-kedro-0166/) - What's new in Kedro 0.16.6
- [whats-new-in-kedro-164](https://waylonwalker.com/whats-new-in-kedro-0164/) - What's new in Kedro 0.16.4
- [graceful-catalog](https://waylonwalker.com/graceful-kedro-catalog/) - Gracefully adopt the Kedro catalog in a non-Kedro project
- [kedro-catalog-search](https://waylonwalker.com/kedro-catalog-search/) - How to find entries in your Kedro catalog
- [Kedro (Python template for production-quality ML data pipelines)](https://wilsonmar.github.io/kedro/)
- [kedro-inputs](https://waylonwalker.com/kedro-inputs/) - How Kedro handles your inputs
- [kedro-preflight-hook](https://waylonwalker.com/creating-the-kedro-preflight-hook/) - Creating the kedro-preflight hook
- [Kedro: A New Tool For Data Science](https://towardsdatascience.com/kedro-prepare-to-pimp-your-pipeline-f8f68c263466)
- [Deploying and Versioning Data Pipelines at Scale](https://medium.com/quantumblack/deploying-and-versioning-data-pipelines-at-scale-942b1d81b5f5)

## Videos

### Intros

- (kedro) [Kedro 0.16.0 was just Released!](https://www.youtube.com/watch?v=HxU6SL14jc4) - Release notes (features) of Kedro 0.16.0 explained.
- (kedro) [What is Kedro? Why is it useful? A Non-Technical Intro to Kedro](https://www.youtube.com/watch?v=dAtZiyQeN8Y) - An intro for management people.

### Howtos

- [Creating Shared Catalogs for your Kedro Projects on GitHub](https://www.youtube.com/watch?v=GwSj64Uqnhk)
- [Deployable REST Enabled Data Pipelines with Flask, Docker, Kedro](https://www.youtube.com/watch?v=z7MIq-B4hPA)
- [How to begin writing tests for your Pipelines](https://www.youtube.com/watch?v=3pF0lZfmvOM)
- [How To Customize Your Kedro CLI Options](https://www.youtube.com/watch?v=euuXz6RLKVE)
- [How to Get/Write Data from/to a SQL Database](https://www.youtube.com/watch?v=24_Acr0oLaQ) - Use `pandas.SQLTableDataSet` or `pandas.SQLQueryDataSet`.
- [How to Lazily Evaluate Chunks of a Big Pandas DataFrame](https://www.youtube.com/watch?v=cbZ4cxCtLZc)
- [How to Setup PySpark for your Kedro Pipeline](https://www.youtube.com/watch?v=vYBMpPZep6E)
- [Kedro Great: Use Great Expectations with Ease!](https://www.youtube.com/watch?v=VY_AO0__oIE) - Show how to use kedro-great to e.g. validate data container meta data (columns, etc.).

## Documentation

- [Documentation](kedro.readthedocs.io)

## Community

- [Forum](https://discourse.kedro.community/)
- [Stackoverflow (tag:kedro)](https://stackoverflow.com/questions/tagged/kedro)

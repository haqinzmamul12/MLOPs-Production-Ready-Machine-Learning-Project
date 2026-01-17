# MLOPs-Production-Ready-Machine-Learning-Project
## Project structure

Below is the repository directory structure:

```
.
|-- .dockerignore
|-- .git/
|-- .gitignore
|-- .ml-mlops/
|-- app.py
|-- config/
|   |-- model.yaml
|   `-- schema.yaml
|-- demo.py
|-- Dockerfile
|-- LICENSE
|-- README.md
|-- requirements.txt
|-- setup.py
|-- template.py
|-- us_visa/
|   |-- __init__.py
|   |-- components/
|   |   |-- __init__.py
|   |   |-- data_ingestion.py
|   |   |-- data_transformation.py
|   |   |-- data_validation.py
|   |   |-- model_evaluation.py
|   |   |-- model_pusher.py
|   |   `-- model_trainer.py
|   |-- configuration/
|   |   `-- __init__.py
|   |-- constants/
|   |   `-- __init__.py
|   |-- entity/
|   |   |-- __init__.py
|   |   |-- artifact_entity.py
|   |   `-- config_entity.py
|   |-- exception/
|   |   `-- __init__.py
|   |-- logger/
|   |   `-- __init__.py
|   |-- pipline/
|   |   |-- __init__.py
|   |   |-- prediction_pipeline.py
|   |   `-- training_pipeline.py
|   `-- utils/
|       |-- __init__.py
|       `-- main_utils.py
```
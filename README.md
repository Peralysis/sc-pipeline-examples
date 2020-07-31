# Example Multi-stage Azure Pipelines for Sitecore
> Note: This is an extremely naive example of CI/CD pipelines for a QA and production environment meant to demonstrate how the fundamentals of YAML pipelines and templates.

## Templates
The [templates](templates/README.md) folder contains the stage templates for builds and deployments. These referenced from [`qa-pipeline.yml`](qa-pipeline.yml) and [`prod-pipeline.yml`](prod-pipeline.yml).

## Pipelines
[`qa-pipeline.yml`](qa-pipeline.yml) and [`prod-pipeline.yml`](prod-pipeline.yml) are the actual pipelines.

[`qa-pipeline.yml`](qa-pipeline.yml) represents a testing/QA instance. 

[`prod-pipeline.yml`](prod-pipeline.yml) represents a production instance.
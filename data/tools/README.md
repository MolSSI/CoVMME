# External links to tools & services related to COVID-19

## To add new resources

Contribute a separate [YAML file](https://yaml.org/) for each entry.

### YAML schema

Each entry has the following required and optional keys:
```
name: (required)
url: (required)
description: (required)
organization: (optional)
institution: (optional)
lab: (optional)
type: (required) one or more of [analysis, construction, workflows, machine learning, productivity]
input_data: (required if type has "analysis" or "construction") one or more of [structure, trajectory]
output: (required if type has "analysis" or "construction") one or more of [visualization, analytics, structure, trajectory]
api: (optional) 
```

# Executors

Only one executor is provide, `python-docker`. This executor utilizes the official CircleCI Python Image.
This executor provides an easy environment for installing the needed dependencies for On Demand Runners.

```yaml
description: The official CircleCI CIMG Python Docker image.
docker:
  - image: 'cimg/python:<< parameters.tag >>'
parameters:
  tag:
    default: '3.10'
    description: The `cimg/python` Docker image version tag.
    type: string

```
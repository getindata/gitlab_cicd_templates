# Gitlab CICD templates

The project contains templates for CICD processes implemented in gitlab


## Usag

In `.gitlab-ci.yml` file use following include statement:

```yaml
include:
  - https://raw.githubusercontent.com/getindata/gitlab_cicd_templates/main/dataops/gcp/gcp_setup_template.yml
  - https://raw.githubusercontent.com/getindata/gitlab_cicd_templates/main/dataops/dev_cicd_template.yml
```
# snow-ansible-docs
Documentation for ServiceNow and Ansible integration

To build the documentation, get Antora from <https://antora.org>
and build the docs using following *site.yml*

```YAML

site:
  title: SNOW-Ansible Documentation
  # the 404 page and sitemap files only get generated when the url property is set
  url: https://github.com/davidsvejda/snow-ansible-docs
  start_page: snow-ansible::introduction.adoc
content:
  sources:
  - url: https://github.com/davidsvejda/snow-ansible-docs.git
    branches: master
ui:
  bundle:
    url: https://github.com/davidsvejda/snow-ansible-docs/raw/master/ui-bundle.zip
```

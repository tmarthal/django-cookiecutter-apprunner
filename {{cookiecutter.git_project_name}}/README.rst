=================================
**{{cookiecutter.project_name}}**
=================================

|

**Version = "{{ cookiecutter.version }}"**

|

*{{cookiecutter.project_short_description}}*

|

{%- if cookiecutter.use_repo_status_badge != "n" %}
.. image:: https://www.repostatus.org/badges/latest/{{cookiecutter.use_repo_status_badge}}.svg
   :target: https://www.repostatus.org/#{{cookiecutter.use_repo_status_badge}}
   :alt: Project Status: {{cookiecutter.use_repo_status_badge}}
{%- endif %}



{%- if cookiecutter.open_source_license != "Not open source" %}
:License: {{cookiecutter.open_source_license}}
{%- endif %}















Built with
`Django Cookiecutter <https://github.com/imAsparky/django-cookiecutter>`_

.. image:: docs/images/DIRECT_LOGO.jpeg

DIgital REservoir Characterization Technology DIRECT Consortium Resources for Member Companies
==============================================================================================

Principal Investigators: Prof. Michael J. Pyrcz and Prof. John T. Foster, Collaborating Faculty: Prof. Carlos Torres-Verdin and Prof. Eric van Oort
The University of Texas at Austin

----

{% for _ in cookiecutter.project_name %}={% endfor %}
{{ cookiecutter.project_name }}
{% for _ in cookiecutter.project_name %}={% endfor %}

.. image:: https://github.com/UT-DIRECT/{{ cookiecutter.project_slug }}/actions/workflows/main.yml/badge.svg
        :target: https://github.com/UT-DIRECT/{{ cookiecutter.project_slug }}/actions

{% if is_open_source %}
.. image:: https://readthedocs.org/projects/{{ cookiecutter.project_slug | replace("_", "-") }}/badge/?version=latest
        :target: https://{{ cookiecutter.project_slug | replace("_", "-") }}.readthedocs.io/en/latest/?version=latest
        :alt: Documentation Status
{%- endif %}


{{ cookiecutter.project_short_description }}

{% if is_open_source %}
* Free software: {{ cookiecutter.open_source_license }}
* Documentation: https://{{ cookiecutter.project_slug | replace("_", "-") }}.readthedocs.io.
{% endif %}

Features
--------

* TODO

Recent Presentations
--------

* `2021 DiReCT Annual Review`_

.. _`2021 DiReCT Annual Review`:
   https://github.com/UT-DIRECT/2021-Annual-Review-Presentations/presentations/{{ cookiecutter.project_slug }}.pdf


Credits
-------

This package was created with Cookiecutter_ and the `UT-DIRECT/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`UT-DIRECT/cookiecutter-pypackage`: https://github.com/UT-DIRECT/cookiecutter-pypackage

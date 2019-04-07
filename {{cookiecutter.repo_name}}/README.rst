{{cookiecutter.repo_name}}
{% for _ in cookiecutter.repo_name %}={% endfor %}

.. image:: https://mybinder.org/badge_logo.svg
   :target: https://mybinder.org/v2/gh/{{cookiecutter.github_account}}/{{cookiecutter.repo_name}}/master
   :alt: Launch on Binder


{{cookiecutter.description}}



Credits
-------

This project was created with `Cookiecutter`_ and the `vtkiorg/cookiecutter-vtki-binder`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`vtkiorg/cookiecutter-vtki-binder`: https://github.com/vtkiorg/cookiecutter-vtki-binder

---
ID: {{ cookiecutter.project_id }}
Project_name: {{ cookiecutter.project_name }}
Version: {{ cookiecutter.version }}
---


This directory contains data associated with the project {{ cookiecutter.project_name }}. 

{{ cookiecutter.short_description }}

Data preprocessed by {{ cookiecutter.processed_by }} using {{ cookiecutter.pipeline }}.


Folder structure 
-------

Project_name/
├── README.md
├── Data (symbolic link)
│   ├── raw/
│   └── processed/
├── metadata.yml
└── pipeline.sh

Notes
-------

{{ cookiecutter.notes }}

Contact details
-------

- Contact person: {{ cookiecutter.contact_person }} 
- Contact_email: {{ cookiecutter.contact_email }} 

Credits
-------
This package was created with Cookiecutter and the https://github.com/hds-sandbox/cc-data-template project template.

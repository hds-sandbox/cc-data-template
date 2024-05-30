# cc-data-template
Cookiecutter data template for the workshop. The folder structure (see below) mirrors a dataset folder structure, where both raw and process files are stored, along with the pipeline used to generate them. 

When this template is used, a metadata file will also be generated with the values provided during initialization (you will be asked for details such as the organism, the name of the project, the person responsible, etc.).

Folder structure 
-------
```
Project_name/
├── README.md
├── Data (symbolic link)
│   ├── raw/
│   └── processed/
├── metadata.yml
└── pipeline.sh
```

Do not forget to generate md5sum for the generated data to keep data integrity and collabs can use it to download the files. 


```
fd '(filename.gz|samplesheet.gz)' -x md5sum > chechsum.md5
```


# cc-data-template
Cookiecutter data template for workshop

Do not forget to generate md5sum for the generated data to keep data integrity and collabs can use it to download the files. 


```
fd '(filename.gz|samplesheet.gz)' -x md5sum > chechsum.md5
```
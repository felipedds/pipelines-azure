# Project 1

### Organizing Multiple Pipelines by Folder (Best Practice)
```
Place a separate pipeline YAML file inside each folder of your repo:

/repo
   /service-a
       azure-pipelines-service-a.yml
   /service-b
       azure-pipelines-service-b.yml
   /frontend
       azure-pipelines-frontend.yml
   /database
       azure-pipelines-database.yml
```

### Split work by PROJECT (per product or domain)
```
Organization: felipediasdesouza
    ├── Project: Platform
    ├── Project: MobileApp
    ├── Project: BackendServices
    ├── Project: DataEngineering

```
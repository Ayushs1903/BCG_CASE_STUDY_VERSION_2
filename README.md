# BCG_CASE_STUDY_VERSION_2

### Runbook
Clone the repo and follow these steps:
1. Go to the Project Directory: `$ cd BCG_CASE_STUDY_VERSION_2`
2. On terminal, run `$ make build`. This will build the project to run via spark-submit. In this process a new folder with 
   name "dist" is created, and the code artefacts are copied into it.
3. `$ cd Dist && spark-submit --master "local[*]" --py-files src.zip --files config.yaml main.py && cd ..`

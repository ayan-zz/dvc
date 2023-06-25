DVC------> DATA VERSION CONTROLL
MANAGING LARGE MACHINE LEARNING DATA VERSIONING
REPRODUCIBILITY
EXPERIMENTAL TRACKING
EFFICIENT STORAGE

1. .dvc-->   dvc/cache, dvc/temp, dvc/state
2. dvc.yaml
3. .dvcignore
4. dvc.lock
5. data.dvc---(extension file)
6. .dvcconfig

commands:
1. dvc init
2. dvc add
3. dvc repro --> reproducabilty
4. dvc dag----> stage 02 dependend on stage 01
# We need an abstract class to define all scheduler actions:
## 1. get resource
## 2. release resource
## 3. query resource status
## 4. submit job
## 5. get job
## 6. stop/cancel job
## 7. Filter job

# In first phase, we support slurm and in short future, we need support lsf

# We need also investigate whether k8s is good for us or not for GPU container

# Each scheduler shall be a separate model

# I do not suggest that we consider any configuration, management function of scheduler in the project. If we need, we can design a separate management project
# openshift-ai-model-training-infra

### utilities/minio

minio is used for model and pipeline storage 

### rhoai model registries

the OpenShift AI Model Registry with DB and Server, depends on model storage

### efs

`efs-sc` storage class will be created for training models and logs

### tensorboard

# setup tensorboard as standard depolyment with ingress, depends on efs model training logs


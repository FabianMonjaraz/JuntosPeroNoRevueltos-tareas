## Tarea 3
Descripcion | Comando
|---:|:---|
Listar compute engine | _```gcloud compute instances list```_
Listar Ip's en uso, existentes o reservadas | _```gcloud compute addresses list```_
Listar buckets disponibles | _```gsutil ls```_
Listar Service Accounts existentes en un proyecto | _```gcloud projects get-iam-policy my-project --format json > ~/policy.json```_

## URLS referencias:

* https://cloud.google.com/sdk/gcloud/reference/compute/instances/list
* https://cloud.google.com/sdk/gcloud/reference/compute/addresses/list
* https://cloud.google.com/storage/docs/gsutil?hl=es-419
* https://cloud.google.com/iam/docs/granting-changing-revoking-access?hl=es-419
# minio-object-storage

To use IBM Cloud Private as a object storage provider you can use Minio.

Steps
1. add helm [https://kubernetes-charts.storage.googleapis.com/](https://kubernetes-charts.storage.googleapis.com/) into ICP using menu Manage/Helm Repositories
2. from the Catalog, search for 'Minio'
3. Click on the Minio Helm chart and 'Configure'
4. Specify Release name
5. Choose target namespace
6. Enter 'LoadBalancer' for Service Type
7. To access the Minio browser, from ICP menu, click Network Access/Services, search for the release name you provided in step 4 above.
8. From the Minio Browser, you can create bucket using the '+' floating icon on the bottom right, then you can use it to upload files to the bucket.

Enjoy.

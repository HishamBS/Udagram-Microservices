## Udagram-Microservices

* first i used docker to build the images of the microservices i have using the docker file in each micro service.
* then i pushed the images to my docker hub
```
https://cloud.docker.com/u/h2binseddeq/repository/list
```
* after that i used docker-compose up to run all the images together which worked perfectly.

* then i used the k8s to apply the .yaml files starting with the main one pod.yaml and configured it with aws eks.

* i tested kubectl port-forwarding and it worked and built fine.

* lastly i added travis ci and integrated it with my github repository and it built fine.

```
all related screenshots can be found in the screenshots folder
```



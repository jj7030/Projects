# Python Pod

This simple pod makes use of custom image (alpine + python) which will be pulled from private docker registry using imagePullSecrets.The Pod also makes use of configmap which contains a python file to print hello world.The output can be viewed using kubectl logs.

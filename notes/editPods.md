A Note on Editing Existing Pods
In any of the practical quizzes if you are asked to edit an existing POD, please note the following:

If you are given a pod definition file, edit that file and use it to create a new pod.

If you are not given a pod definition file, you may extract the definition to a file using the below command:

kubectl get pod <pod-name> -o yaml > pod-definition.yaml

Then edit the file to make the necessary changes, delete and re-create the pod.

Use the kubectl edit pod <pod-name> command to edit pod properties.
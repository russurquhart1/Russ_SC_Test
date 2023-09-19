# Debug with Kubectl `exec` Command


The `kubectl exec` command enables you to execute any commands that are installed on your pod. As a debugging action, you can execute any debugging tools installed on your pod. The following procedure shows how to use this command.

:::note
This command requires an active and running Kubernetes namespace.
:::


1. Open a terminal window.

2. For our example, we want to display an `ls` listing of everything in our pod. In the terminal window, enter the following command:

```shell
kubectl exec my-pod -- ls /
```

The system displays a list of all the files and directories on `my-pod`.

:::note
You can only execute commands that are installed on you pod. The `exec` command fails if the called command is not installed on your pod.
:::

Refer to the [Kubernetes documentation reference](https://kubernetes.io/docs/reference/kubectl/cheatsheet/) for more information on this command.


# Debug with Kubectl `logs` Command

The `kubectl logs` command lists all the log files for a specified pod. As a debugging action, you can use this command to gather all the log files, associated with your pod, in order to determine any issues. The following procedure shows how to use this command.

:::note
This command requires an active and running Kubernetes namespace.
:::


1. Open a terminal window.

2. In the terminal window, enter the following command:

```shell
kubectl logs
```

The system displays a list of all the log files associated with the specified pod.

Refer to the [Kubernetes documentation reference](https://kubernetes.io/docs/reference/kubectl/cheatsheet/) for more information on this command.



# Why this fork ?

Because we did not find a better solution to link the lifecycle of sidecars to the main container.

From this repo, we use only the `argoexec` image in our
[Airflow library](https://github.com/nagra-insight/airflow-lib) to kill the sidecars when the "base"
container is exits.

# Building the image

... is as easy as running

```
make dist/argoexec.image
```

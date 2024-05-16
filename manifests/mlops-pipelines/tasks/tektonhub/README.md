# Official TektonHub Artifacts

These are a collection of Tekton artifacts officially sourced from [TektonHub](https://hub.tekton.dev) that are required for our Edge & GitOps workflows.  All of the artifacts under this directory MUST be copied directly from [TektonHub](https://hub.tekton.dev) without any modifications.

## TektonHub Artifacts
You can access TektonHub via the [TektonHub website](https://hub.tekton.dev) OR using [tkn](https://tekton.dev/docs/cli/), the tekton cli.

### Downloading a task using tkn
``` bash
# Get info about the buildah task directly from TektonHub
$ tkn hub info task buildah

# Get the buildah task yaml for application to the server
$ tkn hub get buildah
```

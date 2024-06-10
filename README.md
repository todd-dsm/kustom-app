# kustom-app

This is a simple example of using kustomize to manage multiple environments with overlays. It follows a simple [walk-through].

This walk-through is great but the code didn't age well. This repo is an attempt to correct those issues.

The example is a simple webapp that has a deployment and a service. The deployment is a simple nginx container and the service is a NodePort service that exposes the deployment.

---

Since the original walk-through is quick/simple, it's probably best to:

1. Create your own repo and follow the walk-through
2. ONLY use this repo as a reference for coding differences

The hope of this method would be that you learn everythign from the presenter and only use this to fill in the gaps. No sense in having to learn these thigns twice `;-)`

## Prerequisites

Install the [Kustomize] binary

> *NOTE: If you have 1.21 or above of kubectl you will have access to kubectl kustomize which is the recommended method. If you aren't on version 1.21 or above, upgrade kubectl.*

For the sake of simplicity, just install the binary via Homebrew:

```bash
brew install kustomize
```

## References:

* [Usage]
* [Workflow] for off the shelf applications

<!--- External Refs/Docs -->

[walk-through]:https://youtu.be/spCdNeNCuFU?si=ye4oqCbGkavJ3Gl8
[Kustomize]:https://kubectl.docs.kubernetes.io/installation/kustomize/homebrew/
[Usage]:https://kubectl.docs.kubernetes.io/guides/config_management/offtheshelf/
[Workflow]:https://kubectl.docs.kubernetes.io/guides/config_management/offtheshelf/

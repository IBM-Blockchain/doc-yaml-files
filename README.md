# yaml-files

This repository contains `yaml` files required for deploying IBP.

## Things to update for new releases

### crd-conversion-webhook

* `deployment.yaml`: "ibp-webhook" container image

### operator

* `k8s`
  * `ibp-console/advanced/ibp-console-cluster-resources.yaml`: version
  * `ibp-console/ibp-console-base.yaml`: version
  * `ibp-operator.yaml`: "ibp-operator" container image
* `ocp`
  * `ibp-console/advanced/ibp-console-cluster-resources.yaml`: version
  * `ibp-console/ibp-console-base.yaml`: version
  * `ibp-operator.yaml`: "ibp-operator" container image

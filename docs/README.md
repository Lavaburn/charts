# Usage
* Make changes to the code
* Update version in Chart.yaml
* cd into project root
* `helm dependency update stable/spinnaker`
* `helm package stable/spinnaker`
* `mv *.tgz docs/`
* `cd docs`
* `helm repo index .`

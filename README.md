## Usage

This tugger chart is a kubernetes admission webhook to enforce pulling of docker images from the harbor registry.


```shell
    export CHART_NAME=tugger
    export CHART_REPO_NAME=tugger-chart
    helm repo add $CHART_REPO_NAME https://iits-consulting.github.io/$CHART_REPO_NAME/
    helm search repo $CHART_NAME
    helm install $CHART_NAME $CHART_REPO_NAME/$CHART_NAME
```
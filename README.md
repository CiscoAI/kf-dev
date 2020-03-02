# kf-dev

Kubeflow on a developer machine.

## Installation

```bash
wget -O kind-config.yaml https://raw.githubusercontent.com/CiscoAI/kf-dev/master/kind/kind-config.yaml
kind create cluster \
    --name kf-k8s \
    --config kind-config.yaml
kustomize build github.com/CiscoAI/kf-dev/deploy/kustomize/overlay/kind | kubectl apply -f -
```

## Usage

TODO(swiftdiaries)

## Kubeflow components

- Stable
    - Notebook controller
    - TF Operator
    - PyTorch Operator
- Beta <br>
    - <br>
- Alpha <br>
    - <br>

:zap: :zap: More to be added very soon :zap: :zap:

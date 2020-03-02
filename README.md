# kf-dev

Kubeflow-development for Kubeflow on a dev machine.

## Installation

```bash
git clone https://github.com/CiscoAI/kf-dev
cd kf-dev
kind create cluster \
    --name kf-k8s \
    --config kind/kind-config.yaml
kustomize build deploy/kustomize/overlay/kind | kubectl apply -f -
kustomize build deploy/kustomize/overlay/user/notebook | kubectl apply -f -
```

## Usage

// TBD
Go to [localhost:80](http://localhost:80) on your web browser.

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

# Cloud Native Apps Guideline

What do we mean by Cloud Native Apps?
```
cloud + orchestration + containers
```
These are the main characteristics of these apps:
* **Automatable**. Deployed and managed by machines, instead of humans.
* **Ubiquitous and flexible**. Apps doesn't have to run on any specific machine, they can run in any node without you knowing where they are, only that they are working.
* **Resilient and scalable**. They can be made highly available through redundancy. No single point of failure.
* **Observable**. Observability is a key requirement: monitoring, logging, tracing and metrics.
* **Distributed**. They tend to be composed of multiple, cooperating, distributed microservices.

## Getting Started

You need to install the following tools to follow all the examples in this guide.

We recommend you install [Homebrew](https://brew.sh) package manager on macOS.

###  Docker
1. Run the installation command

###  Kubernetes CLI
1. Run the installation command
```
brew install kubernetes-cli
```
2. Confirm installation
```
kubectl version --client
```

###  Minikube
Run Kubernetes locally
1. Run the installation command
```
brew install minikube
```
2. Start your local k8s cluster
```
minikube start
```
3. Interact with your cluster
```
kubectl version
```

## Deployment

Add additional notes about how to deploy this on a live system

## Contributing

Please read [CONTRIBUTING.md]() for details on our code of conduct, and the process for submitting pull requests to us.

## Contributors

* 

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

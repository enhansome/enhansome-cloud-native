# Awesome Cloud Native with stars

> A curated list of open-source cloud native tools, software, and tutorials.

Cloud Native is a behavior and design philosophy. At its essence, any behavior or approach that improves resource utilization and application delivery efficiency in the cloud is called Cloud Native.

## Table of Contents

* [AI & Machine Learning Platforms](#ai-machine-learning-platforms)
* [API Design & Documentation](#api-design-documentation)
* [API Gateways & Proxies](#api-gateways-proxies)
* [Build & Packaging Automation](#build-packaging-automation)
* [Cluster Provisioning & Lifecycle](#cluster-provisioning-lifecycle)
* [Configuration & Policy Automation](#configuration-policy-automation)
* [Continuous Delivery & GitOps](#continuous-delivery-gitops)
* [Cost & Governance](#cost-governance)
* [Dashboards & Portals](#dashboards-portals)
* [Data Processing & Analytics](#data-processing-analytics)
* [Data Protection & Backup](#data-protection-backup)
* [Databases](#databases)
* [Developer Workspaces & Productivity](#developer-workspaces-productivity)
* [Diagnostics & Troubleshooting](#diagnostics-troubleshooting)
* [Edge & IoT](#edge-iot)
* [Kubernetes Operators](#kubernetes-operators)
* [Load Balancing & Ingress](#load-balancing-ingress)
* [Logging](#logging)
* [Networking & Connectivity](#networking-connectivity)
* [Networking Utilities](#networking-utilities)
* [Observability & Monitoring](#observability-monitoring)
* [Reliability & Chaos Engineering](#reliability-chaos-engineering)
* [RPC Frameworks](#rpc-frameworks)
* [Runtimes & Platforms](#runtimes-platforms)
* [Security & Compliance](#security-compliance)
* [Serverless Platforms](#serverless-platforms)
* [Service Discovery & Registry](#service-discovery-registry)
* [Service Mesh](#service-mesh)
* [Storage & Data Management](#storage-data-management)
* [Streaming & Messaging](#streaming-messaging)
* [Testing & Conformance](#testing-conformance)
* [Tracing & Profiling](#tracing-profiling)
* [Tutorials & Learning](#tutorials-learning)
* [Workload Orchestration & Scheduling](#workload-orchestration-scheduling)

## AI & Machine Learning Platforms

* [tensorflow](https://github.com/tensorflow/tensorflow) ⭐ 197,367 | 🐛 2,935 | 🌐 C++ | 📅 2026-08-23 - Computation using data flow graphs for scalable machine learning.
* [pytorch](https://github.com/pytorch/pytorch) ⭐ 102,551 | 🐛 17,285 | 🌐 Python | 📅 2026-08-23 - Tensors and Dynamic neural networks in Python with strong GPU acceleration.
* [keras](https://github.com/keras-team/keras) ⭐ 64,249 | 🐛 234 | 🌐 Python | 📅 2026-08-21 - Keras is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano.
* [paddlepaddle](https://github.com/PaddlePaddle/Paddle) ⭐ 24,061 | 🐛 1,505 | 🌐 C++ | 📅 2026-08-20 - PArallel Distributed Deep LEarning: Machine Learning Framework from Industrial Practice（『飞桨』核心框架，深度学习&机器学习高性能单机、分布式训练和跨平台部署）.
* [jina](https://github.com/jina-ai/jina) ⭐ 21,863 | 🐛 26 | 🌐 Python | 📅 2025-03-24 - Cloud-native neural search framework for 𝙖𝙣𝙮 kind of data.
* [kubeflow](https://github.com/kubeflow/kubeflow) ⭐ 15,826 | 🐛 0 | 📅 2026-08-21 - Machine Learning Toolkit for Kubernetes.
* [predictionio](https://github.com/apache/predictionio) ⚠️ Archived - PredictionIO, a machine learning server for developers and ML engineers.
* [allennlp](https://github.com/allenai/allennlp) ⚠️ Archived - An open-source NLP research library, built on PyTorch.
* [caffe2](https://github.com/facebookarchive/caffe2) ⚠️ Archived - Caffe2 is a lightweight, modular, and scalable deep learning framework.
* [h2o-3](https://github.com/h2oai/h2o-3) ⭐ 7,495 | 🐛 2,883 | 🌐 Jupyter Notebook | 📅 2026-08-22 - Open Source Fast Scalable Machine Learning API For Smarter Applications (Deep Learning, Gradient Boosting, Random Forest, Generalized Linear Modeling (Logistic Regression, Elastic Net), K-Means, PCA, Stacked Ensembles.)
* [kserve](https://github.com/kserve/kserve) ⭐ 5,819 | 🐛 203 | 🌐 Go | 📅 2026-08-22 - Standardized Serverless ML Inference Platform on Kubernetes.
* [leaf](https://github.com/autumnai/leaf) ⭐ 5,541 | 🐛 32 | 🌐 Rust | 📅 2024-03-20 - Open Machine Intelligence Framework for Hackers. (GPU/CPU).
* [seldon-core](https://github.com/SeldonIO/seldon-core) ⭐ 4,776 | 🐛 396 | 🌐 Go | 📅 2026-03-23 - A framework to deploy, manage and scale your production machine learning to thousands of models.
* [elasticdl](https://github.com/sql-machine-learning/elasticdl) ⭐ 745 | 🐛 89 | 🌐 Python | 📅 2024-01-26 - Kubernetes-native Deep Learning Framework.
* [kubedl](https://github.com/kubedl-io/kubedl) ⭐ 531 | 🐛 62 | 🌐 Go | 📅 2024-03-04 - Run your deep learning workloads on Kubernetes more easily and efficiently.

## Data Processing & Analytics

* [pachyderm](https://github.com/pachyderm/pachyderm) ⭐ 6,308 | 🐛 940 | 🌐 Go | 📅 2025-02-03 - Reproducible Data Science at Scale!
* [sqlflow](https://github.com/sql-machine-learning/sqlflow) ⭐ 5,189 | 🐛 250 | 🌐 Go | 📅 2024-04-18 - Brings SQL and AI together.
* [fast-data-dev](https://github.com/lensesio/fast-data-dev) ⭐ 2,079 | 🐛 81 | 🌐 Shell | 📅 2025-11-20 - Kafka Docker for development. Kafka, Zookeeper, Schema Registry, Kafka-Connect, Landoop Tools, 20+ connectors.
* [wallaroo](https://github.com/WallarooLabs/wallaroo) ⭐ 1,482 | 🐛 348 | 🌐 Pony | 📅 2021-04-06 - Ultrafast and elastic data processing.
* [v6d](https://github.com/alibaba/v6d) ⭐ 962 | 🐛 127 | 🌐 C++ | 📅 2026-01-22 - vineyard (v6d), an in-memory immutable data manager.
* [spark](https://github.com/apache-spark-on-k8s/spark) ⚠️ Archived - Apache Spark enhanced with native Kubernetes scheduler back-end.
* [spark-on-kubernetes-helm](https://github.com/jahstreet/spark-on-kubernetes-helm) ⭐ 202 | 🐛 21 | 🌐 Mustache | 📅 2022-10-20 - Spark on Kubernetes infrastructure Helm charts repo.

## API Gateways & Proxies

* [litellm](https://github.com/BerriAI/litellm) ⭐ 57,060 | 🐛 4,905 | 🌐 Python | 📅 2026-08-23 - Python SDK, Proxy Server (LLM Gateway) to call 100+ LLM APIs in OpenAI format - \[Bedrock, Azure, OpenAI, VertexAI, Cohere, Anthropic, Sagemaker, HuggingFace, Replicate, Groq].
* [kong](https://github.com/Kong/kong) ⭐ 44,025 | 🐛 190 | 🌐 Lua | 📅 2026-08-16 - The Microservice API Gateway.
* [apisix](https://github.com/apache/apisix) ⭐ 17,019 | 🐛 253 | 🌐 Lua | 📅 2026-08-20 - The Cloud-Native API Gateway.
* [tyk](https://github.com/TykTechnologies/tyk) ⭐ 10,797 | 🐛 497 | 🌐 Go | 📅 2026-08-23 - Tyk Open Source API Gateway written in Go, supporting REST, GraphQL, TCP and gRPC protocols.
* [higress](https://github.com/alibaba/higress) ⭐ 9,164 | 🐛 1,069 | 🌐 Go | 📅 2026-08-20 - Next-generation Cloud Native Gateway.
* [ocelot](https://github.com/ThreeMammals/Ocelot) ⭐ 8,716 | 🐛 61 | 🌐 C# | 📅 2026-08-21 - .NET core API Gateway.
* [lura](https://github.com/luraproject/lura) ⭐ 6,787 | 🐛 12 | 🌐 Go | 📅 2026-08-18 - Ultra performant API Gateway with middlewares. A project hosted at The Linux Foundation.
* [easegress](https://github.com/megaease/easegress) ⭐ 5,868 | 🐛 10 | 🌐 Go | 📅 2026-07-20 - A Cloud Native traffic orchestration system.
* [emissary-gateway](https://github.com/emissary-ingress/emissary) ⭐ 4,519 | 🐛 439 | 🌐 Python | 📅 2026-08-19 - Open source Kubernetes-native API gateway for microservices built on the Envoy Proxy.
* [express-gateway](https://github.com/ExpressGateway/express-gateway) ⭐ 3,031 | 🐛 78 | 🌐 JavaScript | 📅 2024-05-14 - A microservices API Gateway built on top of ExpressJS.
* [gateway](https://github.com/envoyproxy/gateway) ⭐ 2,973 | 🐛 764 | 🌐 Go | 📅 2026-08-21 - Manages Envoy Proxy as a standalone or Kubernetes-based application gateway.
* [orange](https://github.com/orlabs/orange) ⭐ 2,308 | 🐛 77 | 🌐 Lua | 📅 2023-08-25 - OpenResty/Nginx Gateway for API Monitoring and Management.
* [bricksllm](https://github.com/bricks-cloud/BricksLLM) ⭐ 1,226 | 🐛 21 | 🌐 Go | 📅 2025-01-05 - Enterprise-grade API gateway that helps you monitor and impose cost or rate limits per API key. Get fine-grained access control and monitoring per user, application, or environment. Supports OpenAI, Azure OpenAI, Anthropic, vLLM, and open-source LLMs.
* [haproxy-ingress](https://github.com/jcmoraisjr/haproxy-ingress) ⭐ 1,163 | 🐛 80 | 🌐 Go | 📅 2026-08-18 - HaProxy Ingress.
* [nginx-gateway-fabric](https://github.com/nginxinc/nginx-gateway-fabric) ⭐ 1,145 | 🐛 109 | 🌐 Go | 📅 2026-08-22 - NGINX Gateway Fabric provides an implementation for the Gateway API using NGINX as the data plane.
* [hango-gateway](https://github.com/hango-io/hango-gateway) ⭐ 459 | 🐛 18 | 🌐 Python | 📅 2023-12-14 - Hango API Gateway, build on Envoy & Istio.
* [batch-processing-gateway](https://github.com/apple/batch-processing-gateway) ⭐ 222 | 🐛 4 | 🌐 Java | 📅 2026-05-06 - The gateway component to make Spark on K8s much easier for Spark users.
* [gloo](https://github.com/solo-io/gloo) ⭐ 170 | 🐛 1,867 | 🌐 Go | 📅 2026-08-21 - The Feature-rich, Kubernetes-native, Next-Generation API Gateway Built on Envoy.
* [alb](https://github.com/alauda/alb) ⭐ 68 | 🐛 0 | 🌐 Go | 📅 2025-09-01 - ALB (Another Load Balancer) is a Kubernetes Gateway powered by OpenResty with years of production experience from Alauda.
* [sbproxy](https://github.com/soapbucket/sbproxy) ⭐ 50 | 🐛 1 | 🌐 Rust | 📅 2026-08-23 - Single-binary AI gateway and reverse proxy with 103+ LLM providers, cost-based routing, rate limiting, and declarative YAML configuration.

## Continuous Delivery & GitOps

* [terraform](https://github.com/hashicorp/terraform) ⭐ 49,513 | 🐛 1,915 | 🌐 Go | 📅 2026-08-21 - Terraform is a tool for building, changing, and combining infrastructure safely and efficiently.
* [drone](https://github.com/drone/drone) ⭐ 38,087 | 🐛 107 | 🌐 Go | 📅 2026-08-21 - Drone is a Continuous Delivery platform built on Docker, written in Go.
* [helm](https://github.com/helm/helm) ⭐ 30,165 | 🐛 449 | 🌐 Go | 📅 2026-08-23 - The Kubernetes Package Manager.
* [opentofu](https://github.com/opentofu/opentofu) ⭐ 29,872 | 🐛 325 | 🌐 Go | 📅 2026-08-22 - OpenTofu lets you declaratively manage your cloud infrastructure.
* [jenkins](https://github.com/jenkinsci/jenkins) ⭐ 26,481 | 🐛 3,614 | 🌐 Java | 📅 2026-08-23 - Jenkins automation server.
* [pulumi](https://github.com/pulumi/pulumi) ⭐ 25,602 | 🐛 2,450 | 🌐 Go | 📅 2026-08-22 - A multi-language, multi-cloud development platform -- your code, your cloud, your team.
* [argo-cd](https://github.com/argoproj/argo-cd/) ⭐ 23,976 | 🐛 4,386 | 🌐 Go | 📅 2026-08-23 - Declarative continuous deployment for Kubernetes.
* [argo](https://github.com/argoproj/argo) ⭐ 16,927 | 🐛 1,267 | 🌐 Go | 📅 2026-08-21 - Get stuff done with container-native workflows for Kubernetes.
* [dagger](https://github.com/dagger/dagger) ⭐ 16,194 | 🐛 142 | 🌐 Go | 📅 2026-08-22 - A programmable CI/CD engine that runs your pipelines in containers.
* [skaffold](https://github.com/GoogleContainerTools/skaffold) ⭐ 15,889 | 🐛 907 | 🌐 Go | 📅 2026-08-20 - Easy and Repeatable Kubernetes Development.
* [kaniko](https://github.com/GoogleContainerTools/kaniko) ⚠️ Archived - Build Container Images In Kubernetes.
* [jib](https://github.com/GoogleContainerTools/jib) ⭐ 14,440 | 🐛 251 | 🌐 Java | 📅 2026-07-15 - Build container images for your Java applications.
* [kustomize](https://github.com/kubernetes-sigs/kustomize) ⭐ 12,142 | 🐛 196 | 🌐 Go | 📅 2026-08-20 - Customization of kubernetes YAML configurations.
* [crossplane](https://github.com/crossplane/crossplane) ⭐ 11,967 | 🐛 188 | 🌐 Go | 📅 2026-08-22 - An Open Source Multicloud Control Plane.
* [meshery](https://github.com/meshery/meshery) ⭐ 11,554 | 🐛 1,823 | 🌐 TypeScript | 📅 2026-08-23 - A open source cloud native manager that enables the design and management of all Kubernetes-based infrastructure and applications (multi-cloud).
* [kompose](https://github.com/kubernetes/kompose) ⭐ 10,609 | 🐛 20 | 🌐 Go | 📅 2026-06-15 - Go from Docker Compose to Kubernetes.
* [tilt](https://github.com/tilt-dev/tilt) ⭐ 10,014 | 🐛 510 | 🌐 Go | 📅 2026-08-15 - A multi-service dev environment for teams on Kubernetes.
* [spinnaker](https://github.com/spinnaker/spinnaker) ⭐ 9,772 | 🐛 106 | 🌐 Java | 📅 2026-08-22 - Spinnaker is an open source, multi-cloud continuous delivery platform for releasing software changes with high velocity and confidence.
* [pipeline](https://github.com/tektoncd/pipeline) ⭐ 9,040 | 🐛 559 | 🌐 Go | 📅 2026-08-22 - A cloud-native Pipeline resource.
* [ko](https://github.com/ko-build/ko) ⭐ 8,503 | 🐛 58 | 🌐 Go | 📅 2026-08-20 - Build and deploy Go applications on Kubernetes.
* [spec](https://github.com/score-spec/spec) ⭐ 8,084 | 🐛 12 | 🌐 Makefile | 📅 2026-07-27 - The score specification file.
* [kubevela](https://github.com/oam-dev/kubevela) ⭐ 7,883 | 🐛 273 | 🌐 Go | 📅 2026-08-21 - Make shipping applications more enjoyable.
* [woodpecker](https://github.com/laszlocph/woodpecker) ⭐ 7,733 | 🐛 360 | 🌐 Go | 📅 2026-08-23 - Fork of drone.io v0.8 since drone is not fully opensource anymore.
* [jsonnet](https://github.com/google/jsonnet) ⭐ 7,559 | 🐛 210 | 🌐 Jsonnet | 📅 2026-03-30 - Jsonnet - The data templating language.
* [flux](https://github.com/fluxcd/flux) ⚠️ Archived - A tool for turning container images into running Kubernetes services.
* [helm-dashboard](https://github.com/komodorio/helm-dashboard) ⭐ 5,746 | 🐛 19 | 🌐 TypeScript | 📅 2026-08-10 - The missing UI for Helm - visualize your releases.
* [devtron](https://github.com/devtron-labs/devtron) ⭐ 5,586 | 🐛 764 | 🌐 Go | 📅 2026-08-21 - Software Delivery Workflow For Kubernetes
* [wing](https://github.com/winglang/wing) ⭐ 5,396 | 🐛 898 | 🌐 TypeScript | 📅 2026-06-12 - A cloud-oriented programming language that allows developers to build distributed systems, leveraging cloud services as first-class citizens.
* [flagger](https://github.com/weaveworks/flagger) ⭐ 5,393 | 🐛 384 | 🌐 Go | 📅 2026-08-17 - Progressive delivery Kubernetes operator (Canary, A/B Testing and Blue/Green deployments) .
* [kubeapps](https://github.com/kubeapps/kubeapps) ⚠️ Archived - A web-based UI for deploying and managing applications in Kubernetes clusters.
* [cdk8s](https://github.com/awslabs/cdk8s) ⭐ 4,850 | 🐛 77 | 🌐 JavaScript | 📅 2026-08-23 - Define Kubernetes native apps and abstractions using object-oriented programming.
* [cds](https://github.com/ovh/cds) ⭐ 4,836 | 🐛 160 | 🌐 Go | 📅 2026-08-21 - Enterprise-Grade Continuous Delivery & DevOps Automation Open Source Platform.
* [waypoint](https://github.com/hashicorp/waypoint) ⚠️ Archived - A tool to build, deploy, and release any application on any platform.
* [werf](https://github.com/werf/werf) ⭐ 4,717 | 🐛 27 | 🌐 Go | 📅 2026-08-20 - The CLI tool gluing Git, Docker, Helm, and Kubernetes with any CI system to implement CI/CD and Giterminism.
* [jx](https://github.com/jenkins-x/jx) ⭐ 4,688 | 🐛 147 | 🌐 Go | 📅 2026-08-10 - A command line tool for installing and working with Jenkins X.
* [arkade](https://github.com/alexellis/arkade) ⭐ 4,607 | 🐛 14 | 🌐 Go | 📅 2026-08-22 - Kubernetes apps for developers.
* [helmfile](https://github.com/roboll/helmfile) ⭐ 4,033 | 🐛 527 | 🌐 Go | 📅 2023-04-27 - Deploy Kubernetes Helm Charts.
* [gitkube](https://github.com/hasura/gitkube) ⭐ 3,847 | 🐛 44 | 🌐 Go | 📅 2023-08-31 - Gitkube: Build and deploy docker images to Kubernetes using git push.
* [ballerina-lang](https://github.com/ballerina-platform/ballerina-lang) ⭐ 3,846 | 🐛 1,601 | 🌐 Ballerina | 📅 2026-08-14 - Ballerina is a new programming language for integration built on a sequence diagram metaphor.
* [hygieia](https://github.com/Hygieia/Hygieia) ⚠️ Archived - CapitalOne DevOps Dashboard.
* [spegel](https://github.com/spegel-org/spegel) ⭐ 3,747 | 🐛 20 | 🌐 Go | 📅 2026-08-21 - Stateless cluster local OCI registry mirror.
* [garden](https://github.com/garden-io/garden) ⭐ 3,608 | 🐛 246 | 🌐 TypeScript | 📅 2026-06-11 - Development orchestrator for Kubernetes, containers and serverless functions.
* [kargo](https://github.com/akuity/kargo) ⭐ 3,589 | 🐛 183 | 🌐 Go | 📅 2026-08-23 - Application lifecycle orchestration.
* [argo-rollouts](https://github.com/argoproj/argo-rollouts) ⭐ 3,560 | 🐛 659 | 🌐 Go | 📅 2026-08-21 - Progressive delivery controller for blue-green, canary, and experiments on Kubernetes.
* [zadig](https://github.com/koderover/zadig) ⭐ 3,232 | 🐛 32 | 🌐 Go | 📅 2026-08-21 - Zadig is a cloud native, distributed, developer-oriented continuous delivery product.
* [spec](https://github.com/oam-dev/spec) ⭐ 3,173 | 🐛 114 | 📅 2026-08-21 - The Open Application Model specification.
* [cue](https://github.com/cuelang/cue) ⚠️ Archived - Validate and define text-based and dynamic configuration.
* [erda](https://github.com/erda-project/erda) ⭐ 2,750 | 🐛 10 | 🌐 Go | 📅 2026-08-20 - An enterprise-grade application building, deploying, monitoring platform (An iPaaS).
* [binderhub](https://github.com/jupyterhub/binderhub) ⭐ 2,669 | 🐛 269 | 🌐 Python | 📅 2026-08-05 - Run your code in the cloud, with technology so advanced, it feels like magic!
* [source-to-image](https://github.com/openshift/source-to-image) ⭐ 2,543 | 🐛 26 | 🌐 Go | 📅 2026-08-23 - A tool for building/building artifacts from source and injecting into docker images.
* [kcl](https://github.com/kcl-lang/kcl) ⭐ 2,400 | 🐛 93 | 🌐 Rust | 📅 2026-08-16 - KCL is a constraint-based record & functional language mainly used in configuration and policy scenarios. (CNCF Sandbox Project).
* [sealer](https://github.com/alibaba/sealer) ⭐ 2,096 | 🐛 228 | 🌐 Go | 📅 2025-06-03 - Seal your applications all dependencies and kubernetes into CloudImage! Build Deliver and Run user-defined clusters in one command.
* [hub](https://github.com/artifacthub/hub) ⭐ 2,077 | 🐛 29 | 🌐 TypeScript | 📅 2026-07-07 - Find, install and publish Cloud Native packages
* [timoni](https://github.com/stefanprodan/timoni) ⭐ 2,003 | 🐛 33 | 🌐 Go | 📅 2026-08-22 - Timoni is a package manager for Kubernetes, powered by CUE and inspired by Helm.
* [cloudbase-framework](https://github.com/Tencent/cloudbase-framework) ⚠️ Archived - 🚀 A front-end and back-end integrated deployment tool 🔥 One-click deploy to serverless architecture. 云原生一体化部署工具 CloudBase Framework.
* [kpt](https://github.com/GoogleContainerTools/kpt) ⭐ 1,890 | 🐛 347 | 🌐 Go | 📅 2026-08-20 - Kpt is a toolkit to help you manage, manipulate, customize, and apply Kubernetes Resource configuration data files.
* [keptn](https://github.com/keptn/keptn) ⚠️ Archived - Keptn is a control-plane for continuous delivery and operations enable cloud-native applications to run autonomously.
* [fabric8](https://github.com/fabric8io/fabric8) ⚠️ Archived - fabric8 is an open source microservices platform based on Docker, Kubernetes and Jenkins.
* [radius](https://github.com/radius-project/radius) ⭐ 1,662 | 🐛 316 | 🌐 Go | 📅 2026-08-23 - Radius is a cloud-native, portable application platform that makes app development easier for teams building cloud-native apps.
* [lastbackend](https://github.com/lastbackend/lastbackend) ⭐ 1,656 | 🐛 9 | 🌐 Go | 📅 2023-07-19 - Container orchestration with CI\&CD, cli and amazing UI.
* [pipeline](https://github.com/banzaicloud/pipeline) ⭐ 1,505 | 🐛 128 | 🌐 Go | 📅 2023-11-24 - REST API to provision or reuse managed Kubernetes clusters in the cloud and deploy cloud native apps.
* [helmsman](https://github.com/Praqma/helmsman) ⭐ 1,495 | 🐛 2 | 🌐 Go | 📅 2026-08-16 - Helm Charts as Code.
* [tenv](https://github.com/tofuutils/tenv) ⭐ 1,430 | 🐛 45 | 🌐 Go | 📅 2026-08-20 - OpenTofu / Terraform / Terragrunt and Atmos version manager.
* [krane](https://github.com/Shopify/krane) ⭐ 1,417 | 🐛 68 | 🌐 Ruby | 📅 2026-02-18 - A command-line tool that helps you ship changes to a Kubernetes namespace and understand the result.
* [habitus](https://github.com/cloud66-oss/habitus) ⭐ 1,399 | 🐛 8 | 🌐 Go | 📅 2020-02-05 - A build flow tool for Docker.
* [monday](https://github.com/eko/monday) ⭐ 1,377 | 🐛 7 | 🌐 Go | 📅 2026-07-08 - A dev tool for microservice developers that run local applications and/or forward some others from Kubernetes or over SSH.
* [pipecd](https://github.com/pipe-cd/pipecd) ⭐ 1,345 | 🐛 209 | 🌐 Go | 📅 2026-08-23 - The One CD for All {applications, platforms, operations} - Complete and unified CD to deploy any application to any platform
* [kusion](https://github.com/KusionStack/kusion) ⭐ 1,316 | 🐛 54 | 🌐 Go | 📅 2026-08-22 - A compile-to-cloud technology stack with tool chains and engine.
* [kenyata](https://github.com/spinnaker/kayenta) ⚠️ Archived - Automated Canary Service.
* [klotho](https://github.com/klothoplatform/klotho) ⭐ 1,146 | 🐛 170 | 🌐 Go | 📅 2026-01-21 - Write AWS applications at lightning speed.
* [kapp](https://github.com/carvel-dev/kapp) ⭐ 1,074 | 🐛 129 | 🌐 Go | 📅 2026-08-17 - kapp is a simple deployment tool focused on the concept of "Kubernetes application" — a set of resources with the same label.
* [cyclone](https://github.com/caicloud/cyclone) ⭐ 1,065 | 🐛 44 | 🌐 Go | 📅 2023-10-24 - Powerful workflow engine and end-to-end pipeline solutions implemented with native Kubernetes resources.
* [screwdriver](https://github.com/screwdriver-cd/screwdriver) ⭐ 1,044 | 🐛 55 | 🌐 JavaScript | 📅 2026-08-21 - An open source build platform designed for continuous delivery.
* [cnab-spec](https://github.com/cnabio/cnab-spec) ⭐ 972 | 🐛 31 | 🌐 Shell | 📅 2022-09-09 - Cloud Native Application Bundle Specification.
* [couler](https://github.com/couler-proj/couler) ⭐ 943 | 🐛 21 | 🌐 Python | 📅 2024-10-08 - Unified Interface for Constructing and Managing Workflows
* [devstream](https://github.com/devstream-io/devstream) ⭐ 876 | 🐛 3 | 🌐 Python | 📅 2025-03-12 - DevStream: the open-source DevOps toolchain manager (DTM).
* [crane](https://github.com/Dataman-Cloud/crane) ⭐ 750 | 🐛 16 | 🌐 Go | 📅 2023-08-31 - Yet another control plane based on docker built-in swarmkit.
* [gockerize](https://github.com/redbooth/gockerize) ⭐ 667 | 🐛 0 | 🌐 Shell | 📅 2018-03-02 - Package golang service into minimal docker containers.
* [draft](https://github.com/azure/draft) ⭐ 642 | 🐛 24 | 🌐 Go | 📅 2026-08-07 - A tool for developers to create cloud-native applications on Kubernetes.
* [smith](https://github.com/oracle/Smith) ⚠️ Archived - Smith: A microcontainer builder.
* [build](https://github.com/knative/build) ⚠️ Archived - A Kubernetes-native Build resource.
* [hyscale](https://github.com/hyscale/hyscale) ⭐ 446 | 🐛 15 | 🌐 Java | 📅 2023-03-30 - All things HyScale.
* [move2kube](https://github.com/konveyor/move2kube) ⭐ 412 | 🐛 55 | 🌐 Go | 📅 2025-03-06 - A tool to help users migrate their apps from legacy platforms like Cloud Foundry to Kubernetes and Openshift. Analyses the application source code and generates Kubernetes YAMLs, Helm Charts, Tekton Pipelines, etc. The analysis and generation can be heavily customized to produce the exact output that you want.
* [carvel](https://github.com/carvel-dev/carvel) ⭐ 408 | 🐛 86 | 🌐 HTML | 📅 2026-07-16 - Carvel provides a set of reliable, single-purpose, composable tools that aid in your application building, configuration, and deployment to Kubernetes. This repo contains information regarding the Carvel open-source community.
* [mkit](https://github.com/darkbitio/mkit) ⚠️ Archived - MKIT is a Managed Kubernetes Inspection Tool that validates several common security-related configuration settings of managed Kubernetes cluster objects and the workloads/resources running inside the cluster.
* [containerops](https://github.com/Huawei/containerops) ⭐ 339 | 🐛 2 | 🌐 Go | 📅 2022-05-31 - DevOps Orchestration Platform.
* [kedge](https://github.com/kedgeproject/kedge) ⚠️ Archived - Kedge - Concise Application Definition for Kubernetes.
* [charitify](https://github.com/kubepack/chartify) ⭐ 231 | 🐛 12 | 🌐 Go | 📅 2020-02-19 - Generate Helm Charts from Kubernetes objects.
* [qbec](https://github.com/splunk/qbec) ⭐ 190 | 🐛 42 | 🌐 Go | 📅 2026-07-10 - Configure kubernetes objects on multiple clusters using jsonnet.
* [hiboot](https://github.com/hidevopsio/hiboot) ⭐ 179 | 🐛 2 | 🌐 Go | 📅 2026-06-08 - Hiboot is a high performance web and cli application framework with dependency injection support.
* [cross-cloud](https://github.com/crosscloudci/cross-cloud) ⭐ 169 | 🐛 40 | 🌐 Shell | 📅 2021-04-26 - Cross Cloud Continuous Integration.
* [beetle](https://github.com/Clivern/Beetle) ⭐ 167 | 🐛 16 | 🌐 Go | 📅 2026-08-22 - Kubernetes multi-cluster deployment automation service.
* [autoapply](https://github.com/autoapply/autoapply) ⭐ 157 | 🐛 12 | 🌐 JavaScript | 📅 2025-11-14 - Automatically apply changes from a git repository to Kubernetes.
* [commandeer](https://github.com/commandeer/open) ⭐ 148 | 🐛 100 | 🌐 JavaScript | 📅 2023-03-06 - Cloud management desktop app for macOS, Windows, and Linux.
* [kubegen](https://github.com/errordeveloper/kubegen) ⭐ 135 | 🐛 17 | 🌐 Go | 📅 2018-06-01 - Kubegen – simple way to describe Kubernetes resources.
* [heighliner](https://github.com/h8r-dev/heighliner) ⭐ 133 | 🐛 0 | 🌐 Go | 📅 2022-07-15 - An app development platform using cloud native stacks.
* [conveyor](https://github.com/open-ug/conveyor) ⭐ 117 | 🐛 6 | 🌐 Go | 📅 2026-08-23 - Conveyor CI is an extensible Software Framework/Engine for building CI/CD Platforms.
* [kd](https://github.com/UKHomeOffice/kd) ⭐ 90 | 🐛 18 | 🌐 Go | 📅 2025-11-07 - Minimalistic kubernetes resources deployment tool with templating.
* [capact](https://github.com/capactio/capact) ⭐ 79 | 🐛 71 | 🌐 Go | 📅 2025-11-03 - A framework to manage applications and infrastructure in a unified way.
* [armada](https://github.com/att-comdev/armada) ⚠️ Archived - A python orchestrator for a installing, upgrading, and managing a collection of helm charts, dependencies, and values overrides.
* [opencompose](https://github.com/redhat-developer/opencompose) ⭐ 65 | 🐛 47 | 🌐 Go | 📅 2017-08-14 - A higher level abstraction for Kubernetes Resource.
* [kdo](https://github.com/stepro/kdo) ⭐ 64 | 🐛 8 | 🌐 Go | 📅 2026-01-30 - Deployless Development on Kubernetes.
* [helm-kanvas-snapshot](https://github.com/meshery/helm-kanvas-snapshot) ⭐ 45 | 🐛 13 | 🌐 Go | 📅 2026-08-06 - A Plugin that generates a visual snapshot of Helm charts.
* [qovery](https://github.com/Qovery/qovery-skills) ⭐ 9 | 🐛 3 | 🌐 Shell | 📅 2026-08-21 - Enterprise Kubernetes management platform for deploying applications, databases, Helm charts, and Terraform modules on AWS, GCP, Azure, and Scaleway. Includes Terraform provider, CLI, API, and AI Agent Skill.
* [circleci](https://github.com/circleci) - Continuous Integration and Deployment.
* [kismatic](https://github.com/apprenda/kismatic) - Kismatic Enterprise Toolkit: Fully-Automated, Production-Grade Kubernetes Operations.
* [wercker](https://github.com/wercker/wercker) - The Wercker CLI can be used to execute pipelines locally for both local development and easy introspection.

## Build & Packaging Automation

* [packer](https://github.com/hashicorp/packer) ⭐ 15,762 | 🐛 317 | 🌐 Go | 📅 2026-08-23 - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
* [tini](https://github.com/krallin/tini) ⭐ 11,218 | 🐛 45 | 🌐 C | 📅 2025-05-08 - A tiny but valid `init` for containers.
* [skopeo](https://github.com/containers/skopeo) ⭐ 11,184 | 🐛 87 | 🌐 Go | 📅 2026-08-20 - Work with remote images registries - retrieving information, images, signing content.
* [buildx](https://github.com/docker/buildx) ⭐ 4,486 | 🐛 388 | 🌐 Go | 📅 2026-08-20 - Docker CLI plugin for extended build capabilities with BuildKit.
* [container-structure-test](https://github.com/GoogleContainerTools/container-structure-test) ⭐ 2,495 | 🐛 116 | 🌐 Go | 📅 2026-07-20 - Validate the structure of your container images.
* [docker-wine](https://github.com/scottyhardy/docker-wine) ⭐ 1,523 | 🐛 55 | 🌐 Shell | 📅 2025-05-29 - Docker image that includes Wine and Winetricks for running Windows applications on Linux and macOS.
* [dockerized](https://github.com/datastack-net/dockerized) ⭐ 1,270 | 🐛 8 | 🌐 Go | 📅 2023-08-31 - Run popular commandline tools within docker.
* [kpack](https://github.com/pivotal/kpack) ⭐ 1,081 | 🐛 116 | 🌐 Go | 📅 2026-08-17 - Kubernetes Native Container Build Service.
* [docker-pushrm](https://github.com/christian-korneck/docker-pushrm) ⭐ 152 | 🐛 6 | 🌐 Go | 📅 2024-06-10 - A Docker CLI plugin that that lets you push the README.md file from the current directory to Docker Hub. Also supports Quay and Harbor.
* [kuberlr](https://github.com/flavio/kuberlr) ⭐ 142 | 🐛 13 | 🌐 Go | 📅 2026-08-10 - A tool that simplifies the management of multiple versions of kubectl.
* [watchtower](https://github.com/openserbia/watchtower) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2026-08-20 - Automatically update running Docker containers.

## Configuration & Policy Automation

* [ansible](https://github.com/ansible/ansible) ⭐ 70,438 | 🐛 838 | 🌐 Python | 📅 2026-08-19 - Ansible is a radically simple IT automation platform that makes your applications and systems easier to deploy. Avoid writing scripts or custom code to deploy and update your applications — automate in a language that approaches plain English, using SSH, with no agents to install on remote systems.
* [unleash](https://github.com/Unleash/unleash) ⭐ 13,750 | 🐛 57 | 🌐 TypeScript | 📅 2026-08-21 - Open-source feature management platform to decouple deploy from release and enable continuous delivery safely.
* [reloader](https://github.com/stakater/Reloader) ⭐ 10,352 | 🐛 164 | 🌐 Go | 📅 2026-08-23 - A Kubernetes controller to watch changes in ConfigMap and Secrets and do rolling upgrades on Pods with their associated Deployment, StatefulSet, DaemonSet and DeploymentConfig.
* [datree](https://github.com/datreeio/datree) ⚠️ Archived - CLI tool that automatically scans Kubernetes manifests and Helm charts to ensure they follow best practices as well as your organization’s policies.
* [gatekeeper](https://github.com/open-policy-agent/gatekeeper) ⭐ 4,267 | 🐛 178 | 🌐 Go | 📅 2026-08-21 - Enforce Kubernetes admission policies using Open Policy Agent constraints.
* [kube-linter](https://github.com/stackrox/kube-linter) ⭐ 3,501 | 🐛 91 | 🌐 Go | 📅 2026-08-19 - KubeLinter is a static analysis tool that checks Kubernetes YAML files and Helm charts to ensure the applications represented in them adhere to best practices.
* [pluto](https://github.com/FairwindsOps/pluto) ⭐ 2,569 | 🐛 12 | 🌐 Go | 📅 2026-08-21 - A cli tool to help discover deprecated apiVersions in Kubernetes.
* [kapitan](https://github.com/kapicorp/kapitan) ⭐ 1,925 | 🐛 153 | 🌐 Python | 📅 2026-08-09 - Inventory-driven configuration generator for Kubernetes and infrastructure, using Jsonnet, Jinja2, Kadet, Helm, Kustomize, and CUE inputs.
* [container-transform](https://github.com/micahhausler/container-transform) ⭐ 1,411 | 🐛 29 | 🌐 Python | 📅 2020-05-11 - Transforms docker-compose, ECS, and Marathon configurations.
* [openfeature](https://github.com/open-feature/spec) ⭐ 1,241 | 🐛 38 | 🌐 Python | 📅 2026-08-22 - Vendor-neutral feature flag standard and SDKs for cloud native apps.
* [ksonnet](https://github.com/ksonnet/ksonnet) ⚠️ Archived - A CLI-supported framework that streamlines writing and deployment of Kubernetes configurations to multiple clusters.
* [kubecfg](https://github.com/bitnami/kubecfg) ⚠️ Archived - A tool for managing complex enterprise Kubernetes environments as code.
* [ksonnet-lib](https://github.com/ksonnet/ksonnet-lib) ⚠️ Archived - (technical preview) Simplify working with Kubernetes.
* [microconfig](https://github.com/microconfig/microconfig) ⭐ 320 | 🐛 0 | 🌐 Java | 📅 2024-11-27 - Modern and simple way of microservice configuration management.
* [kubewarden](https://github.com/kubewarden/kubewarden-controller) ⭐ 233 | 🐛 143 | 🌐 Rust | 📅 2026-08-23 - Policy as code for Kubernetes powered by WebAssembly modules.
* [ktmpl](https://github.com/InQuicker/ktmpl) ⭐ 152 | 🐛 8 | 🌐 Rust | 📅 2017-10-20 - Parameterized templates for Kubernetes manifests.
* [kcg](https://github.com/bit-cloner/kcg) ⭐ 19 | 🐛 1 | 🌐 Go | 📅 2021-04-29 - Kubernetes config generator.

## Cluster Provisioning & Lifecycle

* [minikube](https://github.com/kubernetes/minikube) ⭐ 32,051 | 🐛 540 | 🌐 Go | 📅 2026-08-23 - Run Kubernetes locally.
* [vagrant](https://github.com/hashicorp/vagrant) ⭐ 27,199 | 🐛 753 | 🌐 Ruby | 📅 2026-08-03 - Vagrant is a tool for building and distributing development environments.
* [kubespray](https://github.com/kubernetes-sigs/kubespray) ⭐ 18,701 | 🐛 201 | 🌐 Jinja | 📅 2026-08-21 - Setup a kubernetes cluster also mentioned as kargo.
* [sealos](https://github.com/labring/sealos) ⭐ 18,316 | 🐛 98 | 🌐 TypeScript | 📅 2026-08-21 - Sealos is a Kubernetes distribution offering comprehensive solutions for both public and private clouds.
* [kops](https://github.com/kubernetes/kops) ⭐ 16,667 | 🐛 131 | 🌐 Go | 📅 2026-08-23 - Kubernetes Operations (kops) - Production Grade K8s Installation, Upgrades, and Management.
* [kind](https://github.com/kubernetes-sigs/kind) ⭐ 15,440 | 🐛 243 | 🌐 Go | 📅 2026-08-21 - Kubernetes IN Docker - local clusters for testing Kubernetes.
* [kubeasz](https://github.com/easzlab/kubeasz) ⭐ 11,411 | 🐛 5 | 🌐 Jinja | 📅 2026-08-11 - 使用 Ansible 脚本安装 K8S 集群，介绍组件交互原理，方便直接，不受国内网络环境影响。
* [talos](https://github.com/talos-systems/talos) ⭐ 11,002 | 🐛 221 | 🌐 Go | 📅 2026-08-21 - A modern OS for Kubernetes.
* [microk8s](https://github.com/ubuntu/microk8s) ⭐ 9,353 | 🐛 164 | 🌐 Python | 📅 2026-08-22 - A kubernetes cluster in a snap.
* [eksctl](https://github.com/weaveworks/eksctl) ⭐ 5,212 | 🐛 89 | 🌐 Go | 📅 2026-08-21 - A CLI for Amazon EKS.
* [cluster-api](https://github.com/kubernetes-sigs/cluster-api) ⭐ 4,287 | 🐛 224 | 🌐 Go | 📅 2026-08-23 - Kubernetes-style APIs for declaratively managing cluster lifecycle across providers.
* [kubeadm](https://github.com/kubernetes/kubeadm) ⭐ 3,997 | 🐛 39 | 🌐 Go | 📅 2026-08-09 - Aggregator for issues filed against kubeadm.
* [gardener](https://github.com/gardener/gardener) ⭐ 3,431 | 🐛 191 | 🌐 Go | 📅 2026-08-21 - Kubernetes API server extension and controller manager providing conformant Kubernetes clusters (a.k.a. (off)shoot clusters) as a service (with day-2 ops) on Alibaba, AWS, Azure, GCP, and OpenStack.
* [cloudpods](https://github.com/yunionio/cloudpods) ⭐ 2,933 | 🐛 217 | 🌐 Go | 📅 2026-08-21 - A cloud-native open-source unified multi-cloud and hybrid-cloud platform.
* [kubefirst](https://github.com/kubefirst/kubefirst) ⭐ 2,056 | 🐛 289 | 🌐 Go | 📅 2026-02-25 - The Kubefirst Open Source Platform.
* [kubernetes-vagrant-centos-cluster](https://github.com/rootsongjc/kubernetes-vagrant-centos-cluster) ⭐ 1,915 | 🐛 18 | 🌐 Shell | 📅 2022-08-17 - Setting up a distributed Kubernetes cluster along with Istio service mesh locally with Vagrant and VirtualBox.
* [fleet](https://github.com/rancher/fleet) ⭐ 1,724 | 🐛 189 | 🌐 Go | 📅 2026-08-23 - Manage large fleets of Kubernetes clusters.
* [clusternet](https://github.com/clusternet/clusternet) ⭐ 1,447 | 🐛 72 | 🌐 Go | 📅 2026-07-28 - Managing your Kubernetes clusters (including public, private, edge, etc) as easily as visiting the Internet.
* [kube-fledged](https://github.com/senthilrch/kube-fledged) ⭐ 1,373 | 🐛 23 | 🌐 Go | 📅 2026-07-17 - A kubernetes add-on for creating and managing a cache of container images in a kubernetes cluster.
* [usernetes](https://github.com/rootless-containers/usernetes) ⭐ 986 | 🐛 28 | 🌐 Shell | 📅 2026-08-14 - Kubernetes installable under $HOME, without the root privileges.
* [claudie](https://github.com/berops/claudie) ⭐ 790 | 🐛 73 | 🌐 Go | 📅 2026-08-20 - Cloud-agnostic managed Kubernetes.
* [kstone](https://github.com/tkestack/kstone) ⭐ 694 | 🐛 23 | 🌐 Go | 📅 2022-09-02 - Kstone is an etcd management platform, providing cluster management, monitoring, backup, inspection, data migration, visual viewing of etcd data, and intelligent diagnosis.
* [tectonic-installer](https://github.com/coreos/tectonic-installer) ⚠️ Archived - Install a Kubernetes cluster the CoreOS Tectonic Way: HA, self-hosted, RBAC, etcd Operator, and more.
* [kubean](https://github.com/kubean-io/kubean) ⭐ 530 | 🐛 13 | 🌐 Go | 📅 2026-08-18 - Kubernetes lifecycle management operator based on kubespray.
* [wksctl](https://github.com/weaveworks/wksctl) ⚠️ Archived - Open Source Weaveworks Kubernetes System.
* [tensile-kube](https://github.com/virtual-kubelet/tensile-kube) ⭐ 291 | 🐛 4 | 🌐 Go | 📅 2025-12-05 - A Kubernetes Provider.
* [ksctl](https://github.com/kubesimplify/ksctl) ⭐ 268 | 🐛 23 | 🌐 Go | 📅 2026-05-23 - A Generic Kubernetes Management CLI tool for multi-cloud Kubernetes clusters.
* [cluster-lifecycle-manager](https://github.com/zalando-incubator/cluster-lifecycle-manager) ⭐ 248 | 🐛 20 | 🌐 Go | 📅 2026-08-21 - Cluster Lifecycle Manager (CLM) to provision and update multiple Kubernetes clusters.
* [kip](https://github.com/elotl/kip) ⭐ 232 | 🐛 34 | 🌐 Go | 📅 2023-02-25 - Virtual-kubelet provider running pods in cloud instances.
* [kubeup](https://github.com/kubeup/archon) ⭐ 195 | 🐛 8 | 🌐 Go | 📅 2017-11-01 - Cluster operation the Kubernetes way.
* [cloud-native-sandbox](https://github.com/rootsongjc/cloud-native-sandbox) ⭐ 129 | 🐛 3 | 📅 2021-04-13 - Cloud Native Sandbox can help you setup a standalone Kubernetes and Istio environment with Docker on you own laptop.
* [kubeadm-offline-installer](https://github.com/fleeto/kubeadm-offline-installer) - Setup a cluster with kubeadm, without internet connections.

## Developer Workspaces & Productivity

* [client-go](https://github.com/kubernetes/client-go) ⭐ 9,866 | 🐛 0 | 🌐 Go | 📅 2026-08-21 - Go client for Kubernetes.
* [telepresence](https://github.com/telepresenceio/telepresence) ⭐ 7,286 | 🐛 27 | 🌐 Go | 📅 2026-08-20 - Local development against a remote Kubernetes or OpenShift cluster.
* [che](https://github.com/eclipse/che) ⭐ 7,158 | 🐛 218 | 🌐 TypeScript | 📅 2026-08-21 - Eclipse Che: Next-generation Eclipse IDE. Open source workspace server and cloud IDE.
* [devspace](https://github.com/devspace-cloud/devspace) ⭐ 5,145 | 🐛 76 | 🌐 Go | 📅 2026-08-17 - Cloud Native Software Development with Kubernetes and Docker - simply run "devspace up" in any of your projects and start coding directly on top of Kubernetes (works with minikube, self-hosted and cloud-based clusters).
* [kubefwd](https://github.com/txn2/kubefwd) ⭐ 4,161 | 🐛 11 | 🌐 Go | 📅 2026-08-21 - Bulk port forwarding Kubernetes services for local development.
* [kube-ps1](https://github.com/jonmosco/kube-ps1) ⭐ 3,806 | 🐛 5 | 🌐 Shell | 📅 2026-05-24 - Kubernetes prompt info for bash and zsh.
* [kubernetes-client](https://github.com/fabric8io/kubernetes-client) ⭐ 3,669 | 🐛 105 | 🌐 Java | 📅 2026-08-11 - Java client for Kubernetes & OpenShift 3.
* [okteto](https://github.com/okteto/okteto) ⭐ 3,534 | 🐛 37 | 🌐 Go | 📅 2026-08-22 - Local development experience for Kubernetes apps.
* [kubectl-tree](https://github.com/ahmetb/kubectl-tree) ⭐ 3,416 | 🐛 16 | 🌐 Go | 📅 2026-07-27 - kubectl plugin to browse Kubernetes object hierarchies as a tree 🎄 (using? star the repo!)
* [kubie](https://github.com/sbstp/kubie) ⭐ 2,618 | 🐛 59 | 🌐 Rust | 📅 2026-08-15 - A more powerful alternative to kubectx and kubens.
* [kube-shell](https://github.com/cloudnativelabs/kube-shell) ⭐ 2,390 | 🐛 67 | 🌐 Python | 📅 2022-11-02 - Kubernetes shell: An integrated shell for working with the Kubernetes CLI.
* [kubebox](https://github.com/astefanutti/kubebox) ⭐ 2,231 | 🐛 42 | 🌐 JavaScript | 📅 2024-06-17 - Terminal console for Kubernetes clusters.
* [xlskubectl](https://github.com/learnk8s/xlskubectl) ⭐ 2,008 | 🐛 7 | 🌐 JavaScript | 📅 2022-09-23 - A spreadsheet to control your Kubernetes cluster.
* [nocalhost](https://github.com/nocalhost/nocalhost) ⭐ 1,895 | 🐛 82 | 🌐 Go | 📅 2026-08-19 - Nocalhost is Cloud Native Dev Environment.
* [wa](https://github.com/wa-lang/wa/) ⭐ 1,767 | 🐛 6 | 🌐 Go | 📅 2026-04-30 - The Wa Programming Language: Simple, maintainable, compiled language for developing WebAssembly software.
* [kftray](https://github.com/hcavarsan/kftray) ⭐ 1,551 | 🐛 18 | 🌐 Rust | 📅 2026-08-23 - Manage and run multiple kubectl port-forward configurations directly in the menu bar, syncing configurations with git repositories.
* [ksync](https://github.com/ksync/ksync) ⚠️ Archived - Sync files between your local system and a kubernetes cluster.
* [dockersh](https://github.com/Yelp/dockersh) ⚠️ Archived - A shell which places users into individual docker containers.
* [fubectl](https://github.com/kubermatic/fubectl) ⭐ 1,006 | 🐛 12 | 🌐 Go | 📅 2026-08-12 - Reduces repetitive interactions with kubectl.
* [cloudtty](https://github.com/cloudtty/cloudtty) ⭐ 660 | 🐛 14 | 🌐 Go | 📅 2026-08-21 - A Friendly Kubernetes CloudShell (Web Terminal) !
* [kvdi](https://github.com/tinyzimmer/kvdi) ⭐ 458 | 🐛 44 | 🌐 Go | 📅 2023-10-20 - A Kubernetes-native Virtual Desktop Infrastructure.
* [macos-vz-kubelet](https://github.com/agoda-com/macOS-vz-kubelet) ⭐ 399 | 🐛 5 | 🌐 Go | 📅 2026-07-06 - Run native macOS workloads on Kubernetes.
* [mindaro](https://github.com/microsoft/mindaro) ⚠️ Archived - Bridge to Kubernetes - for Visual Studio and Visual Studio Code
* [freshpod](https://github.com/googlecloudplatform/freshpod) ⚠️ Archived - Restart Pods on Minikube automatically on image rebuilds.
* [kubelibrary](https://github.com/devopsspiral/KubeLibrary) ⭐ 145 | 🐛 31 | 🌐 Python | 📅 2026-08-13 - Kubernetes library for Robot Framework.
* [go-kubectx](https://github.com/aca/go-kubectx) ⚠️ Archived - 5x-10x faster alternative to kubectx. Uses client-go.
* [kubeonoff](https://github.com/GambitResearch/kubeonoff) ⭐ 24 | 🐛 0 | 🌐 JavaScript | 📅 2020-08-07 - A simple web UI for managing Kubernetes deployments.
* [k](https://github.com/yggheim/k) ⭐ 15 | 🐛 0 | 🌐 Shell | 📅 2020-05-27 - Exec into kubernetes pod easy (via kubectl).

## Diagnostics & Troubleshooting

* [k8sgpt](https://github.com/k8sgpt-ai/k8sgpt) ⭐ 8,105 | 🐛 81 | 🌐 Go | 📅 2026-08-23 - Giving Kubernetes Superpowers to everyone.
* [kube-no-trouble](https://github.com/doitintl/kube-no-trouble) ⭐ 3,682 | 🐛 33 | 🌐 Go | 📅 2025-10-16 - Easily check your clusters for use of deprecated APIs.
* [ksniff](https://github.com/eldadru/ksniff) ⭐ 3,473 | 🐛 67 | 🌐 Go | 📅 2024-08-02 - Kubectl plugin to ease sniffing on Kubernetes pods using tcpdump and Wireshark.
* [kubespy](https://github.com/pulumi/kubespy) ⭐ 3,078 | 🐛 18 | 🌐 Go | 📅 2026-08-22 - Tools for observing Kubernetes resources in real time, powered by Pulumi.
* [robusta](https://github.com/robusta-dev/robusta) ⭐ 3,076 | 🐛 202 | 🌐 Python | 📅 2026-08-23 - Open source Kubernetes troubleshooting and automation platform.
* [kube-capacity](https://github.com/robscott/kube-capacity) ⭐ 2,664 | 🐛 51 | 🌐 Go | 📅 2025-11-21 - A simple CLI that provides an overview of the resource requests, limits, and utilization in a Kubernetes cluster.
* [kubectl-trace](https://github.com/iovisor/kubectl-trace) ⭐ 2,186 | 🐛 49 | 🌐 Go | 📅 2026-04-16 - Schedule bpftrace programs on your kubernetes cluster using the kubectl.
* [kail](https://github.com/boz/kail) ⭐ 2,067 | 🐛 34 | 🌐 Go | 📅 2025-07-03 - Kubernetes log viewer.
* [cri-tools](https://github.com/kubernetes-sigs/cri-tools) ⭐ 2,009 | 🐛 17 | 🌐 Go | 📅 2026-08-21 - CLI and validation tools for Kubelet Container Runtime Interface (CRI).
* [terminus](https://github.com/godaddy/terminus) ⭐ 1,911 | 🐛 17 | 🌐 JavaScript | 📅 2025-08-20 - Graceful shutdown and Kubernetes readiness / liveness checks for any Node.js HTTP applications.
* [squash](https://github.com/solo-io/squash) ⭐ 1,766 | 🐛 87 | 🌐 Go | 📅 2022-06-09 - The debugger for microservices.
* [memfree](https://github.com/memfreeme/memfree) ⭐ 1,507 | 🐛 18 | 🌐 TypeScript | 📅 2026-07-06 - Open Source Hybrid AI Search Engine, Instantly Get Accurate Answers from the Internet, Bookmarks, Notes, and Docs. Support One-Click Deployment.
* [kubeletctl](https://github.com/cyberark/kubeletctl) ⭐ 902 | 🐛 6 | 🌐 Go | 📅 2025-08-06 - A client for kubelet.
* [kubetap](https://github.com/soluble-ai/kubetap) ⭐ 645 | 🐛 19 | 🌐 Go | 📅 2023-08-30 - Kubectl plugin to interactively proxy Kubernetes Services with ease.
* [kube-lineage](https://github.com/tohjustin/kube-lineage) ⭐ 461 | 🐛 9 | 🌐 Go | 📅 2024-07-07 - A CLI tool to display all dependencies or dependents of an object in a Kubernetes cluster.
* [kubectl-doctor](https://github.com/emirozer/kubectl-doctor) ⭐ 366 | 🐛 10 | 🌐 Go | 📅 2022-10-06 - Kubectl cluster triage plugin for Kubernetes (brew doctor equivalent).
* [crashcart](https://github.com/oracle/crashcart) ⚠️ Archived - CrashCart: sideload binaries into a running container.
* [pangolin](https://github.com/dpeckett/pangolin) ⚠️ Archived - An enhanced Horizontal Pod Autoscaler for Kubernetes.
* [kubeutr](https://github.com/mr-karan/kubekutr) ⚠️ Archived - Cookie cutter templating tool for scaffolding K8s manifests.
* [kubehandler](https://github.com/gojektech/kubehandler) ⭐ 29 | 🐛 0 | 🌐 Go | 📅 2022-08-05 - A framework for writing Kubernetes controllers.
* [kubeload](https://github.com/Efrat19/kubeload) ⭐ 24 | 🐛 3 | 🌐 Go | 📅 2024-03-03 - Jobs managing K8S operator for IAC-oriented load tests.
* [kubeiql](https://github.com/yipeeio/kubeiql) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2018-11-29 - A GraphQL interface for Kubernetes.
* [releaserun-cli](https://github.com/Releaserun/releaserun-cli) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-15 - CLI tool to check Kubernetes manifests for deprecated/removed APIs, scan dependencies for vulnerabilities, and track version lifecycle status.
* [compass](https://github.com/winfordlin/Compass) - A Debugging Tool for your Kubernetes Deployments.
* [kube-version-converter](https://github.com/fleeto/kube-version-converter) - Convert API Object file into specified version.
* [stern](https://github.com/wercker/stern) - Multi pod and container log tailing for Kubernetes.

## Testing & Conformance

* [test-infra](https://github.com/kubernetes/test-infra) ⭐ 4,016 | 🐛 125 | 🌐 Go | 📅 2026-08-23 - Test infrastructure for the Kubernetes project.
* [kwok](https://github.com/kubernetes-sigs/kwok) ⭐ 3,174 | 🐛 25 | 🌐 Go | 📅 2026-08-21 - Kubernetes WithOut Kubelet - Simulates thousands of Nodes and Clusters.
* [sonobuoy](https://github.com/vmware-tanzu/sonobuoy) ⭐ 3,051 | 🐛 34 | 🌐 Go | 📅 2026-07-27 - Heptio Sonobuoy is a diagnostic tool that makes it easier to understand the state of a Kubernetes cluster by running a set of Kubernetes conformance tests in an accessible and non-destructive manner.
* [jumpstarter](https://github.com/jumpstarter-dev/jumpstarter) ⭐ 211 | 🐛 169 | 🌐 Python | 📅 2026-08-23 - Open source hardware-in-the-loop testing framework with Kubernetes-native device management and CI/CD integration.
* [seaworthy](https://github.com/cakehappens/seaworthy) ⭐ 39 | 🐛 0 | 🌐 Go | 📅 2020-08-10 - A CLI to verify Kubernetes resource health.

## Data Protection & Backup

* [ark](https://github.com/vmware-tanzu/velero) ⭐ 10,250 | 🐛 834 | 🌐 Go | 📅 2026-08-22 - Heptio Ark is a utility for managing disaster recovery, specifically for your Kubernetes cluster resources and persistent volumes. Brought to you by Heptio.
* [stash](https://github.com/stashed/stash) ⭐ 1,424 | 🐛 121 | 🌐 Go | 📅 2026-08-19 - Backup your Kubernetes Volumes.
* [dotmesh](https://github.com/dotmesh-io/dotmesh) ⭐ 535 | 🐛 221 | 🌐 Go | 📅 2023-09-01 - Dotmesh (dm) is like git for your data volumes (databases, files etc) in Docker and Kubernetes.
* [k8s-snapshots](https://github.com/miracle2k/k8s-snapshots) ⭐ 350 | 🐛 21 | 🌐 Python | 📅 2026-01-05 - Automatic Volume Snapshots on Kubernetes.

## Cost & Governance

* [karpenter](https://github.com/aws/karpenter) ⭐ 7,704 | 🐛 506 | 🌐 Go | 📅 2026-08-21 - Kubernetes Node Autoscaling: built for flexibility, performance, and scalability.
* [cost-model](https://github.com/kubecost/cost-model) ⭐ 6,693 | 🐛 298 | 🌐 Go | 📅 2026-08-21 - Cross-cloud cost allocation models for workloads running on Kubernetes.
* [opencost](https://github.com/opencost/opencost) ⭐ 6,693 | 🐛 298 | 🌐 Go | 📅 2026-08-21 - Kubernetes cost monitoring powered by open allocation models.
* [resoto](https://github.com/someengineering/resoto) ⭐ 2,074 | 🐛 25 | 🌐 Python | 📅 2026-03-28 - Resoto creates an inventory of your cloud, provides deep visibility, and reacts to changes in your infrastructure.
* [lotus](https://github.com/uselotus/lotus) ⭐ 1,833 | 🐛 35 | 🌐 Python | 📅 2026-08-13 - Open Source Pricing & Packaging Infrastructure for SaaS.
* [escalator](https://github.com/atlassian/escalator) ⭐ 686 | 🐛 18 | 🌐 Go | 📅 2026-07-06 - Escalator is a batch or job optimized horizontal autoscaler for Kubernetes.
* [kube-downscaler](https://github.com/hjacobs/kube-downscaler) ⚠️ Archived - Scale down Kubernetes deployments after work hours.
* [burn](https://github.com/tanrikuluozlem/burn) ⭐ 85 | 🐛 7 | 🌐 Go | 📅 2026-08-19 - CLI tool for Kubernetes cost analysis with per-namespace breakdown, real cloud pricing, and AI-powered recommendations.

## Networking Utilities

* [netshoot](https://github.com/nicolaka/netshoot) ⭐ 10,947 | 🐛 41 | 🌐 Shell | 📅 2026-07-01 - A Docker + Kubernetes network trouble-shooting swiss-army container.
* [dragonfly2](https://github.com/dragonflyoss/Dragonfly2) ⭐ 3,307 | 🐛 32 | 🌐 Go | 📅 2026-08-20 - Dragonfly is an intelligent P2P based file distribution system.
* [kt-connect](https://github.com/alibaba/kt-connect) ⭐ 1,677 | 🐛 113 | 🌐 Go | 📅 2024-06-18 - Manage and Integration with your Kubernetes dev environment more efficient.
* [tor-controller](https://github.com/kragniz/tor-controller) ⭐ 534 | 🐛 10 | 🌐 Go | 📅 2021-09-26 - Run Tor onion services on Kubernetes.
* [k8s-mirror](https://github.com/darkbitio/k8s-mirror) ⚠️ Archived - Creates a local mirror of a Kubernetes cluster in a docker container to support offline reviewing.
* [kconmon](https://github.com/Stono/kconmon) ⚠️ Archived - A Kubernetes node connectivity monitoring tool.
* [podtnl](https://github.com/narendranathreddythota/podtnl) ⭐ 65 | 🐛 4 | 🌐 Go | 📅 2022-10-20 - A Powerful CLI that makes your pod available to online without exposing a Kubernetes service.
* [istio-pod-network-controller](https://github.com/sabre1041/istio-pod-network-controller) ⭐ 29 | 🐛 7 | 🌐 Go | 📅 2019-09-17 - Controller to manage Istio Pod Network.

## API Design & Documentation

* [swagger](https://github.com/swagger-api/swagger-ui) ⭐ 28,980 | 🐛 1,139 | 🌐 JavaScript | 📅 2026-08-22 - Swagger UI is a collection of HTML, JavaScript, and CSS assets that dynamically generate beautiful documentation from a Swagger-compliant API.
* [aglio](https://github.com/danielgtaylor/aglio) ⭐ 4,748 | 🐛 135 | 🌐 CoffeeScript | 📅 2019-05-13 - An API Blueprint renderer with theme support that outputs static HTML.
* [drakov](https://github.com/Aconex/drakov) ⭐ 477 | 🐛 52 | 🌐 JavaScript | 📅 2023-04-24 - Mock Server that implements the API Blueprint specification.

## Databases

* [redis](https://github.com/redis/redis) ⭐ 76,086 | 🐛 2,909 | 🌐 C | 📅 2026-08-23 - Redis is an in-memory database that persists on disk. The data model is key-value, but many different kind of values are supported: Strings, Lists, Sets, Sorted Sets, Hashes, HyperLogLogs, Bitmaps.
* [nocodb](https://github.com/nocodb/nocodb) ⭐ 64,666 | 🐛 708 | 🌐 TypeScript | 📅 2026-08-23 - The Open Source Airtable alternative.
* [etcd](https://github.com/etcd-io/etcd) ⭐ 52,156 | 🐛 322 | 🌐 Go | 📅 2026-08-20 - Distributed reliable key-value store for the most critical data of a distributed system.
* [milvus](https://github.com/milvus-io/milvus) ⭐ 45,745 | 🐛 1,335 | 🌐 Go | 📅 2026-08-22 - Vector database for scalable similarity search and AI applications.
* [tidb](https://github.com/pingcap/tidb) ⭐ 40,461 | 🐛 6,832 | 🌐 Go | 📅 2026-08-23 - TiDB is a distributed NewSQL database compatible with MySQL protocol.
* [leveldb](https://github.com/google/leveldb) ⭐ 39,350 | 🐛 403 | 🌐 C++ | 📅 2026-03-11 - LevelDB is a fast key-value storage library written at Google that provides an ordered mapping from string keys to string values.
* [cockroachdb](https://github.com/cockroachdb/cockroach/) ⭐ 32,411 | 🐛 8,318 | 🌐 Go | 📅 2026-08-07 - CockroachDB - the open source, cloud-native SQL database.
* [influxdb](https://github.com/influxdata/influxdb) ⭐ 31,707 | 🐛 2,148 | 🌐 Rust | 📅 2026-08-20 - Scalable datastore for metrics, events, and real-time analytics.
* [mongodb](https://github.com/mongodb/mongo) ⭐ 28,501 | 🐛 31 | 🌐 C++ | 📅 2026-08-22 - MongoDB is an open source database that uses a document-oriented data model.
* [rethinkdb](https://github.com/rethinkdb/rethinkdb) ⭐ 26,996 | 🐛 1,352 | 🌐 C++ | 📅 2026-03-28 - The open-source database for the realtime web.
* [timescaledb](https://github.com/timescale/timescaledb) ⭐ 23,402 | 🐛 393 | 🌐 C | 📅 2026-08-20 - An open-source time-series SQL database optimized for fast ingest and complex queries. Packaged as a PostgreSQL extension.
* [sharding-sphere](https://github.com/apache/shardingsphere) ⭐ 20,784 | 🐛 233 | 🌐 Java | 📅 2026-08-23 - Distributed database middleware.
* [tikv](https://github.com/tikv/tikv) ⭐ 16,807 | 🐛 1,806 | 🌐 Rust | 📅 2026-08-21 - Distributed transactional key-value database, originally created to complement TiDB.
* [arangodb](https://github.com/arangodb/arangodb) ⭐ 14,261 | 🐛 838 | 🌐 C++ | 📅 2026-08-22 - ArangoDB is a native multi-model database with flexible data models for documents, graphs, and key-values. Build high performance applications using a convenient SQL-like query language or JavaScript extensions.
* [nebula](https://github.com/vesoft-inc/nebula) ⭐ 12,359 | 🐛 678 | 🌐 C++ | 📅 2026-05-18 - A distributed, fast open-source graph database featuring horizontal scalability and high availability.
* [oceanbase](https://github.com/oceanbase/oceanbase) ⭐ 10,253 | 🐛 584 | 🌐 C++ | 📅 2026-08-23 - A distributed, banking suitable, open-source related database featuring high scalability and high compatibility.
* [databend](https://github.com/datafuselabs/databend) ⭐ 9,422 | 🐛 563 | 🌐 Rust | 📅 2026-08-23 - An elastic and reliable Serverless Data Warehouse, offers Blazing Fast Query and combines Elasticity, Simplicity, Low cost of the Cloud, built to make the Data Cloud easy.
* [tinydb](https://github.com/msiemens/tinydb) ⭐ 7,557 | 🐛 8 | 🌐 Python | 📅 2026-08-10 - TinyDB is a lightweight document oriented database optimized for your happiness.
* [spicedb](https://github.com/authzed/spicedb) ⭐ 6,982 | 🐛 149 | 🌐 Go | 📅 2026-08-21 - Inspired by Google's Zanzibar paper, SpiceDB is a database system for managing security-critical application permissions.
* [couchdb](https://github.com/apache/couchdb) ⭐ 6,940 | 🐛 371 | 🌐 Erlang | 📅 2026-08-21 - Apache CouchDB is one of a new breed of database management systems.
* [opentsdb](https://github.com/OpenTSDB/opentsdb) ⭐ 5,066 | 🐛 538 | 🌐 Java | 📅 2024-12-12 - A scalable, distributed Time Series Database.
* [m3](https://github.com/m3db/m3) ⭐ 4,894 | 🐛 220 | 🌐 Go | 📅 2026-08-17 - M3 monorepo - Distributed TSDB, Aggregator and Query Engine, Prometheus Sidecar, Graphite Compatible, Metrics Platform.
* [stolon](https://github.com/sorintlab/stolon) ⭐ 4,826 | 🐛 153 | 🌐 Go | 📅 2024-07-08 - PostgreSQL cloud native High Availability and more.
* [kvrocks](https://github.com/KvrocksLabs/kvrocks) ⭐ 4,401 | 🐛 241 | 🌐 C++ | 📅 2026-08-21 - Kvrocks is a distributed key value NoSQL database based on RocksDB and compatible with Redis protocol.
* [polardb-for-postgresql](https://github.com/alibaba/PolarDB-for-PostgreSQL) ⭐ 3,192 | 🐛 65 | 🌐 C | 📅 2026-08-23 - PolarDB for PostgreSQL (PolarDB for short) is an open source database system based on PostgreSQL.
* [beringei](https://github.com/facebookarchive/beringei) ⚠️ Archived - Beringei is a high performance, in-memory storage engine for time series data.
* [kubeblocks](https://github.com/apecloud/kubeblocks) ⭐ 3,109 | 🐛 255 | 🌐 Go | 📅 2026-08-21 - KubeBlocks is an open source system software that runs and manages data infrastructure on K8s. It helps developers, SREs, and platform engineers deploy and maintain dedicated DBPaaS, and supports a variety of public clouds and on-premise environments.
* [promscale](https://github.com/timescale/promscale) ⚠️ Archived - Unified observability backend for metrics and traces powered by SQL and built on PostgreSQL and TimescaleDB.
* [xline](https://github.com/xline-kv/Xline) ⭐ 714 | 🐛 40 | 🌐 Rust | 📅 2026-08-17 - A geo-distributed KV store for metadata management.
* [montydb](https://github.com/davidlatwe/montydb) ⭐ 619 | 🐛 31 | 🌐 Python | 📅 2026-07-20 - Monty, Mongo tinified. MongoDB implemented in Python.
* [kubesql](https://github.com/xuxinkun/kubesql) ⭐ 53 | 🐛 4 | 🌐 Java | 📅 2022-11-16 - A tool using sql to query the resources of kubernetes, such as pod, node and so on.
* [mehdb](https://github.com/mhausenblas/mehdb) ⭐ 22 | 🐛 1 | 🌐 Go | 📅 2021-02-14 - Educational Kubernetes-native NoSQL datastore using StatefulSet and persistent volumes.
* [kubedb](https://github.com/k8sdb/cli) ⭐ 0 | 🐛 0 | 🌐 Go | 📅 2019-03-27 - KubeDB CLI to manage kubernetes ready production-grade Databases.

## Storage & Data Management

* [minio](https://github.com/minio/minio) ⚠️ Archived - Minio is an open source object storage server compatible with Amazon S3 APIs.
* [harbor](https://github.com/goharbor/harbor) ⭐ 29,211 | 🐛 849 | 🌐 Go | 📅 2026-08-22 - An open source trusted cloud native registry project that stores, signs, and scans content.
* [vitess](https://github.com/vitessio/vitess) ⭐ 21,240 | 🐛 1,087 | 🌐 Go | 📅 2026-08-23 - Vitess is a database clustering system for horizontal scaling of MySQL.
* [ceph](https://github.com/ceph/ceph) ⭐ 16,956 | 🐛 1,260 | 🌐 C++ | 📅 2026-08-23 - Ceph is a distributed object, block, and file storage platform.
* [juicefs](https://github.com/juicedata/juicefs) ⭐ 14,352 | 🐛 197 | 🌐 Go | 📅 2026-08-21 - A distributed POSIX file system built on top of Redis and S3.
* [rook](https://github.com/rook/rook) ⭐ 13,607 | 🐛 145 | 🌐 Go | 📅 2026-08-21 - File, Block, and Object Storage Services for your Cloud-Native Environment.
* [openebs](https://github.com/openebs/openebs) ⭐ 9,800 | 🐛 39 | 📅 2026-08-23 - OpenEBS is containerized block storage written in Go for cloud native and other environments w/ per container (or pod) QoS SLAs, tiering and replica policies across AZs and environments, and predictable and scalable performance.
* [fastdfs](https://github.com/happyfish100/fastdfs) ⭐ 9,248 | 🐛 466 | 🌐 C | 📅 2026-08-23 - FastDFS is an open source high performance distributed file system (DFS). It's major functions include: file storing, file syncing and file accessing, and design for high capacity and load balance.
* [longhorn](https://github.com/longhorn/longhorn) ⭐ 7,926 | 🐛 1,857 | 🌐 Shell | 📅 2026-08-23 - We put storage on cows and move them around from rancher.
* [chubaofs](https://github.com/chubaofs/chubaofs) ⭐ 5,634 | 🐛 268 | 🌐 Go | 📅 2026-08-19 - A distributed storage system for cloud native applications.
* [glusterfs](https://github.com/gluster/glusterfs) ⭐ 5,218 | 🐛 280 | 🌐 C | 📅 2026-08-22 - Gluster is a software defined distributed storage that can scale to several petabytes. It provides interfaces for object, block and file storage.
* [flocker](https://github.com/ClusterHQ/flocker) ⭐ 3,385 | 🐛 80 | 🌐 Python | 📅 2017-05-18 - Container data volume manager for your Dockerized application.
* [zot](https://github.com/project-zot/zot) ⭐ 2,643 | 🐛 78 | 🌐 Go | 📅 2026-08-21 - A production-ready vendor-neutral OCI-native container image registry (purely based on OCI Distribution Specification).
* [oras](https://github.com/oras-project/oras) ⭐ 2,397 | 🐛 76 | 🌐 Go | 📅 2026-08-20 - OCI registry client, managing content like artifacts, images, packages.
* [curve](https://github.com/opencurve/curve) ⭐ 2,387 | 🐛 134 | 🌐 C++ | 📅 2024-08-13 - Curve is a better-used cloud-native SDS storage system, featured with high performance, easy operation, cloud native. Curve is composed with CurveBS and CurveFS based on Raft.
* [torus](https://github.com/coreos/torus) ⚠️ Archived - Torus Distributed Storage.
* [convoy](https://github.com/rancher/convoy) ⚠️ Archived - A Docker volume plugin, managing persistent container volumes.
* [heketi](https://github.com/heketi/heketi) ⚠️ Archived - RESTful based volume management framework for GlusterFS.
* [zenko](https://github.com/scality/Zenko) ⭐ 671 | 🐛 23 | 🌐 Gherkin | 📅 2026-08-22 - Because everyone should be in control of their data.
* [hwameistor](https://github.com/hwameistor/hwameistor) ⭐ 654 | 🐛 13 | 🌐 Go | 📅 2026-08-11 - Hwameistor is an HA local storage system for cloud-native stateful workloads.
* [k8ssandra](https://github.com/k8ssandra/k8ssandra) ⭐ 462 | 🐛 248 | 🌐 YAML | 📅 2026-07-28 - K8ssandra is a collection of Helm charts for running Apache Cassandra on Kubernetes in production.
* [infinit](https://github.com/infinit/infinit) ⭐ 368 | 🐛 29 | 📅 2016-10-30 - The Infinit policy-based software-defined storage platform.
* [glusterd2](https://github.com/gluster/glusterd2) ⚠️ Archived - GlusterD-2.0 is the distributed management framework to be used for GlusterFS-4.0.
* [kubefs](https://github.com/configurator/kubefs) ⭐ 94 | 🐛 0 | 🌐 Go | 📅 2020-06-23 - Mount kubernetes metadata storage as a filesystem.
* [awesome-object-storage](https://github.com/mixpeek/awesome-object-storage) ⭐ 27 | 🐛 8 | 📅 2026-05-21 - Curated comparison of 21 S3-compatible object storage providers with pricing, gotchas, and tools.
* [leofs](https://leo-project.net/leofs/) - The LeoFS Storage System.
* [rafter](https://github.com/kyma-project/rafter) - Kubernetes-native S3-like files/assets store based on CRDs and powered by MinIO.
* [storageos](https://storageos.com/) - Enterprise persistent storage for containers and the cloud.

## Streaming & Messaging

* [kafka](https://github.com/apache/kafka) ⭐ 33,597 | 🐛 515 | 🌐 Java | 📅 2026-08-23 - A distributed streaming platform.
* [nsq](https://github.com/nsqio/nsq) ⭐ 25,772 | 🐛 77 | 🌐 Go | 📅 2026-08-11 - A realtime distributed messaging platform.
* [rocketmq](https://github.com/apache/rocketmq) ⭐ 22,562 | 🐛 563 | 🌐 Java | 📅 2026-08-20 - Apache RocketMQ is a distributed messaging and streaming platform with low latency, high performance and reliability, trillion-level capacity and flexible scalability.
* [gnatsd](https://github.com/nats-io/nats-server) ⭐ 20,566 | 🐛 544 | 🌐 Go | 📅 2026-08-22 - High-Performance server for NATS, the cloud native messaging system.
* [emqx](https://github.com/emqx/emqx) ⭐ 16,648 | 🐛 258 | 🌐 Erlang | 📅 2026-08-22 - EMQ X Broker - Scalable Distributed MQTT Message Broker for IoT in 5G Era.
* [pulsar](https://github.com/apache/pulsar) ⭐ 15,311 | 🐛 1,751 | 🌐 Java | 📅 2026-08-20 - A distributed messaging and streaming platform.
* [automq](https://github.com/AutoMQ/automq) ⭐ 10,545 | 🐛 61 | 🌐 Java | 📅 2026-08-21 - A cloud native implementation for Apache Kafka, reducing your cloud infrastructure bill by up to 90%.
* [jocko](https://github.com/travisjeffery/jocko) ⭐ 5,012 | 🐛 64 | 🌐 Go | 📅 2026-05-20 - Kafka implemented in Golang with built-in coordination (No ZK dep, single binary install, Cloud Native).
* [flume](https://github.com/apache/flume) ⭐ 2,565 | 🐛 80 | 🌐 Java | 📅 2026-08-21 - Apache Flume is a distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log data.
* [eventmesh](https://github.com/WeBankFinTech/EventMesh) ⭐ 1,746 | 🐛 268 | 🌐 Java | 📅 2026-08-20 - EventMesh is a dynamic cloud-native eventing infrastructure used to decouple the application and backend middleware layer, which supports a wide range of use cases that encompass complex multi-cloud, widely distributed topologies using diverse technology stacks.
* [kubemq](https://github.com/kubemq-io/kubemq) ⭐ 664 | 🐛 5 | 🌐 Go | 📅 2023-02-18 - KubeMQ is Enterprise-grade message broker native for Docker and Kubernetes.
* [rabbitmq](https://github.com/rabbitmq) - RabbitMQ is the most widely deployed open source message broker.

## Service Mesh

* [istio](https://github.com/istio/istio) ⭐ 38,351 | 🐛 509 | 🌐 Go | 📅 2026-08-23 - Connect, secure, control, and observe services.
* [consul](https://github.com/hashicorp/consul) ⭐ 30,038 | 🐛 1,414 | 🌐 Go | 📅 2026-08-22 - Consul is a distributed, highly available, and data center aware solution to connect and configure applications across dynamic, distributed infrastructure.
* [linkerd2](https://github.com/linkerd/linkerd2) ⭐ 11,479 | 🐛 199 | 🌐 Go | 📅 2026-08-21 - Ultralight, security-first service mesh for Kubernetes. Main repo for Linkerd 2.x.
* [nginx-unit](https://github.com/nginx/unit) ⚠️ Archived - NGINX Unit is a new, lightweight, open source application server built to meet the demands of dynamic and distributed applications.
* [linkerd](https://github.com/linkerd/linkerd) ⭐ 5,310 | 🐛 146 | 🌐 Scala | 📅 2023-03-04 - Resilient service mesh for cloud native apps.
* [kuma](https://github.com/kumahq/kuma) ⭐ 3,995 | 🐛 157 | 🌐 Go | 📅 2026-08-21 - Universal Control Plane for your Service Mesh.
* [secretscanner](https://github.com/deepfence/SecretScanner) ⭐ 3,381 | 🐛 25 | 🌐 Go | 📅 2026-03-07 - Find secrets and passwords in container images and file systems.
* [osm](https://github.com/openservicemesh/osm) ⚠️ Archived - Open Service Mesh (OSM) is a lightweight, extensible, cloud native service mesh that allows users to uniformly manage, secure, and get out-of-the-box observability features for highly dynamic microservice environments.
* [maesh](https://github.com/containous/maesh) ⭐ 2,105 | 🐛 43 | 🌐 Go | 📅 2026-03-23 - Simpler Service Mesh.
* [sermant](https://github.com/sermant-io/Sermant) ⭐ 1,343 | 🐛 31 | 🌐 Java | 📅 2026-02-06 - A Cloud-Native Proxyless Service Mesh based on Java Bytecode Enhancement Technology.
* [merbridge](https://github.com/merbridge/merbridge) ⭐ 808 | 🐛 36 | 🌐 Go | 📅 2025-05-19 - Use eBPF to speed up your Service Mesh like crossing an Einstein-Rosen Bridge.
* [opensergo-specification](https://github.com/opensergo/opensergo-specification) ⭐ 795 | 🐛 28 | 🌐 Makefile | 📅 2024-05-22 - OpenSergo is an open, language-agnostic cloud-native service governance specification.
* [aeraki](https://github.com/aeraki-framework/aeraki) ⭐ 758 | 🐛 21 | 🌐 Go | 📅 2025-12-05 - Manage any layer 7 traffic in an Istio service mesh.
* [kmesh](https://github.com/kmesh-net/kmesh) ⭐ 751 | 🐛 489 | 🌐 Go | 📅 2026-08-20 - High Performance Service Mesh Data Plane Based on Programmable Kernel.
* [nginmesh](https://github.com/nginxinc/nginmesh) ⚠️ Archived - Service Mesh using Nginx.
* [easemesh](https://github.com/megaease/easemesh) ⭐ 520 | 🐛 14 | 🌐 Go | 📅 2024-04-01 - A service mesh implementation for connecting, control, and observe services in spring-cloud.
* [slime](https://github.com/slime-io/slime) ⭐ 424 | 🐛 30 | 🌐 Go | 📅 2025-02-26 - Slime is a CRD controller for istio.
* [amalgam8](https://github.com/amalgam8/amalgam8) ⭐ 157 | 🐛 22 | 🌐 Go | 📅 2025-08-18 - Content and Version-based Routing Fabric for Polyglot Microservices.
* [getmesh](https://github.com/tetratelabs/getmesh) ⭐ 142 | 🐛 22 | 🌐 Go | 📅 2023-09-14 - An integration, and lifecycle management CLI tool that ensures the use of supported and trusted versions of Istio.
* [istio-security-analyzer](https://github.com/tetratelabs/istio-security-analyzer) - A tool to analyze Istio security.
* [servicecomb](https://github.com/ServiceComb) - ServiceComb is a microservice framework that provides an easy way to develop and deploy applications in the cloud.
* [supergloo](https://github.com/solo-io/service-mesh-hub) - The Service Mesh Orchestration Platform.

## Service Discovery & Registry

* [apollo](https://github.com/ctripcorp/apollo) ⭐ 29,798 | 🐛 159 | 🌐 Java | 📅 2026-08-22 - Apollo（阿波罗）是携程框架部门研发的分布式配置中心，能够集中化管理应用不同环境、不同集群的配置，配置修改后能够实时推送到应用端，并且具备规范的权限、流程治理等特性，适用于微服务配置管理场景。
* [coredns](https://github.com/coredns/coredns) ⭐ 14,269 | 🐛 296 | 🌐 Go | 📅 2026-08-20 - CoreDNS is a DNS server that chains middleware.
* [zookeeper](https://github.com/apache/zookeeper) ⭐ 12,793 | 🐛 241 | 🌐 Java | 📅 2026-08-17 - Apache ZooKeeper is an effort to develop and maintain an open-source server which enables highly reliable distributed coordination.
* [eureka](https://github.com/Netflix/eureka) ⭐ 12,735 | 🐛 137 | 🌐 Java | 📅 2026-08-06 - AWS Service registry for resilient mid-tier load balancing and failover.
* [confd](https://github.com/kelseyhightower/confd) ⭐ 8,426 | 🐛 178 | 🌐 Go | 📅 2024-07-16 - Manage local application configuration files using templates and data from etcd or consul.
* [registrator](https://github.com/gliderlabs/registrator) ⭐ 4,675 | 🐛 257 | 🌐 Go | 📅 2025-05-22 - Service registry bridge for Docker with pluggable adapters.
* [vulcand](https://github.com/vulcand/vulcand) ⭐ 3,094 | 🐛 71 | 🌐 Go | 📅 2024-07-27 - Programmatic load balancer backed by Etcd.
* [polaris](https://github.com/polarismesh/polaris) ⭐ 2,559 | 🐛 109 | 🌐 Go | 📅 2025-10-14 - Service discovery and governance center for distributed and microservice architecture.
* [synapse](https://github.com/airbnb/synapse) ⭐ 2,062 | 🐛 48 | 🌐 Ruby | 📅 2023-10-21 - A transparent service discovery framework for connecting an SOA.
* [service-broker](https://github.com/openservicebrokerapi/servicebroker) ⭐ 1,482 | 🐛 28 | 🌐 Shell | 📅 2026-04-15 - Open Service Broker API Specification.
* [service-catalog](https://github.com/kubernetes-sigs/service-catalog) ⚠️ Archived - Consume services in Kubernetes using the Open Service Broker API.
* [clusterpedia](https://github.com/clusterpedia-io/clusterpedia) ⭐ 883 | 🐛 58 | 🌐 Go | 📅 2026-08-20 - Clusterpedia is used for complex resource searches across multiple clusters, support simultaneous search of a single kind of resource or multiple kinds of resources existing in multiple clusters.
* [admiral](https://github.com/istio-ecosystem/admiral) ⭐ 639 | 🐛 21 | 🌐 Go | 📅 2025-10-15 - Admiral provides automatic configuration generation, syncing and service discovery for multicluster Istio service mesh.
* [skydns](https://github.com/skynetservices/skydns1) ⭐ 522 | 🐛 5 | 🌐 Go | 📅 2017-07-08 - DNS for skynet or any other service discovery.
* [rotor](https://github.com/turbinelabs/rotor) ⭐ 306 | 🐛 3 | 🌐 Go | 📅 2019-08-08 - Rotor is a fast, lightweight bridge between your service discovery and the configuration APIs of Envoy. Rotor supports Kubernetes, Consul, AWS (EC2 and ECS), DC/OS, flat files, and even other EDS/CDS implementations.
* [kosmos](https://github.com/kosmos-io/kosmos) ⭐ 258 | 🐛 85 | 🌐 Go | 📅 2025-07-04 - The limitless expansion of Kubernetes. Make Kubernetes without boundaries.
* [steward](https://github.com/deis/steward) ⭐ 153 | 🐛 7 | 🌐 Go | 📅 2017-05-10 - The Kubernetes-native Service Broker.
* [open-service-broker-sdk](https://github.com/openshift/open-service-broker-sdk) ⭐ 30 | 🐛 0 | 🌐 Go | 📅 2017-08-11 - A starting point for creating service brokers implementing the Open Service Broker API.

## Networking & Connectivity

* [pingora](https://github.com/cloudflare/pingora) ⭐ 27,258 | 🐛 313 | 🌐 Rust | 📅 2026-08-07 - A library for building fast, reliable and evolvable network services.
* [cilium](https://github.com/cilium/cilium) ⭐ 24,996 | 🐛 1,121 | 🌐 Go | 📅 2026-08-23 - API-aware Networking and Security using eBPF and XDP.
* [flannel](https://github.com/coreos/flannel) ⭐ 9,522 | 🐛 26 | 🌐 Go | 📅 2026-08-17 - Flannel is a network fabric for containers, designed for Kubernetes.
* [weave](https://github.com/weaveworks/weave) ⚠️ Archived - Simple, resilient multi-host Docker networking and more.
* [cni](https://github.com/containernetworking/cni) ⭐ 6,101 | 🐛 156 | 🌐 Go | 📅 2026-08-13 - Container Network Interface - networking for Linux containers.
* [ziti](https://github.com/openziti/ziti) ⭐ 4,354 | 🐛 283 | 🌐 Go | 📅 2026-08-22 - The parent project for OpenZiti. Here you will find the executables for a fully zero trust, application embedded, programmable network.
* [hubble](https://github.com/cilium/hubble) ⭐ 4,311 | 🐛 44 | 🌐 Makefile | 📅 2026-08-18 - Hubble - Network, Service & Security Observability for Kubernetes.
* [multus](https://github.com/k8snetworkplumbingwg/multus-cni) ⭐ 2,936 | 🐛 24 | 🌐 Go | 📅 2026-08-20 - A CNI meta-plugin for multi-homed pods in Kubernetes.
* [submariner](https://github.com/submariner-io/submariner) ⭐ 2,686 | 🐛 29 | 🌐 Go | 📅 2026-08-22 - Connect all your Kubernetes clusters, no matter where they are in the world.
* [kube-router](https://github.com/cloudnativelabs/kube-router) ⭐ 2,496 | 🐛 14 | 🌐 Go | 📅 2026-08-22 - Kube-router, a turnkey solution for Kubernetes networking.
* [kube-ovn](https://github.com/alauda/kube-ovn) ⭐ 2,393 | 🐛 79 | 🌐 Go | 📅 2026-08-23 - Kube-OVN, a Kubernetes network fabric for enterprises that is rich in functions and easy in operations.
* [antrea](https://github.com/antrea-io/antrea) ⭐ 1,807 | 🐛 201 | 🌐 Go | 📅 2026-08-23 - Antrea is a Kubernetes networking based on Open vSwitch.
* [matchbox](https://github.com/poseidon/matchbox) ⭐ 1,424 | 🐛 5 | 🌐 Go | 📅 2026-08-23 - Network boot and provision Container Linux clusters (e.g. etcd3, Kubernetes, more).
* [bumblebee](https://github.com/solo-io/bumblebee) ⭐ 1,303 | 🐛 29 | 🌐 C | 📅 2025-04-17 - Get eBPF programs running from the cloud to the kernel in 1 line of bash.
* [spiderpool](https://github.com/spidernet-io/spiderpool) ⭐ 671 | 🐛 109 | 🌐 Go | 📅 2026-08-21 - Underlay and RDMA network solution of the Kubernetes, for bare metal, VM and any public cloud.
* [cni-genie](https://github.com/cni-genie/CNI-Genie) ⚠️ Archived - CNI-Genie for choosing pod network of your choice during deployment time. Supported pod networks - Calico, Flannel, Romana, Weave.
* [kubecdn](https://github.com/ilhaan/kubeCDN) ⭐ 415 | 🐛 0 | 🌐 HCL | 📅 2019-03-27 - Self-hosted CDN based on Kubernetes.
* [kubeslice](https://github.com/kubeslice/kubeslice) ⭐ 190 | 🐛 45 | 🌐 Mustache | 📅 2025-12-30 - KubeSlice enables Kubernetes pods and services to communicate seamlessly across clusters, clouds, edges, and data centers by creating logical application boundaries known as Slices.
* [knitter](https://github.com/ZTE/Knitter) ⭐ 154 | 🐛 11 | 🌐 Go | 📅 2020-09-16 - Kubernetes network solution.
* [istio-cni](https://github.com/istio/cni) ⚠️ Archived - Istio CNI to setup kubernetes pod namespaces to redirect traffic to sidecar proxy.
* [calico](https://github.com/projectcalico) - Cloud native networking and network security.
* [contiv](https://github.com/contiv) - Container networking for various use cases.

## Load Balancing & Ingress

* [caddy](https://github.com/caddyserver/caddy) ⭐ 75,135 | 🐛 273 | 🌐 Go | 📅 2026-08-22 - Fast, cross-platform HTTP/2 web server with automatic HTTPS.
* [traefik](https://github.com/containous/traefik) ⭐ 64,541 | 🐛 916 | 🌐 Go | 📅 2026-08-21 - Træfik, a modern reverse proxy.
* [nginx](https://github.com/nginx/nginx) ⭐ 31,472 | 🐛 471 | 🌐 C | 📅 2026-08-21 - Nginx is an HTTP and reverse proxy server, a mail proxy server, and a generic TCP/UDP proxy server, originally written by Igor Sysoev.
* [envoy](https://github.com/envoyproxy/envoy) ⭐ 28,811 | 🐛 1,882 | 🌐 C++ | 📅 2026-08-22 - C++ front/service proxy.
* [cloudflared](https://github.com/cloudflare/cloudflared) ⭐ 15,345 | 🐛 531 | 🌐 Go | 📅 2026-08-21 - Cloudflare Tunnel client (formerly Argo Tunnel).
* [reverse-proxy](https://github.com/microsoft/reverse-proxy) ⭐ 9,602 | 🐛 191 | 🌐 C# | 📅 2026-08-17 - A toolkit for developing high-performance HTTP reverse proxy applications.
* [metallb](https://github.com/metallb/metallb) ⭐ 8,330 | 🐛 102 | 🌐 Go | 📅 2026-08-17 - A network load-balancer implementation for Kubernetes using standard routing protocols.
* [haproxy](https://github.com/haproxy/haproxy) ⭐ 6,796 | 🐛 380 | 🌐 C | 📅 2026-08-21 - HAProxy is a free, very fast and reliable solution offering high availability, load balancing, and proxying for TCP and HTTP-based applications.
* [katran](https://github.com/facebookincubator/katran) ⭐ 5,299 | 🐛 0 | 🌐 C | 📅 2026-08-22 - A high performance layer 4 load balancer.
* [nginx-kubernetes-ingress](https://github.com/nginxinc/kubernetes-ingress) ⭐ 5,067 | 🐛 256 | 🌐 Go | 📅 2026-08-23 - NGINX and NGINX Plus Ingress Controllers for Kubernetes.
* [ribbon](https://github.com/Netflix/ribbon) ⭐ 4,614 | 🐛 216 | 🌐 Java | 📅 2025-12-17 - Ribbon is a Inter Process Communication (remote procedure calls) library with built in software load balancers. The primary usage model involves REST calls with various serialization scheme support.
* [mosn](https://github.com/mosn/mosn) ⭐ 4,508 | 🐛 298 | 🌐 Go | 📅 2026-07-14 - MOSN is a cloud native proxy for edge or service mesh.
* [contour](https://github.com/projectcontour/contour) ⭐ 3,945 | 🐛 124 | 🌐 HTML | 📅 2026-08-18 - Contour is a Kubernetes ingress controller for Lyft's Envoy proxy.
* [skipper](https://github.com/zalando/skipper) ⭐ 3,318 | 🐛 314 | 🌐 Go | 📅 2026-08-21 - An HTTP router and reverse proxy for service composition, including use cases like Kubernetes Ingress.
* [kong/kubernetes-ingress-controller](https://github.com/Kong/kubernetes-ingress-controller) ⭐ 2,408 | 🐛 277 | 🌐 Go | 📅 2026-08-20 - Deploy Kong in a native Kubernetes Ingress Controller.
* [gobetween](https://github.com/yyyar/gobetween) ⭐ 1,986 | 🐛 102 | 🌐 Go | 📅 2025-08-16 - Modern & minimalistic load balancer for the Сloud era.
* [loxilb](https://github.com/loxilb-io/loxilb) ⭐ 1,871 | 🐛 30 | 🌐 Go | 📅 2026-08-19 - eBPF powered cloud-native load-balancer providing efficient externalLB, clusterIP and nodePort services for Kubernetes.
* [inlets-operator](https://github.com/inlets/inlets-operator) ⭐ 1,436 | 🐛 8 | 🌐 Go | 📅 2026-08-18 - Add public LoadBalancers to your local Kubernetes clusters.
* [voyager](https://github.com/voyagermesh/voyager) ⭐ 1,351 | 🐛 118 | 🌐 Shell | 📅 2026-05-16 - Secure Ingress Controller for Kubernetes.
* [apisix-ingress-controller](https://github.com/apache/apisix-ingress-controller) ⭐ 1,143 | 🐛 48 | 🌐 Go | 📅 2026-08-18 - Ingress controller for K8s.
* [dev-proxy](https://github.com/microsoft/dev-proxy) ⭐ 823 | 🐛 46 | 🌐 C# | 📅 2026-08-19 - Dev Proxy is a command line tool that simulates real world behaviors of HTTP APIs, including Microsoft Graph, locally.
* [gimbal](https://github.com/projectcontour/gimbal) ⚠️ Archived - Heptio Gimbal is an ingress load balancing platform capable of routing traffic to multiple Kubernetes and OpenStack clusters. Built by Heptio in partnership with Actapio.
* [func-e](https://github.com/tetratelabs/func-e) ⭐ 384 | 🐛 0 | 🌐 Go | 📅 2026-08-17 - func-e (pronounced funky) makes running Envoy easy.
* [kedge](https://github.com/improbable-eng/kedge) ⚠️ Archived - kEdge - Kubernetes Edge Proxy for gRPC and HTTP Microservices.
* [kong-ingress](https://github.com/koli/kong-ingress) ⚠️ Archived - A Kubernetes Ingress for Kong.

## RPC Frameworks

* [brpc](https://github.com/apache/incubator-brpc) ⭐ 17,592 | 🐛 464 | 🌐 C++ | 📅 2026-08-23 - Most common RPC framework used throughout Baidu, with 600,000+ instances and 500+ kinds of services, called "baidu-rpc" inside Baidu.
* [thrift](https://github.com/apache/thrift) ⭐ 10,954 | 🐛 14 | 🌐 C++ | 📅 2026-08-22 - Apache thrift.
* [tars](https://github.com/TarsCloud/Tars) ⭐ 10,076 | 🐛 48 | 🌐 C++ | 📅 2026-07-18 - Tars is a high-performance RPC framework based on name service and Tars protocol, also integrated administration platform, and implemented hosting-service via flexible schedule.
* [finagle](https://github.com/twitter/finagle) ⭐ 8,864 | 🐛 65 | 🌐 Scala | 📅 2026-08-13 - A fault tolerant, protocol-agnostic RPC system.
* [proxygen](https://github.com/facebook/proxygen) ⭐ 8,374 | 🐛 39 | 🌐 C++ | 📅 2026-08-22 - A collection of C++ HTTP libraries including an easy to use HTTP server.
* [kitex](https://github.com/cloudwego/kitex) ⭐ 8,025 | 🐛 68 | 🌐 Go | 📅 2026-08-21 - A high-performance and strong-extensibility Golang RPC framework that helps developers build microservices.
* [sofa-rpc](https://github.com/sofastack/sofa-rpc) ⭐ 3,921 | 🐛 28 | 🌐 Java | 📅 2026-08-08 - SOFARPC is a high-performance, high-extensibility, production-level Java RPC framework.
* [sofa-bolt](https://github.com/sofastack/sofa-bolt) ⭐ 2,503 | 🐛 39 | 🌐 Java | 📅 2025-12-19 - SOFABolt is a lightweight, easy to use and high performance remoting framework based on Netty.
* [drpc](https://github.com/storj/drpc) ⭐ 1,629 | 🐛 13 | 🌐 Go | 📅 2026-08-18 - drpc is a lightweight, drop-in replacement for gRPC.
* [grpc](https://github.com/grpc) - A high performance, open source, general-purpose RPC framework.
* [rsocket](https://github.com/rsocket) - Streaming message protocol with Reactive Extension/Stream semantics.

## Runtimes & Platforms

* [moby](https://github.com/moby/moby) ⭐ 71,992 | 🐛 3,899 | 🌐 Go | 📅 2026-08-22 - Moby Project - a collaborative project for the container ecosystem to assemble container-based systems.
* [podman](https://github.com/containers/podman) ⭐ 32,666 | 🐛 1,132 | 🌐 Go | 📅 2026-08-21 - A tool for managing OCI containers and pods.
* [lima](https://github.com/AkihiroSuda/lima) ⭐ 21,736 | 🐛 538 | 🌐 Go | 📅 2026-08-21 - Linux virtual machines, on macOS (aka "Linux-on-Mac", "macOS subsystem for Linux", "containerd for Mac", unofficially).
* [containerd](https://github.com/containerd/containerd) ⭐ 21,147 | 🐛 445 | 🌐 Go | 📅 2026-08-22 - An open and reliable container runtime.
* [gvisor](https://github.com/google/gvisor) ⭐ 19,141 | 🐛 793 | 🌐 Go | 📅 2026-08-22 - Sandboxed Container Runtime.
* [rkt](https://github.com/rkt/rkt) ⚠️ Archived - Rkt is a pod-native container engine for Linux. It is composable, secure, and built on standards.
* [agones](https://github.com/googleforgames/agones) ⭐ 6,983 | 🐛 62 | 🌐 Go | 📅 2026-08-19 - Dedicated Game Server Hosting and Scaling for Multiplayer Games on Kubernetes.
* [spin](https://github.com/fermyon/spin) ⭐ 6,502 | 🐛 266 | 🌐 Rust | 📅 2026-08-20 - Spin is an open source framework for building and running fast, secure, and composable cloud microservices with WebAssembly.
* [wazero](https://github.com/tetratelabs/wazero) ⭐ 6,336 | 🐛 40 | 🌐 Go | 📅 2026-08-19 - The zero dependency WebAssembly runtime for Go developers.
* [wasm-micro-runtime](https://github.com/bytecodealliance/wasm-micro-runtime) ⭐ 6,072 | 🐛 604 | 🌐 C | 📅 2026-08-22 - WebAssembly Micro Runtime (WAMR).
* [cri-o](https://github.com/cri-o/cri-o) ⭐ 5,653 | 🐛 141 | 🌐 Go | 📅 2026-08-21 - Open Container Initiative-based implementation of Kubernetes Container Runtime Interface.
* [pouch](https://github.com/alibaba/pouch) ⭐ 4,645 | 🐛 10 | 🌐 Go | 📅 2024-08-22 - Pouch is an open-source project created to promote the container technology movement.
* [crun](https://github.com/containers/crun) ⭐ 4,065 | 🐛 53 | 🌐 C | 📅 2026-08-19 - A fast and lightweight fully featured OCI runtime and C library for running containers.
* [img](https://github.com/genuinetools/img) ⭐ 3,989 | 🐛 110 | 🌐 Go | 📅 2024-05-19 - Standalone, daemon-less, unprivileged Dockerfile and OCI compatible container image builder.
* [krustlet](https://github.com/deislabs/krustlet) ⭐ 3,601 | 🐛 137 | 🌐 Rust | 📅 2023-10-02 - Kubernetes Rust Kubelet.
* [firecracker-containerd](https://github.com/firecracker-microvm/firecracker-containerd) ⭐ 2,907 | 🐛 95 | 🌐 Go | 📅 2026-08-17 - firecracker-containerd enables containerd to manage containers as Firecracker microVMs.
* [wasmcloud](https://github.com/wasmCloud/wasmCloud) ⭐ 2,420 | 🐛 65 | 🌐 Rust | 📅 2026-08-22 - wasmCloud is a universal host runtime for actors built with WebAssembly and capability providers.
* [hyperd](https://github.com/hyperhq/hyperd) ⚠️ Archived - HyperContainer Daemon.
* [kuasar](https://github.com/kuasar-io/kuasar) ⭐ 1,443 | 🐛 29 | 🌐 Rust | 📅 2026-06-05 - An efficient container runtime that provides cloud-native, all-scenario multiple sandbox container solutions.
* [openchoreo](https://github.com/openchoreo/openchoreo) ⭐ 1,396 | 🐛 254 | 🌐 Go | 📅 2026-08-21 - OpenChoreo is a developer platform for Kubernetes.
* [runwasi](https://github.com/containerd/runwasi) ⭐ 1,329 | 🐛 66 | 🌐 Rust | 📅 2026-08-23 - Facilitates running Wasm/WASI workloads managed by containerd.
* [railcar](https://github.com/oracle/railcar) ⚠️ Archived - RailCar: Rust implementation of the Open Containers Initiative oci-runtime.
* [virtlet](https://github.com/Mirantis/virtlet) ⭐ 766 | 🐛 7 | 🌐 Go | 📅 2020-04-18 - Kubernetes CRI implementation for running VM workloads.
* [frakti](https://github.com/kubernetes/frakti) ⚠️ Archived - The hypervisor-based container runtime for Kubernetes.
* [mocker](https://github.com/us/mocker) ⭐ 332 | 🐛 2 | 🌐 Swift | 📅 2026-08-18 - Docker-compatible container CLI for macOS, built on Apple's Containerization framework.
* [containerd-wasm-shims](https://github.com/deislabs/containerd-wasm-shims) ⚠️ Archived - Containerd shims for running WebAssembly workloads in Kubernetes.
* [kubernetes-lts](https://github.com/klts-io/kubernetes-lts) ⭐ 216 | 🐛 49 | 🌐 Shell | 📅 2026-04-22 - Kubernetes LTS(long term support).
* [den](https://github.com/us/den) ⭐ 15 | 🐛 0 | 🌐 Go | 📅 2026-06-18 - Self-hosted sandbox runtime for AI agents with isolated Docker containers, cgroup v2 memory management, and dynamic pressure monitoring.
* [katacontainers](https://katacontainers.io/) - Kata Containers is a new open source project building extremely lightweight virtual machines that seamlessly plug into the containers ecosystem.

## Workload Orchestration & Scheduling

* [kubernetes](https://github.com/kubernetes/kubernetes) ⭐ 124,915 | 🐛 3,010 | 🌐 Go | 📅 2026-08-21 - Production-Grade Container Scheduling and Management.
* [compose](https://github.com/docker/compose) ⭐ 38,046 | 🐛 95 | 🌐 Go | 📅 2026-08-21 - Define and run multi-container applications with Docker.
* [conductor](https://github.com/Netflix/conductor) ⚠️ Archived - Conductor is a microservices orchestration engine.
* [cluster-autoscaler](https://github.com/kubernetes/autoscaler) ⭐ 8,943 | 🐛 313 | 🌐 Go | 📅 2026-08-23 - Kubernetes Cluster Autoscaler for dynamic node scaling across cloud providers.
* [serf](https://github.com/hashicorp/serf) ⭐ 6,068 | 🐛 106 | 🌐 Go | 📅 2026-08-04 - Service orchestration and management tool by hashicorp.
* [deis](https://github.com/deis/deis) ⚠️ Archived - Deis v1, the CoreOS and Docker PaaS: Your PaaS. Your Rules.
* [volcano](https://github.com/volcano-sh/volcano) ⭐ 5,880 | 🐛 807 | 🌐 Go | 📅 2026-08-20 - A Kubernetes Native Batch System (Project under CNCF).
* [swarm](https://github.com/docker/classicswarm) ⚠️ Archived - Swarm: a Docker-native clustering system.
* [karmada](https://github.com/karmada-io/karmada) ⭐ 5,574 | 🐛 839 | 🌐 Go | 📅 2026-08-21 - Open, Multi-Cloud, Multi-Cluster Kubernetes Orchestration.
* [descheduler](https://github.com/kubernetes-sigs/descheduler) ⭐ 5,490 | 🐛 62 | 🌐 Go | 📅 2026-08-18 - Descheduler for Kubernetes.
* [mesos](https://github.com/apache/mesos) ⭐ 5,367 | 🐛 11 | 🌐 C++ | 📅 2026-05-15 - Apache Mesos abstracts CPU, memory, storage, and other compute resources away from machines (physical or virtual), enabling fault-tolerant and elastic distributed systems to easily be built and run effectively.
* [kruise](https://github.com/openkruise/kruise) ⭐ 5,323 | 🐛 85 | 🌐 Go | 📅 2026-08-18 - Automate application workloads management on Kubernetes.
* [hami](https://github.com/Project-HAMi/HAMi) ⭐ 4,418 | 🐛 50 | 🌐 Go | 📅 2026-08-21 - Heterogeneous GPU Sharing on Kubernetes.
* [marathon](https://github.com/mesosphere/marathon) ⚠️ Archived - Deploy and manage containers (including Docker) on top of Apache Mesos at scale.
* [service-fabric](https://github.com/Microsoft/service-fabric) ⭐ 3,063 | 🐛 845 | 🌐 C++ | 📅 2026-08-17 - Service Fabric is a distributed systems platform for packaging, deploying, and managing stateless and stateful distributed applications and containers at large scale.
* [kueue](https://github.com/kubernetes-sigs/kueue) ⭐ 2,897 | 🐛 720 | 🌐 Go | 📅 2026-08-23 - Kubernetes-native Job Queueing.
* [kcp](https://github.com/kcp-dev/kcp) ⭐ 2,815 | 🐛 143 | 🌐 Go | 📅 2026-08-21 - Multi-tenant control plane for running many virtual Kubernetes clusters.
* [fleet](https://github.com/coreos/fleet) ⚠️ Archived - Fleet ties together systemd and etcd into a distributed init system.
* [koordinator](https://github.com/koordinator-sh/koordinator) ⭐ 1,739 | 🐛 308 | 🌐 Go | 📅 2026-08-23 - QoS based scheduling system for hybrid orchestration workloads on Kubernetes, bringing workloads the best layout and status.
* [eks-distro](https://github.com/aws/eks-distro) ⭐ 1,456 | 🐛 90 | 🌐 Shell | 📅 2026-08-19 - Amazon EKS Distro (EKS-D) is a Kubernetes distribution based on and used by Amazon Elastic Kubernetes Service (EKS) to create reliable and secure Kubernetes clusters.
* [ocm](https://github.com/open-cluster-management-io/OCM) ⭐ 1,076 | 🐛 56 | 🌐 Go | 📅 2026-08-17 - The open-cluster-management.io project is focused on enabling end-to-end visibility and control across your Kubernetes clusters.
* [blox](https://github.com/blox/blox) ⚠️ Archived - Open source tools for building custom schedulers on Amazon ECS.
* [kubeadmiral](https://github.com/kubewharf/kubeadmiral) ⭐ 930 | 🐛 43 | 🌐 Go | 📅 2026-05-11 - Multi-cluster Kubernetes Orchestration.
* [vamp](https://github.com/magneticio/vamp) ⚠️ Archived - Vamp - canary releasing and autoscaling for microservice systems.
* [swan](https://github.com/Dataman-Cloud/swan) ⭐ 405 | 🐛 19 | 🌐 Go | 📅 2018-01-29 - A Distributed, Highly Available Mesos Scheduler, Inspired by the design of Google Borg.
* [alameda](https://github.com/containers-ai/alameda) ⭐ 11 | 🐛 1 | 📅 2021-01-08 - Intelligent Resources Orchestrator for Kubernetes by using machine learning.
* [dc/os](https://github.com/dcos) - Datacenter Operating System.
* [supergiant](https://github.com/supergiant/control) - Automatically scale hardware and easily run stateful applications using Kubernetes.

## Serverless Platforms

* [serverless](https://github.com/serverless/serverless) ⭐ 46,918 | 🐛 1,222 | 🌐 JavaScript | 📅 2026-08-20 - Serverless Framework – Build web, mobile and IoT applications with serverless architectures using AWS Lambda, Azure Functions, Google CloudFunctions & more!
* [firecracker](https://github.com/firecracker-microvm/firecracker) ⭐ 36,220 | 🐛 112 | 🌐 Rust | 📅 2026-08-21 - Secure and fast microVMs for serverless computing.
* [openfaas](https://github.com/openfaas/faas) ⭐ 26,228 | 🐛 31 | 🌐 Go | 📅 2026-07-02 - OpenFaaS - Serverless Functions Made Simple for Docker & Kubernetes.
* [dapr](https://github.com/dapr/dapr) ⭐ 26,026 | 🐛 431 | 🌐 Go | 📅 2026-08-21 - Dapr is a portable, event-driven, runtime for building distributed applications across cloud and edge.
* [thanos](https://github.com/thanos-io/thanos) ⭐ 14,181 | 🐛 880 | 🌐 Go | 📅 2026-08-22 - Highly available Prometheus setup with long term storage capabilities.
* [keda](https://github.com/kedacore/keda) ⭐ 10,462 | 🐛 233 | 🌐 Go | 📅 2026-08-23 - KEDA is a Kubernetes-based Event Driven Autoscaling component. It provides event driven scale for any container running in Kubernetes.
* [fission](https://github.com/fission/fission) ⭐ 8,910 | 🐛 47 | 🌐 Go | 📅 2026-08-23 - Fast Serverless Functions for Kubernetes.
* [laf](https://github.com/labring/laf) ⭐ 7,553 | 🐛 46 | 🌐 TypeScript | 📅 2026-07-30 - Laf is a cloud development platform offering ready-to-use resources like cloud functions, databases, and storage. It empowers developers to quickly unleash their creativity.
* [kubeless](https://github.com/kubeless/kubeless) ⚠️ Archived - Kubernetes Native Serverless Framework.
* [serving](https://github.com/knative/serving) ⭐ 6,085 | 🐛 163 | 🌐 Go | 📅 2026-08-21 - Kubernetes-based, scale-to-zero, request-driven compute.
* [fn](https://github.com/fnproject/fn) ⭐ 5,944 | 🐛 159 | 🌐 Go | 📅 2026-06-08 - The container native, cloud agnostic serverless platform.
* [spec](https://github.com/cloudevents/spec) ⭐ 5,873 | 🐛 16 | 🌐 Python | 📅 2026-07-23 - CloudEvents Specification.
* [nuclio](https://github.com/nuclio/nuclio) ⭐ 5,748 | 🐛 116 | 🌐 Go | 📅 2026-08-19 - High-Performance Serverless event and data processing platform.
* [tau](https://github.com/taubyte/tau) ⭐ 5,132 | 🐛 9 | 🌐 Go | 📅 2026-08-16 - Easily build Cloud Computing Platforms with features like Serverless WebAssembly Functions, Frontend Hosting, Object Storage, K/V Database, and Pub-Sub Messaging.
* [ironfunctions](https://github.com/iron-io/functions) ⭐ 3,215 | 🐛 94 | 🌐 Go | 📅 2023-09-15 - IronFunctions - the serverless microservices platform.
* [fx](https://github.com/metrue/fx) ⭐ 2,228 | 🐛 85 | 🌐 Go | 📅 2023-10-24 - Poor man's serverless framework based on Docker, Function as a Service with painless.
* [faas-netes](https://github.com/openfaas/faas-netes) ⭐ 2,170 | 🐛 40 | 🌐 Go | 📅 2026-08-21 - Enable Kubernetes as a backend for Functions as a Service (OpenFaaS).
* [serverless-devs](https://github.com/Serverless-Devs/Serverless-Devs) ⭐ 1,830 | 🐛 67 | 🌐 TypeScript | 📅 2026-02-01  - Serverless Devs developer tool (Serverless Devs 开发者工具).
* [openfunction](https://github.com/OpenFunction/OpenFunction) ⭐ 1,658 | 🐛 102 | 🌐 Go | 📅 2024-06-19 - Cloud Native Function-as-a-Service Platform.
* [eventing](https://github.com/knative/eventing) ⭐ 1,552 | 🐛 116 | 🌐 Go | 📅 2026-08-21 - Open source specification and implementation of Knative event binding and delivery.
* [layotto](https://github.com/mosn/layotto) ⭐ 852 | 🐛 49 | 🌐 Go | 📅 2026-08-22 - A fast and efficient cloud native application runtime.
* [riff](https://github.com/projectriff/riff) ⚠️ Archived - Riff is for functions.
* [easyfaas](https://github.com/baidu/EasyFaaS) ⭐ 613 | 🐛 8 | 🌐 Go | 📅 2022-10-20 - EasyFaaS 是一个依赖轻、适配性强、资源占用少、无状态且高性能的函数计算服务引擎。
* [sqoop](https://github.com/solo-io/sqoop) ⭐ 530 | 🐛 23 | 🌐 Go | 📅 2020-06-17 - The GraphQL Engine powered by Gloo.
* [dispatch](https://github.com/vmware/dispatch) ⚠️ Archived - Dispatch is a framework for deploying and managing serverless style applications.
* [osiris](https://github.com/deislabs/osiris) ⚠️ Archived - A general purpose, scale-to-zero component for Kubernetes.
* [booster](https://github.com/boostercloud/booster) ⭐ 448 | 🐛 285 | 🌐 TypeScript | 📅 2026-06-16 - Booster is a framework for building and deploying reliable and scalable event-driven serverless applications.
* [funktion](https://github.com/funktionio/funktion/) ⭐ 296 | 🐛 11 | 🌐 Go | 📅 2017-11-29 - A CLI tool for working with funktion.
* [knative-lambda-runtime](https://github.com/triggermesh/knative-lambda-runtime) ⚠️ Archived - Running AWS Lambda Functions on Knative/Kubernetes Clusters.
* [firecamp](https://github.com/cloudstax/firecamp) ⭐ 215 | 🐛 22 | 🌐 Go | 📅 2024-04-11 - Serverless Platform for the stateful services.
* [knix](https://github.com/knix-microfunctions/knix) ⚠️ Archived - KNIX MicroFunctions is a serverless computing platform that combines container-based resource isolation with a lightweight execution model using processes to significantly improve resource efficiency and decrease the function startup latency. KNIX MicroFunctions works in Knative as well as bare metal or virtual machine-based environments.
* [openwhisk](http://openwhisk.apache.org/) - Apache OpenWhisk (Incubating) is a serverless, open source cloud platform that executes functions in response to events at any scale.

## Kubernetes Operators

* [prometheus-operator](https://github.com/coreos/prometheus-operator) ⭐ 9,973 | 🐛 306 | 🌐 Go | 📅 2026-08-21 - Prometheus Operator creates/configures/manages Prometheus clusters atop Kubernetes.
* [kubebuilder](https://github.com/kubernetes-sigs/kubebuilder) ⭐ 9,293 | 🐛 68 | 🌐 Go | 📅 2026-08-20 - Kubebuilder - SDK for building Kubernetes APIs using CRDs.
* [operator-sdk](https://github.com/operator-framework/operator-sdk) ⭐ 7,674 | 🐛 64 | 🌐 Go | 📅 2026-08-19 - SDK for building Kubernetes applications. Provides high level APIs, useful abstractions, and project scaffolding.
* [kubevirt](https://github.com/kubevirt/kubevirt) ⭐ 7,018 | 🐛 574 | 🌐 Go | 📅 2026-08-22 - Kubernetes Virtualization Operator with API and runtime in order to define and manage virtual machines.
* [strimzi-kafka-operator](https://github.com/strimzi/strimzi-kafka-operator) ⭐ 5,914 | 🐛 160 | 🌐 Java | 📅 2026-08-23 - Apache Kafka running on Kubernetes.
* [kubeoperator](https://github.com/KubeOperator/KubeOperator) ⚠️ Archived - KubeOperator 是一个开源的轻量级 Kubernetes 发行版，专注于帮助企业规划、部署和运营生产级别的 K8s 集群。
* [spark-on-k8s-operator](https://github.com/GoogleCloudPlatform/spark-on-k8s-operator) ⭐ 3,148 | 🐛 114 | 🌐 Python | 📅 2026-08-22 - Kubernetes operator for managing the lifecycle of Apache Spark applications on Kubernetes.
* [keel](https://github.com/keel-hq/keel) ⭐ 2,722 | 🐛 210 | 🌐 Go | 📅 2026-08-21 - Kubernetes Operator to automate Helm, DaemonSet, StatefulSet & Deployment updates.
* [kopf](https://github.com/nolar/kopf) ⭐ 2,632 | 🐛 183 | 🌐 Python | 📅 2026-06-03 - A Python framework to write Kubernetes operators in just few lines of code.
* [operator-lifecycle-manager](https://github.com/operator-framework/operator-lifecycle-manager) ⭐ 1,863 | 🐛 7 | 🌐 Go | 📅 2026-08-19 - A management framework for extending Kubernetes with Operators.
* [kube-green](https://github.com/kube-green/kube-green) ⭐ 1,369 | 🐛 54 | 🌐 Go | 📅 2026-08-19 - A Kubernetes operator to reduce CO2 footprint of your clusters.
* [kubegres](https://github.com/reactive-tech/kubegres) ⭐ 1,350 | 🐛 80 | 🌐 Go | 📅 2025-01-04 - Kubegres is a Kubernetes operator allowing to deploy one or many clusters of PostgreSql instances and manage databases replication, failover and backup.
* [tidb-operator](https://github.com/pingcap/tidb-operator) ⭐ 1,336 | 🐛 397 | 🌐 Go | 📅 2026-08-21 - TiDB operator creates and manages TiDB clusters running in Kubernetes.
* [kudo](https://github.com/kudobuilder/kudo) ⭐ 1,215 | 🐛 191 | 🌐 Go | 📅 2023-08-22 - Kubernetes Universal Declarative Operator (KUDO).
* [kaito](https://github.com/Azure/kaito) ⭐ 1,003 | 🐛 59 | 🌐 Go | 📅 2026-08-23 - Kubernetes AI Toolchain Operator.
* [k0smotron](https://github.com/k0sproject/k0smotron) ⭐ 733 | 🐛 51 | 🌐 Go | 📅 2026-08-18 - k0smotron is a powerful open-source tool for the efficient management of k0s Kubernetes clusters.
* [vault-secrets-operator](https://github.com/ricoberger/vault-secrets-operator) ⭐ 685 | 🐛 15 | 🌐 Go | 📅 2026-08-13 - Create Kubernetes secrets from Vault for a secure GitOps based workflow.
* [fabedge](https://github.com/FabEdge/fabedge) ⭐ 529 | 🐛 2 | 🌐 Go | 📅 2026-07-10 - Secure Edge Networking Based On Kubernetes And KubeEdge.
* [kubedirector](https://github.com/bluek8s/kubedirector) ⭐ 409 | 🐛 85 | 🌐 Go | 📅 2026-03-26 - Kubernetes Director (aka KubeDirector) for deploying and managing stateful applications on Kubernetes.
* [kubecarrier](https://github.com/kubermatic/kubecarrier) ⚠️ Archived - KubeCarrier - Service Management at Scale.
* [eunomia](https://github.com/KohlsTechnology/eunomia) ⚠️ Archived - A GitOps Operator for Kubernetes.
* [gateway-operator](https://github.com/kong/gateway-operator) ⭐ 108 | 🐛 191 | 🌐 Go | 📅 2026-08-21 - Kong Gateway Operator is a Kubernetes Operator that can manage your Kong Ingress Controller, Kong Gateway Data Planes, or both together when running on Kubernetes.
* [kubevirtbmc](https://github.com/kubevirtbmc/kubevirtbmc) ⭐ 88 | 🐛 30 | 🌐 Go | 📅 2026-08-23 - A Kubernetes operator of virtual BMCs that provide Redfish and IPMI services for KubeVirt virtual machines.
* [agenttier](https://github.com/agenttier/agenttier) ⭐ 71 | 🐛 18 | 🌐 Go | 📅 2026-08-19 - Kubernetes-native operator that manages isolated, persistent sandboxes for human developers and AI agents through Sandbox CRDs, with built-in governance, warm-pod pool, and a streaming agent-mode REST API.
* [xline-operator](https://github.com/xline-kv/xline-operator) ⭐ 16 | 🐛 3 | 🌐 Go | 📅 2024-02-19 - A powerful tool designed to automate the process of bootstrapping, monitoring, snapshotting, and recovering an xline cluster on Kubernetes.
* [banzaicloud/bank-vaults](https://github.com/banzaicloud/bank-vaults) ⚠️ Archived - A Vault swiss-army knife: a K8s operator, Go client with automatic token renewal, automatic configuration, multiple unseal options and more. A CLI tool to init, unseal and configure Vault (auth methods, secret engines). Direct secret injection into Pods.
* [jupyter-notebook-validator-operator](https://github.com/tosin2013/jupyter-notebook-validator-operator) ⭐ 3 | 🐛 19 | 🌐 Go | 📅 2026-04-22 - Validates Jupyter notebooks on Kubernetes/OpenShift (Papermill, golden outputs, Git, model validation).

## Edge & IoT

* [k3s](https://github.com/k3s-io/k3s) ⭐ 33,790 | 🐛 70 | 🌐 Go | 📅 2026-08-22 - Lightweight Kubernetes.
* [kubeedge](https://github.com/kubeedge/kubeedge) ⭐ 7,556 | 🐛 1,279 | 🌐 Go | 📅 2026-08-18 - Kubernetes Native Edge Computing Framework (project under CNCF).
* [k0s](https://github.com/k0sproject/k0s) ⭐ 6,443 | 🐛 208 | 🌐 Go | 📅 2026-08-21 - Zero Friction Kubernetes.
* [openyurt](https://github.com/openyurtio/openyurt) ⭐ 2,000 | 🐛 118 | 🌐 Go | 📅 2026-08-18 - Extending your native Kubernetes to edge(project under CNCF).
* [baetyl](https://github.com/baetyl/baetyl) ⭐ 1,900 | 🐛 7 | 🌐 Go | 📅 2024-05-11 - Extend cloud computing, data and service seamlessly to edge devices.
* [kairos](https://github.com/kairos-io/kairos) ⭐ 1,806 | 🐛 293 | 🌐 Go | 📅 2026-08-22 - The immutable Linux meta-distribution for edge Kubernetes.
* [iotedge](https://github.com/Azure/iotedge) ⭐ 1,508 | 🐛 95 | 🌐 C# | 📅 2026-08-21 - The IoT Edge OSS project.
* [akri](https://github.com/project-akri/akri) ⭐ 1,259 | 🐛 89 | 🌐 Rust | 📅 2026-08-01 - A Kubernetes Resource Interface for the Edge.
* [superedge](https://github.com/superedge/superedge) ⭐ 1,069 | 🐛 39 | 🌐 Go | 📅 2024-02-20 - An edge-native container management system for edge computing.
* [eliot](https://github.com/ernoaapa/eliot) ⭐ 268 | 🐛 10 | 🌐 Go | 📅 2018-12-18 - Open source system for managing containerized applications in IoT device.
* [octopus](https://github.com/cnrancher/octopus) ⚠️ Archived - Lightweight device management system for Kubernetes/k3s.

## Observability & Monitoring

* [grafana](https://github.com/grafana/grafana) ⭐ 76,359 | 🐛 3,331 | 🌐 TypeScript | 📅 2026-08-23 - The tool for beautiful monitoring and metric analytics & dashboards for Graphite, InfluxDB & Prometheus & More.
* [prometheus](https://github.com/prometheus/prometheus) ⭐ 65,782 | 🐛 922 | 🌐 Go | 📅 2026-08-23 - The Prometheus monitoring system and time series database.
* [kibana](https://github.com/elastic/kibana) ⭐ 21,251 | 🐛 14,229 | 🌐 TypeScript | 📅 2026-08-23 - Kibana analytics and search dashboard for Elasticsearch.
* [cadvisor](https://github.com/google/cadvisor) ⭐ 19,375 | 🐛 63 | 🌐 Go | 📅 2026-07-20 - Analyzes resource usage and performance characteristics of running containers.
* [docker-elk](https://github.com/deviantony/docker-elk) ⭐ 18,384 | 🐛 5 | 🌐 Shell | 📅 2026-08-23 - The ELK stack powered by Docker and Compose.
* [statsd](https://github.com/statsd/statsd) ⭐ 18,074 | 🐛 90 | 🌐 JavaScript | 📅 2025-05-20 - Daemon for easy but powerful stats aggregation.
* [victoriametrics](https://github.com/VictoriaMetrics/VictoriaMetrics) ⭐ 17,580 | 🐛 778 | 🌐 Go | 📅 2026-08-22 - VictoriaMetrics: fast, cost-effective monitoring solution and time series database.
* [kubeshark](https://github.com/kubeshark/kubeshark) ⭐ 12,057 | 🐛 145 | 🌐 Go | 📅 2026-08-18 - The API traffic viewer for Kubernetes providing deep visibility into all API traffic and payloads going in, out and across containers and pods inside a Kubernetes cluster. Think TCPDump and Wireshark re-invented for Kubernetes.
* [highlight](https://github.com/highlight/highlight) ⭐ 9,367 | 🐛 552 | 🌐 TypeScript | 📅 2026-08-20 - The open source, full-stack monitoring platform. Error monitoring, session replay, logging and more.
* [opentelemetry-collector](https://github.com/open-telemetry/opentelemetry-collector) ⭐ 7,443 | 🐛 706 | 🌐 Go | 📅 2026-08-21 - Vendor-neutral telemetry pipelines for metrics, logs, and traces.
* [pixie](https://github.com/pixie-io/pixie) ⭐ 6,517 | 🐛 395 | 🌐 C++ | 📅 2026-07-30 - Instant Kubernetes-Native Application Observability.
* [octant](https://github.com/vmware-tanzu/octant) ⚠️ Archived - Highly extensible platform for developers to better understand the complexity of Kubernetes clusters.
* [kube-state-metrics](https://github.com/kubernetes/kube-state-metrics) ⭐ 6,183 | 🐛 104 | 🌐 Go | 📅 2026-08-20 - Add-on agent to generate and expose cluster-level metrics.
* [scope](https://github.com/weaveworks/scope) ⭐ 5,908 | 🐛 455 | 🌐 Go | 📅 2023-07-07 - Monitoring, visualisation & management for Docker & Kubernetes.
* [cortex](https://github.com/cortexproject/cortex) ⭐ 5,851 | 🐛 358 | 🌐 Go | 📅 2026-08-22 - A multitenant, horizontally scalable Prometheus as a Service.
* [elasticsearch-hq](https://github.com/ElasticHQ/elasticsearch-HQ) ⭐ 4,994 | 🐛 82 | 🌐 JavaScript | 📅 2024-01-31 - Monitoring and Management Web Application for ElasticSearch instances and clusters.
* [parca](https://github.com/parca-dev/parca) ⭐ 4,949 | 🐛 204 | 🌐 TypeScript | 📅 2026-08-20 - Continuous profiling for analysis of CPU and memory usage, down to the line number and throughout time. Saving infrastructure cost, improving performance, and increasing reliability.
* [tetragon](https://github.com/cilium/tetragon) ⭐ 4,943 | 🐛 267 | 🌐 C | 📅 2026-08-21 - eBPF-based Security Observability and Runtime Enforcement.
* [deepflow](https://github.com/deepflowys/deepflow) ⭐ 4,237 | 🐛 269 | 🌐 Go | 📅 2026-08-21 - A highly automated observability platform.
* [metaflow](https://github.com/metaflowys/metaflow) ⭐ 4,237 | 🐛 269 | 🌐 Go | 📅 2026-08-21 - MetaFlow is an automated observability platform for cloud-native developers.
* [vizceral](https://github.com/Netflix/vizceral) ⭐ 4,093 | 🐛 54 | 🌐 JavaScript | 📅 2023-11-28 - WebGL visualization for displaying animated traffic graphs.
* [kiali](https://github.com/kiali/kiali) ⭐ 3,631 | 🐛 83 | 🌐 Go | 📅 2026-08-23 - Kiali project to help istio service mesh observability.
* [open-falcon](https://github.com/XiaoMi/open-falcon) ⭐ 3,020 | 🐛 32 | 📅 2018-07-05 - Enterprise Internet monitoring system from Xiaomi.
* [inspektor-gadget](https://github.com/inspektor-gadget/inspektor-gadget) ⭐ 2,913 | 🐛 430 | 🌐 C | 📅 2026-08-21 - The eBPF tool and systems inspection framework for Kubernetes, containers and Linux hosts.
* [goldpinger](https://github.com/bloomberg/goldpinger) ⭐ 2,733 | 🐛 36 | 🌐 JavaScript | 📅 2026-04-23 - Debugging tool for Kubernetes which tests and displays connectivity between nodes in the cluster.
* [ebpftop](https://github.com/Netflix/bpftop) ⭐ 2,702 | 🐛 5 | 🌐 C | 📅 2026-08-01 - bpftop provides a dynamic real-time view of running eBPF programs. It displays the average runtime, events per second, and estimated total CPU % for each program.
* [perses](https://github.com/perses/perses) ⭐ 2,374 | 🐛 263 | 🌐 Go | 📅 2026-08-21 - The CNCF candidate for observability visualisation.
* [naftis](https://github.com/XiaoMi/naftis) ⭐ 1,884 | 🐛 30 | 🌐 Go | 📅 2023-08-19 - An excellent dashboard for Istio built with love.
* [kube-ops-view](https://github.com/hjacobs/kube-ops-view) ⚠️ Archived - Kubernetes Operational View - read-only system dashboard for multiple K8s clusters.
* [sloop](https://github.com/salesforce/sloop) ⭐ 1,581 | 🐛 61 | 🌐 Go | 📅 2026-02-17 - Kubernetes History Visualization.
* [kepler](https://github.com/sustainable-computing-io/kepler) ⭐ 1,559 | 🐛 49 | 🌐 Go | 📅 2026-08-21 - Kepler (Kubernetes-based Efficient Power Level Exporter) uses eBPF to probe performance counters and other system stats, use ML models to estimate workload energy consumption based on these stats, and exports them as Prometheus metrics.
* [kindling](https://github.com/Kindling-project/kindling) ⭐ 1,062 | 🐛 27 | 🌐 Go | 📅 2026-07-21 - eBPF-based CloudNative Monitor tool.
* [owl](https://github.com/TalkingData/owl) ⭐ 840 | 🐛 6 | 🌐 Go | 📅 2026-04-16 - Distributed monitoring system from TalkingData.
* [tobs](https://github.com/timescale/tobs) ⚠️ Archived - tobs - The Observability Stack for Kubernetes. Easy install of a full observability stack into a k8s cluster with a CLI tool or Helm charts.
* [nexclipper](https://github.com/NexClipper/NexClipper) ⭐ 562 | 🐛 8 | 🌐 Go | 📅 2023-05-05 - An open source software for monitoring Kubernetes and containers.
* [kubenurse](https://github.com/postfinance/kubenurse) ⭐ 494 | 🐛 12 | 🌐 Go | 📅 2026-08-17 - Kubernetes network monitoring.
* [sofa-lookout](https://github.com/sofastack/sofa-lookout) ⭐ 373 | 🐛 37 | 🌐 Java | 📅 2023-12-01 - Lookout can help you to measure and monitor the status of the target system with its multi-dimensional metrics.
* [vistio](https://github.com/nmnellis/vistio) ⭐ 371 | 🐛 5 | 🌐 JavaScript | 📅 2018-10-20 - Visualize your Istio mesh using Netflix's Vizceral.
* [monosi](https://github.com/monosidev/monosi) ⭐ 327 | 🐛 31 | 🌐 Python | 📅 2022-09-25 - Open source data observability platform.
* [kelemetry](https://github.com/kubewharf/kelemetry) ⭐ 279 | 🐛 19 | 🌐 Go | 📅 2025-11-20 - Global control plane tracing for Kubernetes.
* [kubernetes-zabbix](https://github.com/monitoringartist/kubernetes-zabbix) ⭐ 269 | 🐛 0 | 📅 2018-12-14 - Kubernetes Zabbix/Grafana cluster (bare metal, Google Computer Engine - GCE, Google Container Engine - GKE).
* [hawkular-metrics](https://github.com/hawkular/hawkular-metrics) ⚠️ Archived - Time Series Metrics Engine based on Cassandra.
* [starship](https://github.com/tricorder-observability/Starship) ⭐ 161 | 🐛 90 | 🌐 Go | 📅 2023-04-06 - Next-generation Observability platform built with eBPF+WASM.
* [lake](https://github.com/merico-dev/lake) ⭐ 135 | 🐛 0 | 🌐 Go | 📅 2025-07-17 - Data lake for dev.
* [middleware](https://github.com/middleware-labs/mw-agent) ⭐ 79 | 🐛 5 | 🌐 Go | 📅 2026-08-18 - Full-stack observability platform with SRE agent.
* [istio-ui](https://github.com/jukylin/istio-ui) ⭐ 52 | 🐛 1 | 🌐 JavaScript | 📅 2018-10-24 - Istio config management backend.
* [searchlight](https://github.com/searchlight/searchlight) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2024-05-02 - Alerts for Kubernetes.
* [ingero](https://github.com/ingero-io/ingero) - eBPF-based GPU causal observability agent. Traces CUDA APIs and host kernel events to explain GPU latency in cloud-native environments. Helm chart and DaemonSet included.
* [konstellate](https://github.com/containership/konstellate) - Free and Open Source GUI to Visualize Kubernetes Applications.

## Logging

* [elasticsearch](https://github.com/elastic/elasticsearch) ⭐ 77,852 | 🐛 5,905 | 🌐 Java | 📅 2026-08-23 - Open Source, Distributed, RESTful Search Engine.
* [loki](https://github.com/grafana/loki) ⭐ 28,774 | 🐛 1,723 | 🌐 Go | 📅 2026-08-23 - Like Prometheus, but for logs.
* [vector](https://github.com/vectordotdev/vector) ⭐ 22,437 | 🐛 2,525 | 🌐 Rust | 📅 2026-08-22 - High-performance observability data router for logs, metrics, and traces.
* [telegraf](https://github.com/influxdata/telegraf) ⭐ 17,763 | 🐛 395 | 🌐 Go | 📅 2026-08-21 - The plugin-driven server agent for collecting & reporting metrics.
* [fluentd](https://github.com/fluent/fluentd) ⭐ 13,579 | 🐛 140 | 🌐 Ruby | 📅 2026-08-23 - Fluentd: Unified Logging Layer (project under CNCF).
* [beats](https://github.com/elastic/beats) ⭐ 12,639 | 🐛 1,040 | 🌐 Go | 📅 2026-08-22 - Beats - Lightweight shippers for Elasticsearch & Logstash.
* [quickwit](https://github.com/quickwit-oss/quickwit) ⭐ 11,536 | 🐛 803 | 🌐 Rust | 📅 2026-08-21 - Open-source & cloud-native log management & analytics.
* [fluent-bit](https://github.com/fluent/fluent-bit) ⭐ 8,060 | 🐛 775 | 🌐 C | 📅 2026-08-21 - Fast and Lightweight Log/Data Forwarder for Linux, BSD and macOS.
* [heapster](https://github.com/kubernetes-retired/heapster) ⚠️ Archived - Compute Resource Usage Analysis and Monitoring of Container Clusters.
* [log-pilot](https://github.com/AliyunContainerService/log-pilot) ⚠️ Archived - Collect logs in docker containers.
* [loggie](https://github.com/loggie-io/loggie/) ⭐ 1,332 | 🐛 159 | 🌐 Go | 📅 2024-07-25 - A lightweight, cloud-native data transfer agent and aggregator.
* [dagger](https://github.com/CloudmindsRobot/dagger) ⭐ 255 | 🐛 4 | 🌐 Vue | 📅 2021-03-05 - Dagger 是一个基于 Loki 的日志查询和管理系统。
* [collectbeat](https://github.com/eBay/collectbeat) ⚠️ Archived - Beats with discovery capabilities for environments like Kubernetes.
* [egg](https://github.com/ducc/egg) ⭐ 14 | 🐛 1 | 🌐 Go | 📅 2021-02-25 - The simple error aggregator.
* [flume](http://flume.apache.org/) - Flume is a distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log data.

## Tracing & Profiling

* [sentry](https://github.com/getsentry/sentry) ⭐ 44,604 | 🐛 2,287 | 🌐 Python | 📅 2026-08-23 - Sentry is a cross-platform crash reporting and aggregation platform.
* [skywalking](https://github.com/apache/skywalking) ⭐ 24,927 | 🐛 23 | 🌐 Java | 📅 2026-08-20 - An APM system for tracing, monitoring, diagnosing distributed systems, especially based on microservices, cloud native and container.
* [jaeger](https://github.com/jaegertracing/jaeger) ⭐ 23,130 | 🐛 570 | 🌐 Go | 📅 2026-08-20 - Jaeger, a Distributed Tracing System.
* [zipkin](https://github.com/openzipkin/zipkin) ⭐ 17,453 | 🐛 175 | 🌐 Java | 📅 2026-08-06 - Zipkin is a distributed tracing system.
* [pinpoint](https://github.com/naver/pinpoint) ⭐ 13,861 | 🐛 532 | 🌐 Java | 📅 2026-08-21 - Pinpoint is an open source APM (Application Performance Management) tool for large-scale distributed systems written in Java.
* [opentelemetry](https://github.com/open-telemetry/opentelemetry-specification) ⭐ 4,320 | 🐛 519 | 🌐 Makefile | 📅 2026-08-19 - An observability framework for cloud-native software.
* [appdash](https://github.com/sourcegraph/appdash) ⚠️ Archived - Application tracing system for Go, based on Google's Dapper.
* [sofa-tracker](https://github.com/sofastack/sofa-tracer) ⭐ 1,127 | 🐛 51 | 🌐 Java | 📅 2026-06-07 - SOFATracer is a component for the distributed system call trace. And through a unified traceId logging the logs of various network calls in the invoking link . These logs can be used for quick discovery of faults, service governance, etc.
* [opencensus](https://github.com/census-instrumentation) - A single distribution of libraries that automatically collect traces and metrics from your app, display them locally, and send them to any backend.
* [opentracing](https://github.com/opentracing) - Consistent, expressive, vendor-neutral APIs for distributed tracing and context propagation.

## Security & Compliance

* [trivy](https://github.com/aquasecurity/trivy) ⭐ 37,569 | 🐛 252 | 🌐 Go | 📅 2026-08-21 - Scanner for vulnerabilities in container images, file systems, and Git repositories, as well as for configuration issues and hard-coded secrets.
* [keycloak](https://github.com/keycloak/keycloak) ⭐ 36,348 | 🐛 3,129 | 🌐 Java | 📅 2026-08-23 - Open Source Identity and Access Management For Modern Applications and Services.
* [vault](https://github.com/hashicorp/vault) ⭐ 36,154 | 🐛 1,429 | 🌐 Go | 📅 2026-08-21 - A tool for managing secrets.
* [teleport](https://github.com/gravitational/teleport) ⭐ 20,841 | 🐛 3,387 | 🌐 Go | 📅 2026-08-21 - Certificate authority and access plane for SSH, Kubernetes, web apps, databases and desktops.
* [supertokens-core](https://github.com/supertokens/supertokens-core) ⭐ 15,275 | 🐛 168 | 🌐 Java | 📅 2026-08-19 - Open source alternative to Auth0 / Firebase Auth / AWS Cognito.
* [cert-manager](https://github.com/jetstack/cert-manager) ⭐ 14,043 | 🐛 248 | 🌐 Go | 📅 2026-08-22 - Automatically provision and manage TLS certificates in Kubernetes.
* [kratos](https://github.com/ory/kratos) ⭐ 13,843 | 🐛 224 | 🌐 Go | 📅 2026-07-29 - Next-gen identity server (think Auth0, Okta, Firebase) with Ory-hardened authentication, MFA, FIDO2, profile management, identity schemas, social sign in, registration, account recovery, service-to-service and IoT auth. Can work as an OAuth2 / OpenID Connect Provider. Golang, headless, API-only - without templating or theming headaches.
* [grype](https://github.com/anchore/grype) ⭐ 12,773 | 🐛 411 | 🌐 Go | 📅 2026-08-21 - A vulnerability scanner for container images and filesystems.
* [opa](https://github.com/open-policy-agent/opa) ⭐ 12,136 | 🐛 341 | 🌐 Go | 📅 2026-08-21 - An open source project to policy-enable your service.
* [kubescape](https://github.com/armosec/kubescape) ⭐ 11,681 | 🐛 77 | 🌐 Go | 📅 2026-08-22 - Kubescape is the first tool for testing if Kubernetes is deployed securely as defined in Kubernetes Hardening Guidance by to NSA and CISA.
* [dex](https://github.com/dexidp/dex) ⭐ 11,054 | 🐛 525 | 🌐 Go | 📅 2026-08-20 - OpenID Connect Identity (OIDC) and OAuth 2.0 Provider with Pluggable Connectors.
* [clair](https://github.com/quay/clair) ⭐ 11,051 | 🐛 60 | 🌐 Go | 📅 2026-08-11 - Vulnerability Static Analysis for Containers.
* [docker-bench-security](https://github.com/docker/docker-bench-security) ⭐ 9,695 | 🐛 29 | 🌐 Shell | 📅 2026-06-04 - The Docker Bench for Security is a script that checks for dozens of common best-practices around deploying Docker containers in production.
* [syft](https://github.com/anchore/syft) ⭐ 9,448 | 🐛 628 | 🌐 Go | 📅 2026-08-21 - CLI tool and library for generating a Software Bill of Materials from container images and filesystems.
* [falco](https://github.com/falcosecurity/falco) ⭐ 9,291 | 🐛 64 | 🌐 C++ | 📅 2026-08-03 - Behavioral Activity Monitoring With Container Support.
* [firezone](https://github.com/firezone/firezone) ⭐ 9,039 | 🐛 420 | 🌐 Elixir | 📅 2026-08-23 - VPN server and Linux firewall built on WireGuard®. Supports SSO, MFA, and user-scoped access rules.
* [checkov](https://github.com/bridgecrewio/checkov/) ⭐ 8,969 | 🐛 164 | 🌐 Python | 📅 2026-08-23 - A static analysis tool for infrastructure as code - to prevent misconfigs at build time.
* [kube-bench](https://github.com/aquasecurity/kube-bench) ⭐ 8,148 | 🐛 95 | 🌐 Go | 📅 2026-08-18 - The Kubernetes Bench for Security is a Go application that checks whether Kubernetes is deployed according to security best practices.
* [kyverno](https://github.com/kyverno/kyverno/) ⭐ 8,059 | 🐛 621 | 🌐 Go | 📅 2026-08-21 - Kubernetes Native Policy Management.
* [external-secrets](https://github.com/external-secrets/external-secrets) ⭐ 6,805 | 🐛 267 | 🌐 Go | 📅 2026-08-19 - Sync secrets from external stores like AWS Secrets Manager or Vault into Kubernetes.
* [cosign](https://github.com/sigstore/cosign) ⭐ 6,227 | 🐛 162 | 🌐 Go | 📅 2026-08-19 - Container signing, verification, and provenance powered by Sigstore.
* [opal](https://github.com/permitio/opal) ⭐ 5,502 | 🐛 64 | 🌐 Python | 📅 2026-08-23 - An administration layer for Policy Engines, detecting changes to both policy and policy data in real time and pushing live updates to your agents.
* [pomerium](https://github.com/pomerium/pomerium/) ⭐ 4,970 | 🐛 149 | 🌐 Go | 📅 2026-08-21 - Pomerium is a zero-trust context and identity aware access gateway inspired by BeyondCorp.
* [coraza](https://github.com/corazawaf/coraza) ⭐ 3,750 | 🐛 119 | 🌐 Go | 📅 2026-08-22 - OWASP Coraza WAF is a golang modsecurity compatible web application firewall library.
* [notary](https://github.com/theupdateframework/notary) ⚠️ Archived - Notary is a Docker project that allows anyone to have trust over arbitrary collections of data.
* [authenticator](https://github.com/kubernetes-sigs/aws-iam-authenticator) ⭐ 2,332 | 🐛 19 | 🌐 Go | 📅 2026-08-21 - A tool for using AWS IAM credentials to authenticate to a Kubernetes cluster.
* [kube-lego](https://github.com/jetstack/kube-lego) ⚠️ Archived - Automatically request certificates for Kubernetes Ingress resources from Let's Encrypt.
* [goldfish](https://github.com/Caiyeon/goldfish) ⚠️ Archived - A HashiCorp Vault UI panel written with VueJS and Vault native Go API.
* [kube2iam](https://github.com/jtblin/kube2iam) ⭐ 2,042 | 🐛 14 | 🌐 HTML | 📅 2026-05-08 - kube2iam provides different AWS IAM roles for pods running on Kubernetes.
* [spiffe](https://github.com/spiffe/spiffe) ⭐ 1,829 | 🐛 50 | 🌐 Shell | 📅 2026-08-03 - The SPIFFE Project.
* [cedar](https://github.com/cedar-policy/cedar) ⭐ 1,681 | 🐛 175 | 🌐 Rust | 📅 2026-08-21 - Core implementation of the Cedar language.
* [grafeas](https://github.com/Grafeas/Grafeas) ⭐ 1,571 | 🐛 62 | 🌐 Go | 📅 2026-07-25 - Cloud artifact metadata CRUD API and resource specifications.
* [kubesec](https://github.com/controlplaneio/kubesec) ⭐ 1,476 | 🐛 28 | 🌐 Go | 📅 2026-07-10 - Security risk analysis for Kubernetes resources.
* [infra](https://github.com/infrahq/infra) ⭐ 1,466 | 🐛 33 | 🌐 Go | 📅 2026-08-10 - Infra provides authentication and access management to servers and Kubernetes clusters.
* [KubiScan](https://github.com/cyberark/KubiScan) ⭐ 1,429 | 🐛 6 | 🌐 Python | 📅 2025-05-25 - A tool to scan Kubernetes cluster for risky permissions.
* [trivy-action](https://github.com/aquasecurity/trivy-action) ⭐ 1,403 | 🐛 178 | 🌐 Shell | 📅 2026-08-19 - Runs Trivy as GitHub action to scan your Docker container image for vulnerabilities.
* [topaz](https://github.com/aserto-dev/topaz) ⭐ 1,359 | 🐛 10 | 🌐 Go | 📅 2026-08-20 - Cloud-native authorization for modern applications and APIs.
* [neuvector](https://github.com/neuvector/neuvector) ⭐ 1,330 | 🐛 304 | 🌐 Go | 📅 2026-08-22 - Kubernetes-native container security platform.
* [in-toto](https://github.com/in-toto/in-toto) ⭐ 1,029 | 🐛 60 | 🌐 Python | 📅 2026-08-05 - in-toto is a framework to protect supply chain integrity.
* [kubed](https://github.com/appscode/kubed) ⭐ 1,017 | 🐛 58 | 🌐 Go | 📅 2026-07-09 - A Kubernetes Cluster Operator Daemon.
* [trousseau](https://github.com/oleiade/trousseau) ⭐ 956 | 🐛 20 | 🌐 Go | 📅 2026-02-08 - File based encrypted key-value store.
* [kamus](https://github.com/Soluto/kamus) ⚠️ Archived - An open source, git-ops, zero-trust secret encryption and decryption solution for Kubernetes applications.
* [darkmoon](https://github.com/ASCIT31/Dark-Moon) ⭐ 861 | 🐛 1 | 🌐 Python | 📅 2026-08-21 - Open source autonomous AI penetration testing platform that orchestrates 80+ offensive tools via Markdown playbooks, with a proof trail per finding.
* [kritis](https://github.com/grafeas/kritis) ⭐ 710 | 🐛 86 | 🌐 Go | 📅 2026-07-24 - Deploy-time Policy Enforcer for Kubernetes applications.
* [guard](https://github.com/appscode/guard) ⭐ 620 | 🐛 55 | 🌐 Go | 📅 2026-08-19 - Kubernetes Authentication WebHook Server.
* [rback](https://github.com/team-soteria/rback) ⭐ 400 | 🐛 8 | 🌐 Go | 📅 2021-01-04 - RBAC in Kubernetes visualizer.
* [trust-manager](https://github.com/cert-manager/trust-manager) ⭐ 394 | 🐛 44 | 🌐 Go | 📅 2026-08-23 - trust-manager is an operator for distributing trust bundles across a Kubernetes cluster.
* [dockscan](https://github.com/kost/dockscan) ⭐ 219 | 🐛 1 | 🌐 Ruby | 📅 2016-08-27 - Dockscan is security vulnerability and audit scanner for Docker installations.
* [rond](https://github.com/rond-authz/rond) ⭐ 161 | 🐛 35 | 🌐 Go | 📅 2026-02-11 - A lightweight container for distributed security policy evaluation.
* [vilicus](https://github.com/edersonbrilhante/vilicus) ⭐ 86 | 🐛 16 | 🌐 SCSS | 📅 2023-01-07 - Vilicus is an open source tool that orchestrates security scans of container images(docker/oci) and centralizes all results into a database for further analysis and metrics.
* [cloud-audit](https://github.com/gebalamariusz/cloud-audit) ⭐ 69 | 🐛 10 | 🌐 Python | 📅 2026-07-21 - Fast, opinionated AWS security scanner with 47 curated checks. Each finding includes copy-paste remediation in AWS CLI and Terraform. Features attack chain detection and a diff command for CI/CD pipeline gating.
* [drydock](https://github.com/zuBux/drydock) ⭐ 66 | 🐛 2 | 🌐 Python | 📅 2016-05-13 - Drydock provides a flexible way of assessing the security of your Docker daemon configuration and containers using editable audit templates.
* [brood-box](https://github.com/stacklok/brood-box) ⭐ 60 | 🐛 13 | 🌐 Go | 📅 2026-08-21 - CLI tool for running coding agents inside hardware-isolated microVMs with workspace snapshot isolation and egress control.
* [awacs](https://github.com/socketkit/awacs) ⭐ 51 | 🐛 8 | 🌐 JavaScript | 📅 2023-08-15 - Next-gen behavior analysis server (think Mixpanel, Google Analytics) with built-in encryption.
* [galadriel](https://github.com/HewlettPackard/galadriel) ⚠️ Archived - SPIFFE Federation the easy way.
* [go-microvm](https://github.com/stacklok/go-microvm) ⭐ 21 | 🐛 9 | 🌐 Go | 📅 2026-08-23 - Go framework for running OCI images as microVMs via libkrun with embedded runtime, rootfs management, and guest networking.
* [segspec](https://github.com/dormstern/segspec) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2026-05-06 - Extracts network dependencies from application config files and generates Kubernetes NetworkPolicies with evidence tracing.
* [apparmor](https://gitlab.com/apparmor/apparmor/-/wikis/home) - AppArmor is an effective and easy-to-use Linux application security system.
* [curiefense](https://github.com/curiefense/curiefense) - Adds a broad set of automated web security tools to Envoy.
* [k8guard](https://github.com/k8guard) - An auditing system for Kubernetes.

## Reliability & Chaos Engineering

* [hystrix](https://github.com/Netflix/Hystrix) ⭐ 24,472 | 🐛 58 | 🌐 Java | 📅 2025-12-17 - Hystrix is a latency and fault tolerance library designed to isolate points of access to remote systems, services and 3rd party libraries, stop cascading failure and enable resilience in complex distributed systems where failure is inevitable.
* [sentinel](https://github.com/alibaba/sentinel) ⭐ 23,142 | 🐛 862 | 🌐 Java | 📅 2026-05-27 - A powerful flow control component enabling reliability, resilience and monitoring for microservices. (面向云原生微服务的高可用流控防护组件)
* [chaosmonkey](https://github.com/Netflix/chaosmonkey) ⭐ 17,086 | 🐛 34 | 🌐 Go | 📅 2025-01-06 - Chaos Monkey is a resiliency tool that helps applications tolerate random instance failures.
* [metersphere](https://github.com/metersphere/metersphere) ⭐ 13,463 | 🐛 1 | 🌐 Java | 📅 2026-08-10 - MeterSphere is an End-to-End open source continuous testing platform. MeterSphere 是一站式开源持续测试平台，涵盖测试跟踪、接口测试、性能测试、团队协作等功能，全面兼容 JMeter、Postman、Swagger 等开源、主流标准。
* [toxiproxy](https://github.com/shopify/toxiproxy) ⭐ 12,277 | 🐛 105 | 🌐 Go | 📅 2026-08-04 - A TCP proxy to simulate network and system conditions for chaos and resiliency testing.
* [chaos-mesh](https://github.com/chaos-mesh/chaos-mesh) ⭐ 7,852 | 🐛 551 | 🌐 Go | 📅 2026-08-18 - A Chaos Engineering Platform for Kubernetes.
* [chaosblade](https://github.com/chaosblade-io/chaosblade) ⭐ 6,497 | 🐛 365 | 🌐 Python | 📅 2026-08-17 - An easy to use and powerful chaos engineering experiment toolkit（阿里巴巴开源的一款简单易用、功能强大的混沌实验注入工具）.
* [litmus](https://github.com/litmuschaos/litmus) ⭐ 5,600 | 🐛 416 | 🌐 Go | 📅 2026-07-31 - Litmus helps SREs and developers practice chaos engineering in a Cloud-native way.
* [concurrency-limits](https://github.com/Netflix/concurrency-limits) ⭐ 3,596 | 🐛 52 | 🌐 Java | 📅 2026-01-16 - Java Library that implements and integrates concepts from TCP congestion control to auto-detect concurrency limits to achieve optimal throughput with optimal latency.
* [ratelimit](https://github.com/envoyproxy/ratelimit) ⭐ 2,684 | 🐛 33 | 🌐 Go | 📅 2026-08-21 - Go/gRPC service designed to enable generic rate limit scenarios from different types of applications.
* [kubedoom](https://github.com/storax/kubedoom) ⭐ 2,166 | 🐛 4 | 🌐 C++ | 📅 2024-08-20 - Kill Kubernetes pods by playing Id's DOOM!
* [chaostoolkit](https://github.com/chaostoolkit/chaostoolkit/) ⭐ 2,018 | 🐛 3 | 🌐 Python | 📅 2026-08-09 - An Open API to Chaos Engineering.
* [powerfulseal](https://github.com/powerfulseal/powerfulseal) ⭐ 1,977 | 🐛 55 | 🌐 Python | 📅 2023-11-10- A powerful testing tool for Kubernetes clusters.
* [testkube](https://github.com/kubeshop/testkube) ⭐ 1,646 | 🐛 51 | 🌐 Go | 📅 2026-08-21 - Kubernetes-native framework for test definition and execution.
* [krkn](https://github.com/krkn-chaos/krkn) ⭐ 489 | 🐛 139 | 🌐 Python | 📅 2026-08-20 - Chaos and resiliency testing tool for Kubernetes with a focus on improving performance under failure conditions. A CNCF sandbox project.
* [kubediag](https://github.com/kubediag/kubediag) ⚠️ Archived - Problem diagnosis and operation orchestration for Kubernetes.
* [rider](https://github.com/hango-io/rider) ⭐ 46 | 🐛 5 | 🌐 Lua | 📅 2026-01-04 - SDK for Envoy Lua extensions.

## Dashboards & Portals

* [portainer](https://github.com/portainer/portainer) ⭐ 38,313 | 🐛 746 | 🌐 TypeScript | 📅 2026-08-21 - Simple management UI for Docker.
* [backstage](https://github.com/backstage/backstage) ⭐ 34,217 | 🐛 402 | 🌐 TypeScript | 📅 2026-08-22 - Backstage is an open platform for building developer portals.
* [rancher](https://github.com/rancher/rancher) ⭐ 25,867 | 🐛 3,347 | 🌐 Go | 📅 2026-08-22 - Complete container management platform.
* [kubesphere](https://github.com/kubesphere/kubesphere) ⭐ 17,028 | 🐛 353 | 🌐 Go | 📅 2026-07-15 - Enterprise Container Managent Platform.
* [dashboard](https://github.com/kubernetes/dashboard) ⚠️ Archived - General-purpose web UI for Kubernetes clusters.
* [openshift](https://github.com/openshift/origin) ⭐ 8,680 | 🐛 299 | 🌐 Go | 📅 2026-08-22 - Enterprise Kubernetes for Developers.
* [rainbond](https://github.com/goodrain/rainbond) ⭐ 6,254 | 🐛 56 | 🌐 Go | 📅 2026-08-21 - Serverless PaaS , A new generation of easy-to-use cloud management platforms based on kubernetes.
* [wayne](https://github.com/Qihoo360/wayne) ⭐ 3,700 | 🐛 61 | 🌐 TypeScript | 📅 2022-05-31 - Web UI for Kubernetes multi-clusters.
* [radar](https://github.com/skyhook-io/radar) ⭐ 3,048 | 🐛 57 | 🌐 Go | 📅 2026-08-23 - Modern Kubernetes visibility tool with multi-cluster topology, image filesystem viewer, Helm and GitOps management, and built-in MCP server.
* [kubediagrams](https://github.com/philippemerle/KubeDiagrams) ⭐ 2,678 | 🐛 11 | 🌐 JavaScript | 📅 2026-08-19 - A CLI tool to generate Kubernetes architecture diagrams automatically from Kubernetes manifest files, kustomization files, Helm charts, helmfile descriptors, and actual cluster state.
* [kdash](https://github.com/kdash-rs/kdash) ⭐ 2,524 | 🐛 2 | 🌐 Rust | 📅 2026-08-19 - A simple and fast dashboard for Kubernetes.
* [choerodon](https://github.com/choerodon/choerodon) ⭐ 2,393 | 🐛 6 | 📅 2024-01-13 - The open source PaaS for Kubernetes.
* [karpor](https://github.com/KusionStack/karpor) ⭐ 1,732 | 🐛 90 | 🌐 Go | 📅 2026-07-12 - Intelligence for Kubernetes. World's most promising Kubernetes Visualization Tool for Developer and Platform Engineering teams.
* [kubevious](https://github.com/kubevious/kubevious) ⭐ 1,706 | 🐛 17 | 📅 2026-06-13 - Kubevious - application centric Kubernetes UI and continuous assurance provider.
* [kubermatic](https://github.com/kubermatic/kubermatic) ⭐ 1,297 | 🐛 457 | 🌐 Go | 📅 2026-08-21 - The Central Kubernetes Management Platform For Any Infrastructure.
* [breeze](https://github.com/wise2c-devops/breeze) ⭐ 1,010 | 🐛 2 | 🌐 Jinja | 📅 2025-12-07 - Wise2C ansible playbook for Kubernetes cluster installation.
* [oneinfra](https://github.com/oneinfra/oneinfra) ⭐ 876 | 🐛 18 | 🌐 Go | 📅 2024-12-01 - Kubernetes as a Service.
* [kubernator](https://github.com/smpio/kubernator) ⚠️ Archived - Alternative Kubernetes UI.
* [conjure-up](https://github.com/conjure-up/conjure-up) ⚠️ Archived - Deploying complex solutions, magically.
* [opendcp](https://github.com/weibocom/opendcp) ⭐ 409 | 🐛 3 | 🌐 Go | 📅 2026-08-07 - Docker platform developed by weibo.
* [statusbay](https://github.com/similarweb/statusbay) ⭐ 387 | 🐛 34 | 🌐 Go | 📅 2024-07-02 - Kubernetes deployment visibility like a pro.
* [kqeen](https://github.com/Mirantis/kqueen) ⭐ 138 | 🐛 16 | 🌐 Python | 📅 2022-12-08 - Kubernetes queen - cluster manager.
* [kubestellar](https://github.com/kubestellar/console) ⭐ 127 | 🐛 33 | 🌐 TypeScript | 📅 2026-08-23 - KubeStellar Console is an AI-powered multi-cluster Kubernetes dashboard with natural language operations, MCP support, and GitOps deployment management.
* [kuui](https://github.com/viveksinghggits/kuui) ⭐ 18 | 🐛 4 | 🌐 JavaScript | 📅 2023-02-06 - UI that can be used to edit configmaps/secrets of your kubernetes cluster.
* [k100s](https://github.com/AndrewVos/k100s) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-18 - Free, open-source desktop Kubernetes app for browsing pods, streaming logs, and opening pod shells.
* [cloudfoundry](https://github.com/cloudfoundry) - Cloud Foundry is an open source, multi cloud application platform as a service (PaaS) governed by the Cloud Foundry Foundation.

## Tutorials & Learning

* [developer-roadmap](https://github.com/kamranahmedse/developer-roadmap) ⭐ 365,214 | 🐛 12 | 🌐 TypeScript | 📅 2026-08-21 - Interactive roadmaps, guides and other educational content to help developers grow in their careers.
* [kubernetes-the-hard-way](https://github.com/kelseyhightower/kubernetes-the-hard-way) ⭐ 49,536 | 🐛 51 | 📅 2025-04-10 - Bootstrap Kubernetes the hard way on Google Cloud Platform. No scripts.
* [kubernetes-handbook](https://github.com/rootsongjc/kubernetes-handbook) ⭐ 11,610 | 🐛 1 | 🌐 Mermaid | 📅 2025-12-26 - Kubernetes 中文指南/云原生应用架构实践手册。
* [kubernetes-security-best-practice](https://github.com/freach/kubernetes-security-best-practice) ⭐ 2,706 | 🐛 12 | 📅 2019-09-11 - Kubernetes Security - Best Practice Guide.
* [aws-workshop-for-kubernetes](https://github.com/aws-samples/aws-workshop-for-kubernetes) ⚠️ Archived - AWS Workshop for Kubernetes.
* [kube-ladder](https://github.com/caicloud/kube-ladder) ⭐ 2,596 | 🐛 6 | 📅 2022-11-28 - Learning Kubernetes, The Chinese Taoist Way.
* [aws-eks-best-practices](https://github.com/aws/aws-eks-best-practices/) ⭐ 2,157 | 🐛 91 | 🌐 Python | 📅 2026-08-21 - A best practices guide for day 2 operations, including operational excellence, security, reliability, performance efficiency, and cost optimization.
* [istio-tutorial](https://github.com/redhat-developer-demos/istio-tutorial) ⭐ 1,205 | 🐛 11 | 🌐 Java | 📅 2024-10-17 - Istio Tutorial for Java Microservices.
* [kubeadm-workshop](https://github.com/luxas/kubeadm-workshop) ⭐ 679 | 🐛 29 | 🌐 Makefile | 📅 2020-05-22 - Showcasing a bare-metal multi-platform kubeadm setup with persistent storage and monitoring.
* [kubernetes-on-aws](https://github.com/zalando-incubator/kubernetes-on-aws) ⭐ 635 | 🐛 30 | 🌐 Go | 📅 2026-08-21 - Deploying Kubernetes on AWS with CloudFormation and Ubuntu.
* [istio-ingress-tutorial](https://github.com/kelseyhightower/istio-ingress-tutorial) ⭐ 321 | 🐛 4 | 🌐 Shell | 📅 2018-07-26 - How to run the Istio Ingress Controller on Kubernetes.
* [kubernetes-java-simple](https://github.com/arun-gupta/kubernetes-java-sample) ⭐ 279 | 🐛 9 | 🌐 Java | 📅 2025-10-16 - Kubernetes Hands-on Workshop for Java Developers.
* [istio-service-mesh-workshop](https://github.com/layer5io/istio-service-mesh-workshop) ⭐ 274 | 🐛 1 | 📅 2026-02-07 - Using Istio Workshop.
* [ks](https://github.com/red-gate/ks) ⚠️ Archived - A series of Kubernetes walk-throughs.
* [istio101](https://github.com/IBM/istio101) ⚠️ Archived - Istio 101 workshop from IBM.
* [envoy-steps](https://github.com/datawire/envoy-steps) ⭐ 74 | 🐛 6 | 🌐 Python | 📅 2020-11-14 - Envoy Step by Step.
* [falco-analyze-audit-log-from-k3s-cluster](https://github.com/developer-guy/falco-analyze-audit-log-from-k3s-cluster) ⭐ 63 | 🐛 1 | 📅 2021-06-02 - Detect intrusions that happened in your Kubernetes cluster through audit logs using Falco.
* [mosn-tutorial](https://github.com/mosn/mosn-tutorial) ⭐ 20 | 🐛 3 | 🌐 Shell | 📅 2022-07-23 - Tutorial for MOSN and Istio Service Mesh.
* [istio-index-conf2018](https://github.com/todkap/istio-index-conf2018) ⭐ 19 | 🐛 1 | 🌐 Shell | 📅 2018-08-01 - Istio is not just for Microservices: Secure your Kubernetes services using Istio Service Mesh.
* [envoy-tutorial](https://github.com/rootsongjc/envoy-tutorial) - Envoy mesh in kubernetes tutorial.
* [kubicorn](https://github.com/kris-nova/kubicorn-fork) - Create, manage, snapshot, and scale Kubernetes infrastructure in the public cloud.

## Contribute

This website is hosted on GitHub Pages within [rootsongjc/awesome-cloud-native](https://github.com/rootsongjc/awesome-cloud-native) ⭐ 2,434 | 🐛 6 | 🌐 HTML | 📅 2026-08-17 repository.

Please take a quick gander at the **[contribution guidelines](https://github.com/rootsongjc/awesome-cloud-native/blob/main/CONTRIBUTING.md) ⭐ 2,434 | 🐛 6 | 🌐 HTML | 📅 2026-08-17** first. Thanks to all **[contributors](https://github.com/rootsongjc/awesome-cloud-native/graphs/contributors) ⭐ 2,434 | 🐛 6 | 🌐 HTML | 📅 2026-08-17**, you rock 🤟!

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-23._

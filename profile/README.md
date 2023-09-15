## kubernetes-learning-playground
### kubernetes 学习广场

- 成立目的：主要专注在基于k8s相关的扩展，以**自身学习**为主的项目组织
- 项目都是简易版或是属于半成品，属于自学使用，**不适合**用于生产环境

### 项目方向：
主要围绕k8s展开


#### 多集群工具

- a. [**multi-cluster-informer**](https://github.com/Kubernetes-Learning-Playground/multi-cluster-informer) :兼容原生client-go, 实现对多集群的informer功能的SDK
- b. [**multi-cluster-clientgo**](https://github.com/Kubernetes-Learning-Playground/multi-cluster-clientgo) :兼容原生client-go, 实现多集群的client-go功能的SDK

#### 集群内扩展实践

- a. [**work-flow-by-cue**](https://github.com/Kubernetes-Learning-Playground/work-flow-by-cue) :基于cue-lang实现简易版顺序部署工作负载顺序的工作流
- b. [**kube-event-collector**](https://github.com/Kubernetes-Learning-Playground/kube-event-collector) :基于k8s中集群的event事件通知器，对接结构化日志、prometheus metrics、邮件发送等功能
- c. [**k8s-webhook-develop**](https://github.com/Kubernetes-Learning-Playground/k8s-webhook-develop): 基于k8s-apiserver的webhook扩展，实现简易镜像白名单、黑名单或支持pod sider功能
- d. [**k8s-aggregator-apiserver**](https://github.com/Kubernetes-Learning-Playground/k8s-aggregator-apiserver-demo) : 基于k8s提供的aggregator-apiserver进行控制器扩展demo
- f. [**my-sample-kubelet**](https://github.com/Kubernetes-Learning-Playground/my-sample-kubelet) : 基于k8s的简易轻量级kubelet工作节点
- g. [**k8s-leader-election**](https://github.com/Kubernetes-Learning-Playground/k8s-leader-election-demo) :基于k8s提供的分布式锁，实现集群内pod的选主机制

#### 自定义调度器实践

- a. [**k8s-schedule-plugins**](https://github.com/Kubernetes-Learning-Playground/k8s-schedule-plugins-demo) :基于k8s-scheduler的自定义调度插件-demo练习

#### CRI方面实践

- a. [**virtual-kubelet-practice**](https://github.com/Kubernetes-Learning-Playground/virtual-kubelet-practice-demo) :基于virtual-kubelet模拟创建边缘节点demo，其中调用containerd CRI接口实现容器生命周期管理

#### CNI方面实践

- a. [**cni-interface-study**](https://github.com/Kubernetes-Learning-Playground/cni-interface-study) :基于k8s扩展的CNI接口练习，实现简易容器互通(创建出容器的网络资源)

#### CSI方面实践

- a. [**csi-interface-study**](https://github.com/Kubernetes-Learning-Playground/csi-interface-study) :基于k8s扩展的CSI接口练习，实现简易版nfs服务器挂载

#### OpenTelemetry可观测相关

- a. [**opentelemetry-trace-practice**](https://github.com/Kubernetes-Learning-Playground/opentelemetry-trace-practice) :基于opentelemetry概念实现简易链路追踪demo，1. http 2. informer

#### 其他：

- a. [**k8s-informer-practice**](https://github.com/Kubernetes-Learning-Playground/k8s-informer-practice) :基于golang对k8s-client-go中的informer机制的学习
- b. [**imitate-k8s-kubectl-clientgo-apiserver**](https://github.com/Kubernetes-Learning-Playground/imitate-k8s-kubectl-clientgo-apiserver) :模拟k8s中的kubectl与clientgo与apiserver的练习

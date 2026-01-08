# fcg-yaml-deploy

Bem-vindo ao repositório `fcg-yaml-deploy`! 🎉 Este projeto contém uma coleção de arquivos YAML para o deploy de diversas partes de uma aplicação baseada em microsserviços em um ambiente Kubernetes.

Aqui está uma visão geral do que você encontrará:

---

### 🎮 **Game**
Contém os manifests Kubernetes para o serviço `Game`.
- `configmap-game.yaml`: Configurações de ambiente para o serviço Game.
- `deployment-game.yaml`: Define o deployment do microsserviço Game.
- `hpa-game.yml`: Configuração de Horizontal Pod Autoscaler para o Game.
- `secret-game.yaml`: Segredos (credenciais, chaves) para o serviço Game.
- `service-game.yaml`: Define o serviço Kubernetes para o Game.

### 📊 **NewRelic**
Contém configurações e integração com o New Relic para monitoramento.
- `newrelic.yaml`: Configurações do agente New Relic ou integrações relacionadas.

### 💳 **Payment**
Contém os manifests Kubernetes para o serviço `Payment`.
- `deployment-payment.yaml`: Define o deployment do microsserviço Payment.
- `hpa-payment.yml`: Configuração de Horizontal Pod Autoscaler para o Payment.
- `secret-payment.yaml`: Segredos para o serviço Payment.
- `service-payment-balancer.yaml`: Define o serviço Kubernetes para o Payment, possivelmente com um load balancer.

### 🌐 **Svc_Getway**
Contém os manifests Kubernetes para o serviço `Gateway`.
- `configmap-svc.yaml`: Configurações de ambiente para o Gateway.
- `deployment-svc.yaml`: Define o deployment do microsserviço Gateway.
- `secret-svc.yaml`: Segredos para o serviço Gateway.

### 👤 **User**
Contém os manifests Kubernetes para o serviço `User`.
- `deployment-user.yaml`: Define o deployment do microsserviço User.
- `hpa-user.yml`: Configuração de Horizontal Pod Autoscaler para o User.
- `secret-user.yaml`: Segredos para o serviço User.
- `service-users.yaml`: Define o serviço Kubernetes para o User.

---

Este repositório visa facilitar a orquestração e o gerenciamento desses serviços no Kubernetes. 🚀

## 👥 Idealizadores do Projeto (Discord)
- 👨‍💻 Clovis Alceu Cassaro (`cloves_93258`)
- 👨‍💻 Gabriel Santos Ramos (`_gsramos`)
- 👨‍💻 Júlio César de Carvalho (`cesarsoft`)
- 👨‍💻 Marco Antonio Araujo (`_marcoaz`)
- 👩‍💻 Yasmim Muniz Da Silva Caraça (`yasmimcaraca`)

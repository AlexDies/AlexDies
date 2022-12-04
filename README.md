
### Привет!

Меня зовут **Алексей Гуреев**, я начинающий DevOps-инженер. Ниже моё портфолио с некоторой частью моих проектов и домашних работ.

---
##### Дипломный проект:

- Инфраструктура: [Основная часть](https://github.com/AlexDies/DipIomInfrastructure) 
- Приложение и CI/CD: [Приложение](https://gitlab.com/alex1094/superapp/-/tree/main/helmDeploy/superapp)

В дипломном проекте использовались следующий инструменты: Terraform, Ansible, YC, Kubernetes, Prometheus, Grafana, Helm, Gitlab CI/CD.

---
##### Примеры работы с Ansible:
1. Пример `Role` для установки `Kibana`: [Kibana](https://github.com/AlexDies/kibana-role)
2. Пример `Role` для установки `Filebeat`: [Filebeat](https://github.com/AlexDies/filebeat-role/tree/main/playbook)
3. `Ansible playbook` для установки `Elasticsearch`, `Kibana`, `Filebeat`: [Elastiksearch & Kibana & Filebeat](https://github.com/AlexDies/AnsiblePlaybook/tree/Ansible_8_3)
4. `Ansible playbook` для установки `Kibana`, `Filebeat`, `Elasticsearch` с использованием `ansbile-galaxy` через роли: [EFK](https://github.com/AlexDies/AnsiblePlaybook/tree/Ansible_8_4)
5. Тестирования Role с использованием `Molecule` и `Tox`: [Molecule & Tox Testing](https://github.com/AlexDies/AnsiblePlaybook/tree/Ansible_8_5(TestRole))

---
##### Примеры работы с CI/CD:

1. Утановка(через ansible) и работа с `Jenkins` (Declarative Pipeline, Freestyle Job, Scripted Pipeline, Multibranch Pipeline). 
Тестирование и развертывание стека EFK на YC: [Jenkins](https://github.com/AlexDies/homework/blob/main/homework_9_4(Jenkins)/homework_9_4.md)

2. Установка и работа с `TeamCity`. 
Сборка через `maven` и хранение артефакта в `Nexus`: [TeamCity](https://github.com/AlexDies/homework/tree/main/homework_9_5(TeamCity))
3. Работа с `Gitlab`. 
Автосборка приложения (python) в docker-образ и пуш в репозиторий: [Gitlab](https://github.com/AlexDies/homework/tree/main/homework_9_6(GitLab))

---
##### Примеры работы с Terrafrom:

1. Подготовка EC2-инстансов в AWS: [AWS EC2](https://github.com/AlexDies/homework/tree/main/homework_7_2(terraform_ec2))
2. Создание `S3 bucket` в AWS для хранения state: [AWS S3](https://github.com/AlexDies/homework/blob/main/homework_7_3(terraform_basic(backend%2Cworkspace))/homework_7_3.md)
3. Работы с `Atlantis` и `TerraformCloud`: [Remote state](https://github.com/AlexDies/homework/tree/main/homework_7_4(terraform%20cloud%2C%20remote%20state%2C%20atlasin))
4. Создание VPC, Subnet, Route, NAT, VM в `YandexCloud`: [Работа в YC](https://github.com/AlexDies/homework/tree/main/homework_15.1(YC(Network)))

---
##### Примеры работы с Kubernetes:

1. Описание работы с Minikub: [Minikube](https://github.com/AlexDies/homework/blob/main/homework_12.1(Kuber%20component)/homework_12_1.md)
2. Развертывание кластера `Kubernetes` с `kuberspray`: [Установка Kubernetes](https://github.com/AlexDies/homework/tree/main/homework_12.4(Kuber%20install%20p2%20(kuberspray)))
3. Подготовка деплоя приложения (фронтенд, бекенд, БД (`statefulset`)) для dev и prod-окружения: [Пример деплоя](https://github.com/AlexDies/homework/tree/main/homework_13.1(Pods%2Cdeploy%2C%20service%2C%20ed%2C%20etc.))
4. Работа с NFS, Helm и Volume: [Примеры работы с PVC и NFS](https://github.com/AlexDies/homework/tree/main/homework_13.2(Mount))
5. Подготовка `Helm` чарта приложения: [Helm](https://github.com/AlexDies/homework/tree/main/homework_13.4(Helm%2C%20Jsonnet))
6. Работа с секретами `Kubernetes` с внешним `Vault`: [Secret Vault](https://github.com/AlexDies/homework/tree/main/homework_14.2(Vault))
7. Настройка `NetworkPolicies` и работа с `ServiceAccount` Kubernetes: [NetworkPolicies](https://github.com/AlexDies/homework/tree/main/homework_14.5(NetworkPolicies)), [ServiceAccount](https://github.com/AlexDies/homework/tree/main/homework_14.4(ServiceAccount))


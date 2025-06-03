# Concept: Порівняння інструментів для локального розгортання Kubernetes кластерів



#### Характеристики
| Характеристика | Minikube | Kind | k3d |
| Підтримувані ОС | Windows, macOS, Linux | Windows, macOS, Linux | Windows, macOS, Linux |
| Підтримка архітектур | amd64, arm64 | amd64, arm64 | amd64, arm64 |
| Потреба в Docker | Опційно (може використовувати VM) | Обов'язково | Обов'язково |
| Альтернатива Docker | Podman (експериментально) | Частково, з Podman | Частково, з Podman |
| Автоматизація | Так (CLI, API) | Так (CLI, YAML конфіг) | Так (CLI, YAML конфіг) |
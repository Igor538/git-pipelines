# Git-Pipelines – Git, GitHub e CI/CD

Este repositório foi criado com foco em versionamento de código, uso de branches, integração contínua (CI) e entrega contínua (CD).

---

## 📌 Tecnologias utilizadas

- Git
- GitHub
- GitHub Actions
- Bitbucket Pipelines
- Python 3.11

---

## 🌿 Controle de Versão

O projeto utiliza Git para controle de versão, com as seguintes práticas:

- Inicialização de repositório Git
- Commits descritivos
- Uso de branches (`master` e `feature/*`)
- Merge de branches
- Resolução de conflitos
- Uso de `git stash`, `git reset` e `git revert`

---

## 🔄 CI/CD com GitHub Actions

Foi configurado um pipeline de Integração Contínua utilizando **GitHub Actions**, acionado automaticamente em eventos de `push` e `pull request`.

### Funcionalidades do pipeline:
- Checkout do código
- Configuração do ambiente Python
- Execução de testes simples
- Simulação de envio de alerta para Slack/Teams

Arquivo:
```
.github/workflows/django.yml
```

---


## 🚀 Deploy Manual

Foi criado um script de deploy manual para simular o processo de implantação do projeto.

Arquivo:
```
deploy.bat
```

O script executa:
- Verificação do ambiente
- Simulação de testes
- Simulação de deploy
# Módulo 12 – Git, GitHub e CI/CD

Este repositório foi criado como parte dos exercícios do Módulo 12, com foco em versionamento de código, uso de branches, integração contínua (CI) e entrega contínua (CD).

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
.github/workflows/python-ci.yml
```

---

## 🔁 CI/CD com Bitbucket Pipelines

Também foi configurado um pipeline equivalente utilizando **Bitbucket Pipelines**, com etapas de:

- Execução de testes
- Simulação de deploy automático
- Mensagens de status do pipeline

Arquivo:
```
bitbucket-pipelines.yml
```

---

## 🔔 Notificações (Exercício 28)

A integração com ferramentas de comunicação como Slack ou Microsoft Teams foi **simulada** dentro dos pipelines, demonstrando como alertas automáticos podem ser enviados ao final da execução do CI/CD.

---

## 🌐 Webhook (Exercício 27)

Foi realizada a tentativa de configuração de webhook no GitHub para notificação de eventos de push, utilizando o serviço webhook.site para testes.

Apesar de limitações no ambiente de teste, o conceito e o funcionamento do webhook foram compreendidos e documentados.

---

## 🚀 Deploy Manual (Exercício 29)

Foi criado um script de deploy manual para simular o processo de implantação do projeto.

Arquivo:
```
deploy.bat
```

O script executa:
- Verificação do ambiente
- Simulação de testes
- Simulação de deploy

---

## 📄 Conclusão

Este projeto demonstra a aplicação prática de versionamento com Git, integração contínua e entrega contínua (CI/CD), utilizando ferramentas amplamente adotadas no mercado.

Todos os exercícios do módulo foram implementados e documentados conforme proposto.

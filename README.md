# Vagrant — Ambientes de Aplicações IASEP

Repositório destinado ao gerenciamento de ambientes virtuais utilizando Vagrant, com infraestrutura definida como código (IaC) para implantação, configuração e testes de aplicações utilizadas no ambiente de TI do IASEP.

O objetivo é disponibilizar ambientes padronizados, reproduzíveis e isolados para aplicações como Zabbix, GLPI, Wiki.js, Vaultwarden, entre outras.

---

### 📋 Sumário
* Objetivos
* Arquitetura
* Estrutura do Repositório
* Aplicações
* Tecnologias
* Pré-requisitos
* Instalação
* Utilização
* Gerenciamento das VMs
* Provisionamento
* Rede
* Boas Práticas
* Segurança
* Ambientes
* Troubleshooting
* Roadmap
* Contribuição
* Licença

---

### 🎯 Objetivos

Este repositório tem como objetivos:

* Padronizar a criação de máquinas virtuais.
* Facilitar a implantação de aplicações para laboratório e homologação.
* Permitir a reprodução dos ambientes em diferentes computadores.
* Utilizar Infrastructure as Code (IaC).
* Automatizar o provisionamento das máquinas.
* Facilitar testes de novas versões das aplicações.
* Criar ambientes isolados para desenvolvimento e homologação.
* Reduzir configurações manuais.
* Documentar a infraestrutura das aplicações.
* Servir como base para futuras integrações com Ansible, Terraform, GitLab CI/CD e GitOps.

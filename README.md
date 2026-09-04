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

---

### 📦 Pré-requisitos

Antes de utilizar os ambientes, instale:
```
Vagrant
vagrant --version
VirtualBox
VBoxManage --version
Git
git --version
```
Opcionalmente:

```
ansible --version
🚀 Instalação

Clone o repositório:

git clone <URL_DO_REPOSITORIO>
```
Entre no diretório:

```
cd vagrant
```

Escolha a aplicação:
```
cd zabbix
```
Inicialize o ambiente:
```
vagrant up
```
Após a criação da máquina:
```
vagrant status
```
Acesse a VM:
```
vagrant ssh
```

---

### ⚙️ Utilização

Cada aplicação possui seu próprio Vagrantfile.

Exemplo:
```
cd glpi
vagrant up
```
Para acessar:
```
vagrant ssh
```
Para desligar:
```
vagrant halt
```
Para iniciar novamente:
```
vagrant up
```
Para destruir o ambiente:
```
vagrant destroy
```

---
### 🖥️ Gerenciamento das VMs

Verificar status
```
vagrant status
```
Iniciar
```
vagrant up
```
Reiniciar
```
vagrant reload
```
Desligar
```
vagrant halt
```
Acessar
```
vagrant ssh
```
Destruir
```
vagrant destroy
```
Recriar completamente
```
vagrant destroy -f
vagrant up
```

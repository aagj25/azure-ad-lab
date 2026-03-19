# 🧪 Azure Active Directory Lab (Windows Server + GPO)

Projeto prático de implementação de ambiente corporativo utilizando Windows Server com Active Directory em ambiente cloud.


## 📌 Objetivo
Simular um ambiente empresarial com controle de usuários, permissões e políticas de segurança.


## ☁️ Infraestrutura
* 1 VM Windows Server (Domain Controller)
* 1 VM Windows 10 (cliente)
* Rede virtual configurada (VNet e Subnet)
* Comunicação interna entre máquinas

---

## ⚙️ Tecnologias utilizadas

* Microsoft Azure
* Windows Server
* Active Directory
* Group Policy (GPO)
* DNS
* RDP

---

## 🚀 Etapas do projeto

### 1. Criação da infraestrutura

* Criação de Resource Group
* Criação de VNet e Subnet
* Provisionamento das VMs

---

### 2. Configuração do Domain Controller

* Instalação da role Active Directory Domain Services
* Promoção do servidor a Domain Controller
* Criação do domínio

---

### 3. Gerenciamento de usuários e grupos

* Criação de usuários (ex: maria.santos, joao.silva)
* Criação de grupos (ex: GRP_FINANCEIRO)
* Organização em OU

---

### 4. Ingresso de máquina no domínio

* Configuração de DNS apontando para o DC
* Join do Windows 10 no domínio

---

### 5. Configuração de File Server

* Criação de pasta compartilhada
* Permissões NTFS e Share
* Controle de acesso por grupo

---

### 6. Aplicação de GPO

* Criação de políticas de usuário
* Bloqueio de funcionalidades do sistema
* Aplicação via OU

---

### 7. Testes de acesso

* Login com usuários do domínio
* Validação de permissões
* Acesso a recursos de rede

---

## 📸 Evidências

*(adicione seus prints aqui depois)*

---

## 🧠 Aprendizados

* Implementação de ambiente de domínio
* Gerenciamento de identidades e acessos
* Aplicação de políticas corporativas
* Diagnóstico de problemas de autenticação e rede

---

## 💼 Aplicação profissional

Este projeto simula um ambiente corporativo real, com controle de usuários, permissões e políticas, semelhante a cenários encontrados em suporte técnico nível.


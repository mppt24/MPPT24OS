# MPPT24OS
Sistema Operativo de IA distribuído (Servidor + IAs + Clientes + Infraestrutura).  

## MPPT24 ESCUDO

Inventário visual do software e dos serviços do servidor doméstico de segurança.

[![Infográfico do MPPT24 ESCUDO com Ubuntu Server, Arch Linux e o inventário de software](docs/mppt24-escudo-infografico.png)](docs/mppt24-escudo-infografico.png)

[Ver infográfico em tamanho completo](docs/mppt24-escudo-infografico.png)

Este projeto é composto por **4 repositórios principais**:

---

## 🔹 [ai-hub-publish](https://github.com/mppt24/ai-hub-publish)
Repositório para partilhar **prompts, respostas e ideias de IA**.  
Estrutura:
- `prompts/` → prompts em `.txt` ou `.md`
- `respostas/` → respostas em `.json` ou `.txt`
- `docs/` → documentação

---

## 🔹 [MPPT24OS](https://github.com/mppt24/MPPT24OS)
Repositório principal com toda a **arquitetura do sistema**.  
Estrutura:
- `docs/` → Documentação  
- `server/` → Configuração do servidor  
- `ai/` → Modelos de IA  
- `clients/` → Clientes (web, mobile, etc.)  
- `infra/` → Infraestrutura  
- `scripts/` → Automação  

---

## 🔹 [rustlinux-termux-installer](https://github.com/mppt24/rustlinux-termux-installer)
Instalador de **Rust no Termux**, com verificação automática.  
Scripts incluídos:
- `scripts/check.sh`
- `scripts/install.sh`

---

## 🔹 [mppt24-server-setup](https://github.com/mppt24/mppt24-server-setup)
Scripts para **configurar e atualizar o servidor**.  
Inclui:
- `scripts/setup.sh`
- `scripts/update.sh`

---

## 🚀 Como contribuir
1. Faça um **fork** de qualquer repositório.  
2. Adicione melhorias.  
3. Envie um **Pull Request**.

Todos os projetos estão sob **Licença MIT**.

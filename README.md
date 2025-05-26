# 💻 Projeto - Máquina Virtual no Azure

Este repositório documenta a criação e configuração de uma máquina virtual (VM) na plataforma Microsoft Azure. O objetivo é demonstrar o provisionamento de uma VM e a hospedagem de [descreva o que está rodando nela, ex: um site, servidor web, banco de dados etc].

---

## ☁️ Detalhes da Máquina Virtual

- **Provedor**: Microsoft Azure  
- **Sistema Operacional**: Ubuntu Server 22.04 LTS *(ou outro que você usou)*  
- **Tamanho**: Standard B1s  
- **IP Público**: `xxx.xxx.xxx.xxx` *(coloque o IP real da VM)*  
- **Portas Liberadas**: 22 (SSH), 80 (HTTP) *(adicione outras se necessário)*  
- **Usuário de acesso**: `seu-usuario`  
- **Método de login**: senha ou chave SSH  

---

## 📦 Conteúdo Hospedado na VM

Descreva o que tem dentro da VM:

- [ ] Aplicação web (ex: Node.js, Python Flask, etc.)
- [ ] Site em HTML/CSS
- [ ] Banco de dados (ex: MySQL, SQLite)
- [ ] Outros serviços (especifique)

---

## 🛠️ Como Criar Esta VM no Azure

1. Acesse [https://portal.azure.com](https://portal.azure.com)
2. Vá em **"Criar um recurso" > "Máquina virtual"**
3. Configure:
   - **Imagem**: Ubuntu 22.04 LTS
   - **Tamanho**: Standard B1s
   - **Usuário e senha/SSH**
4. **Abrir portas**: Adicione as portas necessárias (22, 80, 443...)
5. Clique em **"Revisar + criar"** e depois em **"Criar"**

---

## 🚀 Como Acessar a VM

Se for Linux:
```bash
ssh seu-usuario@xxx.xxx.xxx.xxx


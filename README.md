# projetoASA
# Projeto ASA

Este projeto contém um **playbook Ansible** para configuração automática de servidores. Ele instala e configura o **Docker** e o **Docker Compose**, além de outras dependências necessárias para o ambiente.

## 📌 Funcionalidades
- Configuração do hostname
- Instalação de pacotes essenciais
- Instalação e configuração do Docker
- Adição do usuário ao grupo `docker`
- Deploy de serviços com Docker Compose

## 🚀 Como Usar
1. Certifique-se de ter o **Ansible** instalado.  
2. Clone o repositório:  
   ```bash
   git clone git@github.com:diegosls/projetoASA.git
cd projetoASA
ansible-playbook playbook.yml -i inventory


Agora basta adicionar ao repositório e fazer o commit:

```bash
echo "# Projeto ASA" > README.md
git add README.md
git commit -m "Adicionando README"
git push origin master

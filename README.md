# 🚀 Linux Essencial – Adriano Souza

> Projeto de estudo e documentação dos principais conceitos e comandos do Linux.  
> Este material foi criado com o objetivo de compartilhar conhecimento, servir de consulta rápida e ajudar outros profissionais que estão iniciando na área de infraestrutura, cloud ou DevOps.

## 🗺️ Sumário
- [📂 Navegação no Sistema de Arquivos](#-navegação-no-sistema-de-arquivos)
- [🔐 Permissões e Propriedades](./permissoes/README.md)
- [👥 Usuários e Grupos](#-usuários-e-grupos)
- [⚙️ Processos e Serviços](#-processos-e-serviços)
- [📦 Gerenciamento de Pacotes](#-gerenciamento-de-pacotes)
- [📝 Análise de Logs](#-análise-de-logs)
- [🔗 Referências](#-referências)

## 📂 Navegação no Sistema de Arquivos
O Linux usa uma estrutura hierárquica. Para navegar no sistema de arquivos, usamos comandos como:

```bash
pwd      # Mostra o diretório atual
ls       # Lista arquivos e pastas
cd       # Navega entre diretórios
mkdir    # Cria pastas
touch    # Cria arquivos
```

## 🧠 Exemplo prático:
```bash
pwd
/home/adriano

cd Documentos
mkdir projetos
cd projetos
touch arquivo.txt
ls -l
```

### 📸 Exemplo visual:
![pwd](imagens/navegacao-pwd.png)
![ls](imagens/navegacao-ls.png)

## 🔗 Referências
- https://linuxjourney.com/
- https://linuxcommand.org/
- https://www.digitalocean.com/community/tutorials
- https://help.ubuntu.com/

## 📝 Licença
Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

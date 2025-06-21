# 🔐 Permissões e Propriedades no Linux – Adriano Souza

> Projeto de estudo focado em entender e documentar o sistema de permissões e propriedades no Linux.  
> Material criado com objetivo de aprendizado, compartilhamento de conhecimento e consulta rápida.

## 🗺️ Sumário
- [📂 Navegação no Sistema de Arquivos](#-navegação-no-sistema-de-arquivos)
- [🔐 Permissões e Propriedades](#-permissões-e-propriedades)
- [🔗 Referências](#-referências)

## 🔐 Permissões e Propriedades

O Linux controla o acesso aos arquivos com três tipos de permissões:

| Permissão | Símbolo | Ação        |
|------------|---------|-------------|
| r          | Read    | Ler         |
| w          | Write   | Escrever    |
| x          | Execute | Executar    |

Cada arquivo ou pasta possui permissões para:
- **Usuário (Owner)**
- **Grupo (Group)**
- **Outros (Others)**

### 🔧 Alterando Permissões:
- `chmod 755 arquivo` → rwx r-x r-x
- `chmod u+x arquivo` → Adiciona execução para usuário
- `chmod g-w arquivo` → Remove escrita do grupo

### 👑 Alterando Propriedades:
- `chown usuario:grupo arquivo` → Altera dono e grupo

### 🧠 Exemplo:
```bash
mkdir teste-permissoes
cd teste-permissoes
touch arquivo.txt
chmod 755 arquivo.txt
chown adriano:desenvolvedores arquivo.txt
ls -l arquivo.txt
```

### 📸 Resultado:
![ls](imagens/permissoes-ls.png)
![chmod](imagens/permissoes-chmod.png)
![chown](imagens/permissoes-chown.png)

## 🔗 Referências
- https://linuxjourney.com/
- https://linuxcommand.org/
- https://www.digitalocean.com/community/tutorials
- https://help.ubuntu.com/

## 📝 Licença
Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.
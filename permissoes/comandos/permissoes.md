# 🔐 Permissões e Propriedades no Linux

## 🧠 Conceito
No Linux, cada arquivo e pasta tem permissões que controlam quem pode ler (r), escrever (w) e executar (x) o conteúdo. Essas permissões são atribuídas a três categorias:
- **Usuário (owner)**
- **Grupo (group)**
- **Outros (others)**

## 🔍 Visualizando Permissões
```bash
ls -l
```

## 🔧 Modificando Permissões com `chmod`
| Valor | Permissão |
|-------|-----------|
| 4     | Read      |
| 2     | Write     |
| 1     | Execute   |

- **Exemplo:** `chmod 755 arquivo`
- **Explicação:** rwx r-x r-x

## 👑 Modificando Propriedades com `chown`
```bash
chown usuario:grupo arquivo
```

## 🧪 Exemplo Prático
```bash
mkdir teste-permissoes
cd teste-permissoes
touch arquivo.txt
chmod 755 arquivo.txt
ls -l
chown adriano:desenvolvedores arquivo.txt
```

## 🖼️ Exemplos Visuais
- ![ls](../imagens/permissoes-ls.png)
- ![chmod](../imagens/permissoes-chmod.png)
- ![chown](../imagens/permissoes-chown.png)

---
# Git instruções de uso

## Clonando um repositório
```
git clone endereco_do_repositorio
```

## Navegação entre branchs

### Criando nova branch
Na branch que você deseja utilizar como base utilizar o comando:
```
git checkout -b nome-da-nova-branch
``` 

### Navegar entre branchs
```
git checkout nome-da-branch
```

### Listar branchs locais
```
git branch
```

## Commitando código

### Verificar alterações locais:
```
git status
```

### Selecionar arquivos para commit:
```
git add endereco-do-arquivo
```

### Criando o commit local
```
git commit
```

Ao executar o comando git commit o terminal irá abrir um editor de texto para escrever a mensagem de commit, por padrão vem o [vim](https://www.vim.org/) instalado, mas isso é configurável.

### Subir minhas alterações no repositório online
```
git push
```

## Verificar histórico da branch
```
git log
```

## Como atualizar o repositório local
```
git fetch
```

```
git pull
```

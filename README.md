# testing-git

## 1. Copiar um repositório remoto
```
git clone {link do repositório}
```

## 2. Adicionar alterações de um repositório local
```
git add {caminho do arquivo a ser adicionado/* ou . para adicinar todas alterações}
```

## 3. Empacotar alterações de um repositório local
```
git commit -m {descrição da alteração}
```

## 4. Subir alterações de um repositório local para um repositório remoto(Depois do passo 2 e 3)
```
git push --set-upstream {link do repositório remoto} {nome da branch do repositório local}
```

## 5. Puxar todas as branchs de um repositório remoto para um repositório local(Depois do passo 1)
```
git fetch --prune --all
```

## 6. Mostrar branchs do repositório local
```
git branch
```

## 7. Mostrar branchs do repositório local(Depois do passo 1)
```
git branch -a
```

## 8. Alterar branch a branch local
```
git checkout {nome da branch}
```

## 8. Criar uma branch local
```
git checkout -b {nome da branch}
```

## 9. Mostra informações detalhadas de uma branch
```
git show
```

## 10. Mostrar o historicos de commits de um repositório
```
git log
```

## 10. Mostrar alterações não commitadas de uma branch
```
git status
```

## 11. Atualizar branch local apartir da remota
```
git pull origin
```

## 12. Apagar branch remota
```
git push origin :{nome da branch}
```

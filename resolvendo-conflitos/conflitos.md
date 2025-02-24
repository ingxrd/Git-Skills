### ⚔️ **Resolvendo Conflitos**

Conflitos acontecem quando duas ou mais pessoas editam a mesma parte do código. Para resolver:

1. Tente fazer o merge com as novas atualizações.

```
git merge branch-b  # Realiza o merge da branch 'branch-b' para a branch atual 
```
2. Caso ocorra um conflito, você pode resolvê-lo manualmente, editando os arquivos afetados.

3. Após resolver os conflitos, adicione as alterações e realize um commit.

```
git add . # Adiciona as alterações resolvidas
git commit -m "Resolvendo conflitos"  # Cria um commit com a resolução
```


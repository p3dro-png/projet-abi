# Registro de Conflito de Merge

## O que causou o conflito
As branches 'branch-a' e 'branch-b' alteraram a mesma linha (o <h1> do index.html) com textos diferentes.

## Como foi resolvido
Ao tentar mesclar branch-b na main (após já ter mesclado branch-a), o Git sinalizou o conflito.
O arquivo index.html foi editado manualmente, escolhendo o texto final e removendo as marcações
<<<<<<< HEAD, ======= e >>>>>>> branch-b. Em seguida, as mudanças foram adicionadas (git add) e
commitadas (git commit), finalizando o merge.

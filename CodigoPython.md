# Codigo em Python

```
import pandas as pd

df = pd.read_excel("base_notas.xlsx")

#f['Média'] = df[['Nota1', 'Nota2', 'Nota3', 'Nota4']].mean(axis=1)
df['Média'] = df[['Nota1', 'Nota2', 'Nota3', 'Nota4']].mean(axis=1)
df.to_excel('nota_aluno.xlsx', index=False)
```

Este código em python faz uma modificação em um arquivo do excel.
Neste código em específico ele pega quatro notas dos alunos e cria mais uma coluna com a média final de cada aluno.

## Demonstração do código de python em ação

### Antes

![Imagem](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/Antes_do_Python.PNG)

### Depois

![Imagem](https://github.com/TymotheoTrisch/UC10_Documentacao/blob/main/Depois_do_Python.PNG)

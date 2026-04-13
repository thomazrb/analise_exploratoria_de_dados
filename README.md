# Análise Exploratória de Dados - Datasets

Repositório público que hospeda os datasets usados na disciplina **Análise Exploratória de Dados** da Pós-Graduação em Inteligência Artificial do Ifes Campus São Mateus.

**Professor:** Thomaz Rodrigues Botelho

## Para que serve

Os notebooks da disciplina são disponibilizados pelo AVA (Moodle). Quando um notebook precisa carregar um dataset, ele lê direto daqui pela URL raw, por exemplo:

```python
import pandas as pd

url = 'https://raw.githubusercontent.com/<usuario>/analise_exploratoria_de_dados/main/datasets/cafe-es-producao.csv'
df = pd.read_csv(url)
```

Assim o aluno não precisa baixar nada, montar Google Drive nem configurar pasta: é só abrir o notebook no Colab e executar.

## Estrutura

```
datasets/
  cafe-es-producao.csv   # Produção de café conilon por município do norte do ES
```

## Licença

Material didático de uso livre para fins educacionais.


# Construção de grafos dependenciais conforme o modelo UD

Repositório com a resolução do exercício prático de análise sintática segundo o modelo Universal Dependencies (UD).

## Conteúdo

A resolução completa está disponível no notebook [`UD_Analysis.ipynb`](UD_Analysis.ipynb), que inclui:

1. Representação das duas sentenças no formato CoNLL-U e validação com o validador oficial do UD.
2. Visualização dos grafos com dois visualizadores online de CoNLL-U.
3. Construção dos grafos utilizando o script `DepTree.py`.
4. Análise de quatro sentenças do Kadiwéu, extraídas de Sandalo e Galves (2025, p. 3).

O arquivo [`exemplos.conllu`](exemplos.conllu) contém as anotações das duas sentenças em português.Todos os grafos de dependências estão disponíveis na pasta [`figures/`](figures/).

## Ferramentas utilizadas

- [Universal Dependencies](https://universaldependencies.org/)
- [CoNLL-U Viewer (Groningen)](https://urd2.let.rug.nl/~kleiweg/conllu/)
- [UD CoNLL-U Viewer](https://universaldependencies.org/conllu_viewer.html)
- [DepTree.py](https://github.com/CompLin/nheengatu/blob/main/src/DepTree.py)
- Python e Google Colab

## Uso de IA generativa

O ChatGPT (OpenAI) foi utilizado como ferramenta de apoio na elaboração e revisão das análises, do código e da documentação.

## Referências

- Universal Dependencies. [Documentação oficial](https://universaldependencies.org/).
- Sandalo, F. e Galves, C. (2025). *A brief description and analysis of tense, finiteness, and verbal embedding strategies in Kadiwéu*.

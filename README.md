# Estudo Dirigido 1 - Planejamento e Análise Estatística de Experimentos (PAEE)

Este repositório contém um Jupyter Notebook desenvolvido para a disciplina de **PAEE** do CEFET-MG, focado na simulação e compreensão do conceito de **intervalo de confiança** na estatística.

## 📘 Descrição

O notebook tem como objetivo ilustrar e validar, de forma prática, o conceito de confiança de um intervalo. Para isso, são abordados os seguintes tópicos:

- Geração de uma população simulada com distribuição normal.
- Extração de múltiplas amostras da população.
- Cálculo de intervalos de confiança para a média.
- Verificação empírica do conceito de nível de confiança.
- Visualização dos intervalos que contém ou não a média populacional.

## 🧠 Conceitos abordados

- **Nível de confiança:** Proporção dos intervalos que, a longo prazo, conterão a média populacional verdadeira.
- **Intervalo de confiança:** Construção utilizando distribuições amostrais e o teorema central do limite.
- Diferença entre **nível de confiança** e **probabilidade de conter a média populacional em um único intervalo**.

## 🛠️ Ferramentas e Pacotes

- Linguagem: **R v4.5**
- Ambiente: **Jupyter Notebook** com suporte ao kernel de R (`IRkernel`)
- Funções principais usadas:
  - `rnorm()` - geração de dados normais
  - `sample()` - seleção de amostras
  - `t.test()` - cálculo do intervalo de confiança

## ▶️ Execução

Para executar este notebook:

1. Instale o kernel de R para Jupyter (`IRkernel`):
   ```r
   install.packages("IRkernel")
   IRkernel::installspec()
````

2. Execute no Jupyter Notebook.
3. Certifique-se de ter os pacotes padrão do R instalados.

## 🎯 Objetivos de Aprendizado

* Compreender profundamente o conceito de intervalo de confiança.
* Realizar simulações estatísticas para validar conceitos teóricos.
* Interpretar corretamente o significado de um nível de confiança.

## ✍️ Autor

Este notebook foi desenvolvido como parte das atividades da disciplina ministrada pelos professores Elizabeth Fialho Wanner e Fabio Rocha da Silva.

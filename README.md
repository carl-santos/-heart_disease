# Nanodegree Engenheiro de Machine Learning
# Projeto de conclusão de machine learning
## Projeto: Prevendo a existência de doenças cardíacas (Heart Disease UCI)

### Instalação

Este projeto requer **Python 3.7** e as seguintes bibliotecas Python instaladas:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [Matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/)



Você também precisará ter software instalado para rodar e executar um [iPython Notebook](http://ipython.org/notebook.html)

### Código

O código é fornecido no arquivo notebook `final_project_1.ipynb`. Você também precisará usar o o arquivo de dados `heart.csv` para executar o notebook. 

### Execução

Em um terminal ou janela de comando, navegue até o diretório raiz de projeto 'final_project_1.ipynb'/` (que contém este README) e execute os seguintes comandos:

```bash
ipython notebook final_project_1.ipynb
```  
ou
```bash
jupyter notebook final_project_1.ipynb
```

Isso abrirá o o software e arquivo de projeto iPython Notebook em seu navegador.

### Dados

O conjunto de dados é o dataset (Heart Disease UCI) oriundo de uma pesquisa que envolveu 5 Instituições Médicas, de mais de um país, que obteve informações de pacientes com objetivo de identificar a existência de doença cardíaca. Esse conjunto de dados é um subconjunto com 14 atributos (originalmente eram 76 atributos) e 303 entradas que fizeram parte da pesquisa da Cleveland Clinic Foundation. 

O conjunto de dados original hospedado em https://www.kaggle.com/ronitf/heart-disease-uci.

**Atributos**

* 1.	age (idade em anos);
* 2.	sex (1 para masculino e 0 para feminino); 
* 3.	chest pain type (tipo de dor no peito, dividada em 4 valores); 
* 4.	resting blood pressure (pressão arterial em repouso (em mmHg na admissão ao hospital)); 
* 5.	serum cholestoral in mg/dl (colesterol sérico);
* 6.	fasting blood sugar > 120 mg/dl (açucar no sangue em jejum ((1 = verdadeiro; 0 = falso));
* 7.	resting electrocardiographic results (resultados eletrocardiográficos em repouso(valores 0,1,2));
* 8.	maximum heart rate achieved (frequência cardíaca máxima alcançada);
* 9.	exercise induced angina (angina induzida por exercício (1 = sim; 0 = não));
* 10.	oldpeak = ST depression induced by exercise relative to rest (depressão do segmento ST induzida pelo exercício em relação ao repouso); 
* 11.	the slope of the peak exercise ST segment (a inclinação do segmento ST de pico do exercício);
* 12.	number of major vessels (0-3) colored by flourosopy;
* 13.	thal: 3 = normal; 6 = fixed defect; 7 = reversable defect.;
* 14.	target (VARIAVEL ALVO) = sendo 1 para possuí doença e 0 para não possuí doença.


**Variável-alvo**
- `target`: sendo 1 para possuí doença e 0 para não possuí doença.
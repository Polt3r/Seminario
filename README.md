# Seminario

## Vinho Vermelho
A certificação da qualidade do vinho é essencial para a indústria vitivinícola. O principal objetivo deste trabalho é desenvolver um modelo de aprendizado de máquina para prever a qualidade do vinho usando o conjunto de dados. Utilizamos amostras do conjunto de dados de vinho tinto (RWD) com onze propriedades físico-químicas distintas. Com o RWD inicial, cinco modelos de aprendizado de máquina (ML) foram treinados e colocados à prova. Os algoritmos mais precisos são Random Forest (RF) e Extreme Gradient Boosting (XGBoost). Usando essas duas abordagens de ML, os três principais recursos de um total de onze recursos são escolhidos e a análise de ML é realizada nos recursos restantes. Vários gráficos são empregados para demonstrar a importância do recurso com base no modelo XGBoost e RF. A qualidade do vinho foi prevista utilizando características relevantes, muitas vezes referidas como elementos fundamentais, que se revelaram essenciais durante o procedimento de seleção das características. Quando treinado e testado sem seleção de recursos, com seleção de recursos (RF) e com atributos-chave, o classificador XGBoost apresentou 100% de precisão. Na presença de variáveis ​​essenciais, o classificador RF teve melhor desempenho. Por fim, para avaliar a precisão de suas previsões, os autores treinaram um classificador RF, validaram-no e alteraram seus hiperparâmetros. Para abordar a colinearidade e diminuir a quantidade de preditores sem sacrificar a precisão do modelo, também utilizamos a análise de cluster.

<b>PDF:</b> https://www.nature.com/articles/s41598-023-44111-9#Sec3 </br>
<b>Dataset 1:</b> https://archive.ics.uci.edu/dataset/186/wine+quality </br>
<b>Dataset 2:</b> https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009 </br>

### <b>Algoritoms Utilizados</b></br>
O artigo descreve a aplicação de algoritmos de aprendizado de máquina, incluindo a análise de componentes principais (PCA) e redes neurais artificiais (ANN), para prever a qualidade do vinho. Os dados foram divididos em conjuntos de treinamento e teste, e técnicas de validação cruzada foram utilizadas para avaliar a precisão dos modelos. Os resultados mostraram que as ANN superaram outros métodos em termos de desempenho.

## Movie Review
Propomos e validamos um novo esquema de transmissão semântica óptica utilizando fibra multimodo
(MMF). Ao aproveitar a sensibilidade à frequência da dispersão intermodal em MMFs, alcançamos
codificação e decodificação semântica de alta dimensão no domínio da frequência. Nossos mapas de sistema
símbolos para 128 frequências distintas espaçadas em intervalos de 600 kHz, demonstrando uma
aumento na capacidade em comparação com a codificação de comunicação convencional. Melhoramos ainda mais
eficiência espectral implementando modulação de amplitude de pulso de 4 níveis (PAM-4), alcançando
9,12 bits/s/Hz sem erros de decodificação. Além disso, exploramos a aplicação deste sistema
para análise de sentimento usando o conjunto de dados de resenhas de filmes da IMDb. Ao codificar semanticamente semelhantes
símbolos para frequências adjacentes, a tolerância ao ruído do sistema é efetivamente melhorada,
facilitando a análise precisa do sentimento. Este trabalho destaca o potencial da tecnologia baseada em MMF
comunicação semântica para aumentar a capacidade e robustez na comunicação óptica
sistemas, oferecendo aplicações promissoras em ambientes ruidosos e com restrição de largura de banda.

<b>PDF: </b>https://arxiv.org/pdf/2409.00066 </br>
<b>Dataset: </b>https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews/discussion?sort=hotness

### <b>Algoritoms Utilizados</b></br>
O artigo apresenta um esquema de comunicação semântica óptica utilizando fibra multimodo (MMF). Ele implementa modulação por amplitude de pulso em 4 níveis (PAM-4) para aumentar a eficiência espectral e alcançar 9,12 bits/s/Hz. A pesquisa também aplica essa abordagem em uma análise de sentimentos, utilizando um conjunto de dados de resenhas de filmes do IMDb, onde símbolos semanticamente semelhantes são mapeados para frequências adjacentes, melhorando a tolerância ao ruído e a precisão da análise.





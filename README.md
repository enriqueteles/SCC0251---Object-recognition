
<br />
<p align="center">
  <h2 align="center">SCC0251 - Reconhecimento de objeto por template</h2>

  <p align="center">
    Reconhecer um determinado objeto dado uma imagem template e uma imagem em que será feita a análise e destacar o objeto localizado. Os inputs serão as duas imagens e o output será a imagem com o objeto alvo destacado.
    <br />
  </p>
</p>

<br />

Inicialmente vamos começar gerando nossas próprias imagens de input para ir aumentando a dificuldade gradualmente, tendo como objetivo final, a fim de teste, achar a solução do jogo "onde está Wally?" dado o cenário e o Wally (podendo ser de outro cenário).

<br/>

### Template Matching
Primeiramente vamos implementar uma solução baseada na técnica `template matching` usando um coeficiente de correlação (calculado usando cross-correlation normalizado) para achar o objeto desejado e destacá-lo

Depois de ter feito a base, pretendemos experimentar utilizar técnicas de `Image Enhancement` para tentar conseguir resultados melhores.

Também, dependendo do tempo, implementar a solução utilizando uma técnica mais elaborada.
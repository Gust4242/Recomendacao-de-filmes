# Recomendação de filmes
 Algoritmo de recomendação de filmes utilizando *cosine similarity* e técnicas de NLP

 Cheque também o vídeo onde explico com mais detalhes (aqui)[https://www.youtube.com/watch?v=tGMllk5YJRQ]

## Dados
Foi utilizada uma base de mais de 9000 filmes e 100_000 avaliações do site MovieLens, além tags associadas e uma base de ficha técnica do IMDb

## Recomendador
Duas abordagens utilizadas:

 1. User-based:

![Imagem1](https://github.com/Gust4242/Recomendacao-de-filmes/assets/90975619/5673b9f0-7d72-44a5-94f9-59145944c398)

 - Tem como base as avaliações postadas pelos usuários
 - Busca filmes que receberam notas similares pelos mesmos usuários
 
 2. Content-based:

![Imagem2](https://github.com/Gust4242/Recomendacao-de-filmes/assets/90975619/f7806b5d-ca4c-4be2-9218-febf8beae236)

 - Tem como base as características de cada filme, como *casting*, diretor, sinopse, e tags marcadas
 - Utilizado um vetorizador de palavras para a mensuração da similaridade
 
A ideia por trás de ambos os algoritmos é a transformação dos filmes em vetores de modo que sua similaridade - e consequentemente, a recomendação - era dada pelo cossseno do ângulo formado por esses vetores.
![Similaridade de cossenos](https://github.com/Gust4242/Recomendacao-de-filmes/assets/90975619/52432d07-2451-4327-92d8-6453bd014c4a)

## Oportunidades de melhoria
- Definição de funções para uma leitura melhor do código e maior aplicabilidade
- Utilização de datasets maiores e mais atualizados
- Criação de um site/dashboard em que fosse possível visualizar melhor as recomendações

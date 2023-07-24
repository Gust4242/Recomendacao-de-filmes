# Recomendação de filmes
 Algoritmo de recomendação de filmes utilizando *cosine similarity* e técnicas de NLP

## Dados
Foi utilizada uma base de mais de 9000 filmes e 100_000 avaliações do site MovieLens, além tags associadas e uma base de ficha técnica do IMDb

## Recomendador
Duas abordagens utilizadas:

 1. User-based:
 - Tem como base as avaliações postadas pelos usuários
 - Busca filmes que receberam notas similares pelos mesmos usuários
 
 2. Content-based:
 - Tem como base as características de cada filme, como *casting*, diretor, sinopse, e tags marcadas
 - Utilizado um vetorizador de palavras para a mensuração da similaridade
 
A ideia por trás de ambos os algoritmos é a transformação dos filmes em vetores de modo que sua similaridade - e consequentemente, a recomendação - era dada pelo cossseno do ângulo formado por esses vetores.

## Oportunidades de melhoria
- Definição de funções para uma leitura melhor do código e maior aplicabilidade
- Utilização de datasets maiores e mais atualizados
- Criação de um site/dashboard em que fosse possível visualizar melhor as recomendações

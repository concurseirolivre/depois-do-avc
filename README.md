# Depois do AVC

Aplicativo educativo para pacientes que tiveram AVC (AVE) e suas famílias. Foi feito com base no roteiro "Educação em saúde e continuidade do cuidado ao paciente com AVE" da Unidade de AVC (UAVE · HMGV).

O conteúdo é educativo e não substitui a orientação da equipe de saúde.

## O que tem no app

- **Mapa da jornada** com 7 paradas, pontos de cuidado e medalhas
- **Tema 1 · Conhecendo o AVC:** animação narrada dos tipos de AVC, sinais do S.A.M.U e os jogos "É sinal de AVC ou não?", "Faça ou não faça" e memória dos fatores de risco
- **Tema 2 · Cuidados na internação:** quarto da Unidade de AVC para explorar, lavagem das mãos, "Pode fazer ou chame a equipe?", como conversar e complicações
- **Tema 3 · Sequelas e reabilitação** (Fala, Força e Função)
- **Tema 4 · Cuidados após a alta:** CASA SEGURA, jogo dos 6 riscos de queda e lista de remédios
- **Tema 5 · Prevenção de um novo AVC:** os cinco controles
- **Desafio final** com certificado

## Estrutura

```
index.html   o app inteiro (HTML, CSS e JavaScript)
img/         ilustrações e GIFs
audio/       narrações das animações
```

## Como abrir

Abra o `index.html` em um navegador. Para testar com as imagens e os áudios carregando como no site, rode um servidor local na pasta:

```
python3 -m http.server 8000
```

e acesse http://localhost:8000.

## Privacidade

O app não coleta dados pessoais. Os pontos, o progresso e a lista de remédios ficam salvos apenas no navegador do próprio aparelho.

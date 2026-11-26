# Sistema de Recomendação com a API Olho Vivo

Dadas uma coordenada de origem e uma de destino, o sistema recomenda uma linha de ônibus de São Paulo usando a API Olho Vivo (SPTrans).

## Estrutura

- `notebook.ipynb`: notebook final, já executado
- `mapa.html`: mapa interativo salvo à parte (o GitHub costuma não exibir mapas folium no notebook)
- `fluxograma.png`: fluxograma do algoritmo
- `.env`: token da API (não vai para o GitHub)

## Como executar

1. Instale as dependências: `pip install requests pandas folium python-dotenv`
2. Crie um arquivo `.env` na raiz com o token da SPTrans:
   ```
   SPTRANS_TOKEN=seu_token_aqui
   ```
3. Abra e execute o `notebook.ipynb` de ponta a ponta.

## Integrantes

- Membro 1: Victor Afonso
- Membro 2: Matheus Bonato
- Membro 3: Lucas Gabriel
- Membro 4: Athos Jasper

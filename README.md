# Análise de dados do Twitter dos Bombeiros de Joinville 

Repositório de código com as etapas necessárias para analisar os dados dos bombeiros de Joinville. Em breve explicação detalhada. 

## Resumo:
- Raspar todos os tweets utilizando o arquivo e salvar em CSV ([bombeiros-tweet-scrapper.ipynb](https://github.com/nuno-nunes/bombeiros-jlle/blob/master/bombeiros-tweet-scrapper.ipynb "bombeiros-tweet-scrapper.ipynb"))
- Tratar base de tweets para obter descrição, endereço, data e outros atributos com Regex. ([limpeza_db_bombeiros_regex.ipynb](https://github.com/nuno-nunes/bombeiros-jlle/blob/master/limpeza_db_bombeiros_regex.ipynb "limpeza_db_bombeiros_regex.ipynb"))
- Refinar as bases retirando espaços em branco e clusterizando as categorias com o Open Refine. ([bombeiros-openrefine-extract.txt](https://github.com/nuno-nunes/bombeiros-jlle/blob/master/bombeiros-openrefine-extract.txt "bombeiros-openrefine-extract.txt"))
- Preparar arquivos para importar na plataforma de visualização. Pode ser feito via tabela dinâminca em um editor de planilhas.
- Importar dados no [https://flourish.studio/](https://flourish.studio/)
- Criar mapas utilizando Folium e Google Colab ([mapa_bombeiros_folium.ipynb](https://github.com/nuno-nunes/bombeiros-jlle/blob/master/mapa_bombeiros_folium.ipynb "mapa_bombeiros_folium.ipynb"))
- Converter arquivos de mapas HTML para gif ([mapa-to-gif.ipynb](https://github.com/nuno-nunes/bombeiros-jlle/blob/master/mapa-to-gif.ipynb "mapa-to-gif.ipynb"))


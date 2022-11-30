# Contexto e objetivos
Para defender a escolha de tema (narrativas sexistas na música, entre a MPB e a atualidade) para o projeto de conclusão do bacahrelado em design perante os professores orientadores, foi necessária a coleta de dados para analisar a evolução da frequência das narrativas sexistas na música popular ao longo do tempo.
Foram coletados dados da lista [Top 50 BR](https://open.spotify.com/playlist/37i9dQZEVXbMXbN3EUUhlg) do Spotify por meio de webscraping com a biblioteca Beautiful Soup ao longo de algumas semanas, também foram coletados dados do artigo acadêmico ["Nem “umas” nem “outras”, todas... – a representação da mulher na MPB na década de 1970"](https://www.revistas.udesc.br/index.php/linhas/article/view/1243/0) de Susana Claudino Barbosa.
Os dados foram modelados e analisados separadamente para obter a frequência com que cada narrativa relacionada ao sexismo aparece na música de cada período.

<img src="https://raw.githubusercontent.com/maiarafsouza/TCC_data_scraping_and_viz/main/generated%20media/narrativas_freq_atual.png" width=50% height=50%><img src="https://raw.githubusercontent.com/maiarafsouza/TCC_data_scraping_and_viz/main/generated%20media/narrativas_freq_anos70.png" width=50% height=50%>

Em seguida os dados foram comparados para analisar as alterações na frequência da aparição de cada narrativa sexista entre os anos 70 e a atualidade.

<img src="https://raw.githubusercontent.com/maiarafsouza/TCC_data_scraping_and_viz/main/generated%20media/comparativo2.png" width=50% height=50%><img src="https://raw.githubusercontent.com/maiarafsouza/TCC_data_scraping_and_viz/main/generated%20media/comparativo_perc2.png" width=50% height=50%>

# Tecnologias
- Python
- BeautifulSoup
- Pandas
- Seaborn
- Excel

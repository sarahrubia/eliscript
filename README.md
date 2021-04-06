# Resumo

O autoarquivamento é o depósito da produção científica, realizado pelo autor do trabalho, em um repositório institucional ou temático de acesso aberto. Os repositórios temáticos armazenam e fornecem acesso à literatura de uma disciplina específica e seus assuntos correlatos. O presente estudo propõe uma metodologia automatizada para analisar o autoarquivamento na Biblioteconomia e Ciência da Informação, visando avaliar as contribuições do repositório Eprints in Library and Information Science (E-LIS) para a comunicação científica aberta na área. Para tanto, foi desenvolvido um instrumento em linguagem de programação Python, o ELIScript, que permitiu coletar e analisar a produção científica do repositório. Essa produção foi caracterizada baseando-se na tipologia dos documentos depositados, suas temáticas, data de publicação, data de depósito, idioma, periódicos científicos, eventos científicos e palavras-chave. A pesquisa configurou-se como aplicada, quantitativa, descritiva e exploratória. Com a criação do ELIScript, foi possível coletar os dados de todo o acervo do E-LIS. O universo da pesquisa constitui-se de 23.245 documentos, subdivididos entre a África (187 documentos); América, dividida em: a) América do Norte e Central (3.345); e b) América do Sul (4.125); Antártica (2); Ásia (2.169); Europa (13.253); e Oceania (164). Os resultados apontam que a produção científica do E-LIS foi depositada entre 2002 e 2020, e os documentos foram publicados entre 1965 e 2020. Cerca de 47% dos documentos depositados são artigos de periódicos. Os assuntos mais abordados nos documentos são “Uso da Informação e Sociologia da Informação”, “Tecnologia da Informação e Tecnologia de Biblioteca”, e “Tratamento da Informação para Serviços de Informação”. De forma mais específica, os documentos tratam sobre “Disseminação e difusão da informação”, “Repositórios (baseado ou não em acesso aberto)” e “Métodos bibliométricos”. O espanhol aparece como o idioma mais frequente das publicações, seguido do inglês, italiano, alemão e português. Os artigos publicados em periódicos e depositados no E-LIS estão indexados em bases de dados importantes da área, como a LISTA, LISA e a ISTA, e bases generalistas como Web of Science e a Scopus, alguns deles com alto fator de impacto. Verificou-se, ainda, a existência de documentos publicados ou apresentados em eventos científicos regionais, nacionais e internacionais. A partir dos dados, pode-se dizer que o E-LIS alcançou reconhecimento como uma comunidade internacional aberta de Biblioteconomia e Ciência da Informação. A criação de uma metodologia automatizada pode auxiliar no acompanhamento da produção científica depositada no E-LIS, sem que seja necessário recriar métodos para a coleta e análise de dados. Pesquisar sobre o autoarquivamento na Biblioteconomia e Ciência da Informação evidenciou a necessidade de incentivo dessa prática para preservação da memória da área, de forma que sirva como fonte de informação para trabalhos científicos e beneficie o exercício profissional de bibliotecários, arquivistas, museólogos e cientistas da informação. Ter artigos e outros documentos publicados em periódicos de acesso aberto não garante que esses trabalhos serão preservados ao longo do tempo. A melhor alternativa ainda é o depósito em repositórios digitais consoantes com o Movimento de Acesso Aberto.

# TL;DR

O ELIScript é um script para coleta e análise de dados do repositório digital EPrints in Library and Information Science (e-LIS http://eprints.rclis.org/). O trabalho foi desenvolvido no Programa de Pós-Graduação em Gestão e Organização do Conhecimento (PPGGOC) da Escola de Ciência da Informação (ECI) na Universidade Federal de Minas Gerais (UFMG).

# Responsáveis

Sarah Rúbia de Oliveira Santos - <sarahrubia@ufmg.br> 

Sob orientação da Profª. Drª. Dalgiza Andrade Oliveira.

# Dependências a serem instaladas para utilizar o e-LIS script

- selenium <br>
`pip install selenium`

- geckodriver <br>
Download em: https://github.com/mozilla/geckodriver/releases <br>
No linux, extrair e mover o arquivo para /usr/bin <br>
Abrir o terminal na pasta onde está o arquivo e utilizar o comando `sudo mv geckodriver /usr/bin`

- palettable (cores para o gráfico de idiomas) <br>
`pip install palettable`

- wordcloud (para a nuvem de palavras)<br>
`pip install wordcloud`


# Agradecimentos

O presente trabalho foi realizado com apoio da Coordenação de Aperfeiçoamento de Pessoal de Nível Superior – Brasil (CAPES) – Código de Financiamento 001.

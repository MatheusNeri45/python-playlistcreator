Descrição do Projeto

Nome do Projeto: DJ Playlist Creator

Descrição Geral:
O DJ Playlist Creator é uma aplicação Python projetada para facilitar a criação de playlists no YouTube com as melhores músicas de DJs populares. O usuário insere o nome de um ou mais DJs e a aplicação realiza uma busca no YouTube, filtra as músicas mais populares e cria uma playlist personalizada com esses vídeos. Essa aplicação é especialmente útil para fãs de música eletrônica, organizadores de eventos, e qualquer pessoa que queira montar uma playlist de alta qualidade rapidamente.

Objetivo do Projeto:
O objetivo principal do DJ Playlist Creator é automatizar o processo de busca e curadoria de músicas de DJs no YouTube, simplificando a criação de playlists e proporcionando uma experiência musical mais organizada e agradável.

Funcionalidades Principais:

    Busca Avançada no YouTube:
        Realiza buscas detalhadas no YouTube com base no nome dos DJs fornecidos.
        Filtra os resultados para encontrar as músicas mais populares e relevantes.

    Criação de Playlists no YouTube:
        Utiliza a API do YouTube para criar uma nova playlist no canal do usuário.
        Adiciona automaticamente as músicas encontradas à playlist criada.

    Interface de Usuário:
        Simples e intuitiva, permitindo a inserção dos nomes dos DJs e a criação da playlist com poucos cliques.

    Autenticação com OAuth 2.0:
        Implementa autenticação segura para que os usuários possam criar playlists diretamente em seus próprios canais do YouTube.

Tecnologias Utilizadas:

    Linguagem de Programação: Python
    APIs: YouTube Data API v3
    Bibliotecas: google-api-python-client, OAuth 2.0
    Ferramentas de Desenvolvimento: Visual Studio Code, Git, Poetry

Como Funciona:

    Entrada do Usuário:
        O usuário insere o nome de um ou mais DJs na interface do aplicativo.

    Busca e Filtragem:
        A aplicação utiliza a YouTube Data API para buscar vídeos relacionados aos DJs.
        Filtra os vídeos para selecionar as músicas mais populares, baseando-se em critérios como número de visualizações e relevância.

    Criação da Playlist:
        A aplicação autentica o usuário com OAuth 2.0 e cria uma nova playlist no canal do YouTube do usuário.
        Adiciona as músicas filtradas à playlist recém-criada.

    Resultado Final:
        O usuário recebe um link para a playlist no YouTube, pronta para ser ouvida e compartilhada.

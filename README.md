# WebScrap
 Web Scraping com Python.
Neste código, faço a captura de informação do portal de notícias G1 para obter informação previsão do tempo. Peço entradas de usuário para que ele defina o nome da cidade e UF do estado.Formato a string substituindo os espaços por hífens, para que a variável de URL receba as entradas e monte o link no padrão do G1.

Utilizo a biblioteca Selenium para capturar o elemento* que contém as informações necessárias e as converto em texto para a tela do usuário.

*Utilizei o elemento "xpath". Não é aconselhável por possível mudança na estrutura do site. Mas serviu para o exemplo.


Lembrando: 
pip install: selenium e time.

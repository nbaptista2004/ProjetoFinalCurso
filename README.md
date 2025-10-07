Este projeto é um portal de notícias desenvolvido na plataforma OutSystems, criado para facilitar a comunicação e a divulgação de conteúdos informativos. Foi utilizada a opção gratuita da OutSystems.

A plataforma digital permite o acesso a notícias, a gestão de publicações e a interação entre diferentes tipos de utilizadores, desde visitantes até administradores, garantindo um fluxo editorial controlado e eficiente.

Principais Funcionalidades:
  - Consulta de notícias por todos os visitantes.
  - Registo e autenticação de utilizadores.
  - Submissão e edição de notícias por jornalistas.
  - Aprovação e publicação de conteúdos por administradores.
  - Gestão de utilizadores e funções.
  - Personalização de idioma e preferências do utilizador.
  - Visualização de páginas institucionais: contactos, termos de utilização, estatuto editorial e ficha técnica.

Perfis de Utilizador e Credenciais de Acesso:

  Administrador: 
  
    Nome de Utilizador: 
    admin
    
    Palavra-passe: 
    admin1234
    
    Publica, edita e aprova notícias. Gere utilizadores e respetivas funções.

  Jornalista:
  
    Nome de Utilizador: 
    jornalista1
    
    Palavra-passe: 
    jornalista1
    
    Redige, edita e submete notícias para aprovação. Pode gerir apenas os seus próprios conteúdos.

  Utilizador Registado:			
  
    Nome de Utilizador: 
    user1
    
    Palavra-passe: 
    user1234
    
    Consulta notícias, configura preferências e acede a informações gerais.

  Utilizador Não Registado:			
  
    Nome de Utilizador: 
    —
    
    Palavra-passe: 
    —
    
    Consulta notícias publicadas, cria conta de utilizador e acede a informações gerais sobre a aplicação.

Diagrama de Contexto:
  - Utilizador Não Registado
    Interage diretamente com a aplicação, acedendo à mesma para:
    Consultar notícias publicadas;
    Criar uma conta de utilizador;
    Configurar o idioma;
    Visualizar os contactos, os termos de utilização, o Estatuto Editorial e a Ficha Técnica.

  - Utilizador Registado
    Interage diretamente com a aplicação, acedendo à mesma para:
    Consultar notícias publicadas;
    Editar dados pessoais;
    Configurar o idioma;
    Visualizar contactos, termos de utilização, Estatuto Editorial e Ficha Técnica;
    Poderá ser promovido a Jornalista ou Administrador, caso um dos administradores o atribua.

  - A aplicação responde às atividades realizadas por cada utilizador (como editar dados pessoais) e processa internamente as ações de acordo com os requisitos definidos.

  - Jornalista
    Interage diretamente com a aplicação para:
    Redigir, editar e submeter notícias para aprovação;
    Gerir os conteúdos associados à sua autoria;
    A publicação das notícias depende da aprovação de um Administrador.

  - Administrador
    Interage diretamente com a aplicação para:
    Publicar, editar e aprovar notícias submetidas pelos jornalistas;
    Gerir utilizadores (atribuir ou remover funções, editar dados e gerir permissões).

Objetivo:

  A plataforma digital Canal Albicastrense tem como objetivo oferecer uma plataforma digital moderna e funcional para a publicação e gestão de notícias locais, promovendo a comunicação e o acesso à informação por parte da comunidade.

Tecnologias Utilizadas:

OutSystems Platform

OutSystems Service Studio

Base de Dados OutSystems (integrado)

HTML / CSS / JavaScript (gerados automaticamente pela plataforma)

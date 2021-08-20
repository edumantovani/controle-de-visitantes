# Home
O repositório controle-visitantes é destinado a armazenar o código referente ao projeto desenvolvido durante o curso [Django framework na prática] do Thiago Brasil na plataforma Udemy.

O objetivo do curso é explorar as principais funcionalidades do framework Django por meio da construção de uma dashboard para registro e administração de visitantes de um determinado condomínio. Vamos desenvolver um projeto real e aprender ao longo de seu desenvolvimento o que são as ferramentas que o framework nos dá e como utilizá-las.

# Conhecendo o processo
O projeto controle de visitantes tem o objetivo informatizar o processo de registro e administração de visitantes do condomínio Montanhas Azuis.

# Processo de registro de visitantes.

Deploy da Aplicação com Git Pages: ACESSE AQUI
Status: Finalizado ✅

<p align="center">
  Projeto desenvolvido em Django Python.
</p>

<h4 align="center">
  Status: Finalizado :white_check_mark:
</h4>

<p align="center">
  <img src="img/NETFLIX_CLONE.gif" alt="" width="600px" height="300px">
</p>

Principais funcionalidades
Registro de visitantes
O formulário de registro de visitantes deve abstrair a etapa 01 do processo, onde o visitante informa nome completo, CPF, data de nascimento, o número da casa que deseja visitar e ainda a placa do veículo, se estiver utilizando durante a visita. Além desta informações, o formulário salva o horário de chegada do visitante automaticamente.

Listagem de visitantes
A listagem de visitantes exibe, por meio de uma tabela, os visitantes recentes classificados por horário de chegada, do mais recente para o mais antigo.

Widgets para resumo de informações
O widgets da página inicial da dashboard têm a função de exibir um resumo dos números referentes aos visitantes em cada status e ainda o número total de visitantes registrados no mês.

Visualização de informações de visitante
A partir da tabela que lista os visitantes recentes, é possível acessar a página que exibe as informações detalhadas de cada visitante. No exemplo abaixo um visitante com a visita já finalizada:

Autorização de entrada
A tela de informações de vistante é importante pois a partir dela é possível utilizar as funcionalidades de autorização de entrada e finalização de visita.

Finalização de visita
Assim como conseguimos utilizar a funcionalidade para autorizar a entrada do visitante, podemos finalizar sua visita. A funcionalidade funciona de forma parecida, com a diferença que é necessário apenas confirmar a ação, sem necessidade de informações adicionais.

Ao clicar no botão para finalizar uma visita, um alerta é exibido solicitando que o porteiro confirme a ação.

Tecnologias utilizadas
Django framework
Django widget tweaks
Start Bootstrap - SB Admin 2
Instalação
pip install virtualenv

virtualenv env

.\env\Scripts\activate.bat

pip install Django

django-admin startproject controle_estoque

python manage.py startapp usuario

python manage.py runserver iniciar a aplicação

python manage.py startapp porteiros

python manage.py makemigrations porteiros

pip3 install django-widget-tweaks

python manage.py migrate

python manage.py runserver

# Seleção CGM – Desafio PHP

Desafio para seleção para o cargo de Gestor de Unidade de Apoio ao Portal da Transparência.

Este desafio consiste no desenvolvimento de um protótipo de sistema web em PHP.

## Cenário

Uma imobiliária solicitou o desenvolvimento de um sistema de publicação de anúncios dos imóveis à venda. Você foi alocado para desenvolver um protótipo com as funcionalidades básicas iniciais do sistema. 

Nesta versão do sistema, será desenvolvido apenas o módulo onde o administrador irá gerenciar corretores, imóveis e anúncios. **Não está no escopo desta versão** uma página onde o público em geral visualizará os anúncios.

## Requisitos

Neste sistema os anúncios serão criados pelo administrador do sistema. Não há necessidade de desenvolver telas para acesso pelos donos dos imóveis nem pelos corretores.

Um anúncio consiste basicamente em associar um imóvel a um corretor. 
Só haverá um anúncio por imóvel. Cada anúncio de imóvel será associado a apenas um corretor. Um corretor pode estar associado a vários anúncios.

Não é necessário desenvolver tela para login / autenticação.

Na tela de gerenciamento de anúncios, o administrador poderá pesquisar os anúncios pelo nome do corretor responsável ou pelo bairro do imóvel **(o bairro é um campo textual, não é necessário criar uma tabela de bairros)**. 

## CRUD de Imóveis

Criar um gerenciamento aonde seja possível Criar, Listar, Editar e Visualizar imóveis.

**Atributos do imóvel**

Tipo – Texto - obrigatório **(Valores permitidos: apenas “CASA” e “APARTAMENTO”)**

Bairro – Texto – obrigatório

Descrição – Texto – obrigatório (campo textual para descrever os detalhes do imóvel)

## CRUD de Corretores

Criar um gerenciamento aonde seja possível Criar, Listar, Editar e Visualizar corretores.

**Atributos do corretor**

Nome – Texto - obrigatório

Email – Texto – obrigatório

Telefone – Texto – obrigatório

## CRUD  de anúncios

Criar um gerenciamento aonde seja possível Criar, Listar, Editar e Visualizar anúncios.

## Observações

#### Você deverá incluir um arquivo com as instruções para rodar o seu projeto

#### Serão avaliadas boas práticas de orientação a objetos e organização de código

## Branches

#### Cada participante deverá clonar a branch com seu nome, e submeter o código desenvolvido até o fim do prazo do teste

git clone -b lucas_cruz git@github.com:CaioSobreira/cgm_desafio_php.git

git clone -b william_silva git@github.com:CaioSobreira/cgm_desafio_php.git

git clone -b gilson_silva git@github.com:CaioSobreira/cgm_desafio_php.git

git clone -b cesar_muniz git@github.com:CaioSobreira/cgm_desafio_php.git

git clone -b rafael_lima git@github.com:CaioSobreira/cgm_desafio_php.git

git clone -b sandro_anconetani git@github.com:CaioSobreira/cgm_desafio_php.git

git clone -b elemer_janovitz git@github.com:CaioSobreira/cgm_desafio_php.git

git clone -b vitor_santos git@github.com:CaioSobreira/cgm_desafio_php.git

git clone -b ariston_cordeiro git@github.com:CaioSobreira/cgm_desafio_php.git

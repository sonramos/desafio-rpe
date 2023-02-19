# desafio-rpe

<h2 align="center">Repositório - desafio técnico RPE</h2>

Para testes e desenvolvimento da estrutura do banco e dos 2 primeiros tópicos do desafio foi utilizado um container docker com as imagens de banco POSTGRES e pgAdmin, nos primeiros estágios e MySql e Adminer, a partir do tópico 2.C.

O arquivo docker-compose.yml pode ser encontrado no diretório ./containers. Para utilizar a estrutura, navegar até o diretório e executar o comando:
  docker compose up

# A modelagem E-R pode ser encontrada no diretório ./modelagem-er. Constam de 2 imagens (.png) com os modelos conceitual e lógico.

# Os Scripts seguem dois padrões: SQL-ANSI (scripts-sql) e Oracle-SQL (scripts-oracle). Ambos estão na raíz do repositório.
# Diferenças entre os dois padrões:
=================
<!--ts-->
   * CONSTRAINTS: Adaptadas para o padrão Oracle em scripts-oracle.
   * INSERT - formato de DATE: Padrão oracle em scripts-oracle.
   * CONSULTAS - sem distinção.
   * Anonymous blocks - sem distinção.
<!--te-->

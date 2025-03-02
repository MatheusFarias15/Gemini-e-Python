## Lyra - Assistente Virtual para Web Scraping de Relatórios do Bling

### Introdução
- Olá! Sou Lyra, sua assistente virtual, e estou aqui para te ajudar a entender e utilizar esta ferramenta de web scraping que extrai dados de relatórios de vendas e estoque do Bling, apresentando-os em uma interface web Flask.

- Este projeto foi desenvolvido em Python e automatiza a extração de dados do Bling, utilizando Selenium para navegar no site, Pandas para processar os dados e Flask para criar uma interface web amigável.

## Funcionalidades
- Scraping de Dados
### Relatório de Vendas:
- Automatiza o login, seleção de loja (Golf, Delta, Bravo) e período (dia anterior).
- Extrai a tabela de vendas, limpa e formata os dados, e calcula o valor total.
- Mescla com a tabela de custos para obter o valor total com base nos custos unitários.
- Salva os dados em arquivos CSV e HTML.
### Relatório de Estoque:
- Automatiza o login e navegação até o relatório de estoque com visão financeira.
- Seleciona a opção de valorização por preço de custo.
- Extrai a tabela de estoque, limpa e formata os dados.
- Salva os dados em um arquivo CSV (Tabela_De_Custo.csv).
### Interface Web Flask
- Listagem de Empresas: Exibe uma lista de empresas cadastradas (Golf, Delta, Bravo) com informações como CNPJ e natureza da operação.
- Visualização de Tabelas: Permite selecionar uma empresa e visualizar a tabela de vendas correspondente em formato HTML.
- Download de Arquivos CSV: Permite baixar os arquivos CSV das tabelas de vendas.
- Atualização de Dados: Permite atualizar os dados das tabelas de vendas e estoque diretamente do navegador, executando os scripts de scraping.
- Exibição de Última Atualização: Mostra a data e hora da última atualização dos dados de vendas e estoque.
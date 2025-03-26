# XML-em-EXCEL

Este script Python foi desenvolvido para ler arquivos XML de Notas Fiscais Eletrônicas (NF-e), extrair informações relevantes (como número da nota, dados da empresa emissora, dados do cliente, e peso da mercadoria) e gerar uma tabela Excel com essas informações. O código utiliza as bibliotecas xmltodict para fazer o parse dos arquivos XML e pandas para manipular e salvar os dados em formato de planilha.

Funcionalidades:

Leitura de arquivos XML de Notas Fiscais Eletrônicas.

Extração das informações de cada nota, como número da nota, empresa emissora, CNPJ, nome do cliente, endereço e peso da mercadoria.

Geração de uma planilha Excel (tabela_nf.xlsx) com as informações extraídas.

Pré-requisitos:

Python 3.x

Bibliotecas: xmltodict, pandas

Como usar:

Coloque os arquivos XML de Notas Fiscais Eletrônicas na pasta nfs/.

Execute o script.

O script irá gerar um arquivo Excel chamado tabela_nf.xlsx com as informações extraídas dos XMLs.

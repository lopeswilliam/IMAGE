# FLUXO DE LEITURA DE ARQUIVO
Leitura de arquivo.

1 - Componente verifica o arquivo, se existir, lê as informações e insere na base. 

2 - Componente verifica as informações na base, com base na data do dia.
    Identifica o codigo do cliente, busca a informação , atualiza a base, para cada registro encontrado.
    
3 - Componente faz a leitura da base, monta o arquivo. d- 1
    Posta em um topic kakfa, ou qualquer um de utilidade.
    
4 - Componente consome arquivo e segue o fluxo.

if you talk about anything, dont worry. Im here!!! :)

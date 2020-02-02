# Dealbook_Capture_Deals
Capture deals data from Dealbook site.

1 Acessar o site http://dealbook.co
2 Clicar em "Deals" (http://dealbook.co/deals)
3 Para cada linha da tabela, para todas as páginas do rodapé, clicar no link da coluna "Deal Type"
4 Serão gerados dois arquivos de saída.
  1 O primeiro arquivo terá os seguintes campos:
    1 Close Date
    2 Company Name
    3 Company URL
    4 Investors (somente os nomes)
    5 Round
    6 Amount
    7 Pre-money valuation
    8 Source URL
    9 Verified/unverified
    10 Data da Captura
    11 Deal URL
  2 O segundo arquivo terá os seguintes campos:
    1 Deal URL
    2 Data da Captura
    3 Para cada Investor, capturar:
      1 Investor (nome do investidor)
      2 Investor URL
      ***Obs.: os campos 1 e 2 deversão ser repetidos para cada ocorrência dos campos 3.1 e 3.2***

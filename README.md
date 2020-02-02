# Dealbook_Capture_Deals
Capture deals data from Dealbook site.

- Acessar o site http://dealbook.co
- Clicar em "Deals" (http://dealbook.co/deals)
- Para cada linha da tabela, para todas as páginas do rodapé, clicar no link da coluna "Deal Type"
- Serão gerados dois arquivos de saída.
- O primeiro arquivo terá os seguintes campos:
 1. Close Date
 2. Company Name
 3. Company URL
 4. Investors (somente os nomes)
 5. Round
 6. Amount
 7. Pre-money valuation
 8. Source URL
 9. Verified/unverified
 10. Data da Captura
 11. Deal URL
- O segundo arquivo terá os seguintes campos:
 1. Deal URL
 2. Data da Captura
 3. Para cada Investor, captura:
     1. Investor (nome do investidor)
     2. Investor URL
***Obs.: os campos 1 e 2 deverão ser repetidos para cada ocorrência dos campos 3.i e 3.ii***

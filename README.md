# Metodologia da reportagem: "Raio-x de quem é dono da água: 50 empresas podem usar a mesma quantidade que metade do Brasil"

1. Foram baixados os dados [disponibilizados pela ANA](https://www.gov.br/ana/pt-br/assuntos/regulacao-e-fiscalizacao/outorga/outorgas-emitidas) (“planilha de outorgas”) em 15/08/2023. O arquivo pode ser visto [aqui](https://github.com/apublica/donosdaagua/blob/main/relatorio_outorgas.csv)
2. Foram excluídas as colunas que versam sobre vazão diária e correlatos;
3. Foram excluídas as outorgas sem nome do requerente, sem volume anual, com data de vencimento anterior à 15/08/2023 e nas categorias revogação, suspensão, cancelamento/anulação.
4. Foi adicionada a coluna “volume anual em litros”, convertendo os dados de volume anual de metros cúbicos;
5. Foram excluídas outorgas duplicadas (outorgas em que o mesmo volume de água era concedido na mesma data e nas mesmas coordenadas);
6. Foram excluídas as outorgas que tinham como finalidade “obras hidráulicas”, “criação animal”, “consumo humano”, “esgotamento sanitário” e “abastecimento público”;
7. Foram consideradas as outorgas de “irrigação”, “indústria”, “mineração - extraçção de areaia/cascalho em leito de rio”, “mineração - outros processos extrativos”, “termoelétrica”, “aquicultura” e “outros”;
8. Foram consideradas outorgas de captação e desconsideradas as de lançamento;
9. Foram consideradas tanto as outorgas de direito de uso quanto as preventivas;
10. A partir desse recorte, foi utilizada tabela dinâmica para agrupar as outorgas por requerente, considerando o CPF/CNPJ;
11. Em seguida, foram agrupadas outorgas de pessoas físicas e/ou pessoas jurídicadas que fazem parte do mesmo grupo empresarial ou da mesma família, a partir de busca em diferentes fontes de pesquisa.

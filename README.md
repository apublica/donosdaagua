# Metodologia da reportagem: "Os donos da água: 50 empresas podem usar mesma quantidade que metade do Brasil"

## Download e importação dos dados
*  Foram baixados os dados [disponibilizados pela ANA](https://www.gov.br/ana/pt-br/assuntos/regulacao-e-fiscalizacao/outorga/outorgas-emitidas) (“planilha de outorgas”) em 15/08/2023. O arquivo pode ser visto [aqui](https://github.com/apublica/donosdaagua/blob/main/relatorio_outorgas.csv)
*  Fizemos o upload do arquivo no Google Sheets para análise posterior.

## Limpeza dos dados
* Para montar o ranking apresentado na reportagem, foram selecionadas as outorgas de captação de recursos hídricos, tanto de direito de uso quanto as preventivas (que reservam água para grandes projetos em fase de planejamento). Não foram incluídas as outorgas de lançamento (que tratam dos efluentes que serão lançados em corpos hídricos), nem aquelas que tinham como finalidade o abastecimento público, esgotamento sanitário, consumo humano, criação animal, obras hidráulicas ou sem finalidade definida. Além disso, foram excluídos os órgãos públicos, os distritos de irrigação e demais projetos de irrigação para pequenos agricultores, incluindo os promovidos por empresas privadas.
* Foram excluídas as colunas que versam sobre vazão diária e correlatos.
* Foram excluídas as outorgas sem nome do requerente, sem volume anual, com data de vencimento anterior a 15/08/2023 e nas categorias revogação, suspensão, cancelamento/anulação.
* Foi adicionada a coluna “volume anual em litros”.
* Foram excluídas outorgas duplicadas (outorgas em que o mesmo volume de água era concedido na mesma data e nas mesmas coordenadas)
* Foram excluídas as outorgas que tinham como finalidade “obras hidráulicas”, “criação animal”, “consumo humano”, “esgotamento sanitário” e “abastecimento público”. Foram consideradas as outorgas de “irrigação”, “indústria”, “mineração - extração de areia/cascalho em leito de rio”, “mineração - outros processos extrativos”, “termoelétrica”, “aquicultura” e “outros”
* Foram consideradas outorgas de captação e desconsideradas as de lançamento
* Foram consideradas tanto as outorgas de direito de uso quanto as preventivas

## Análise
* A partir desse recorte, foi utilizada tabela dinâmica do Google Sheets para formular um ranking dos 50 outorgados que mais têm outorgas de água em volume, considerando o CPF/CNPJ. Em seguida, foram agrupadas outorgas de pessoas físicas e/ou pessoas jurídicas que fazem parte do mesmo grupo empresarial ou da mesma família, a partir de busca em diferentes fontes de pesquisa.
* O cálculo de quantas pessoas poderiam ser abastecidas com o volume das outorgas considerou o consumo médio de 152,1 litros por dia por pessoa, que foi estimado pelo Sistema Nacional de Informações sobre Saneamento (SNIS) em 2021.


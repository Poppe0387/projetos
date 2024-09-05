# Análise de Salários de Cientistas de Dados em 2024

O principal objetivo deste projeto é analisar o conjunto de dados fornecido para extrair insights valiosos sobre os salários de cientistas de dados. A análise inclui uma comparação com outras áreas dentro do setor de tecnologia, considerando diferentes variáveis como o nível de experiência, tipo de emprego, localização e outras métricas relevantes. A meta é identificar padrões e tendências que possam ser úteis para empregadores, profissionais e outros interessados no mercado de trabalho de ciência de dados.

## Fonte de Dados
Para este projeto, utilizamos o arquivo de dados salaries.csv, que contém informações detalhadas sobre os salários de cientistas de dados e outras profissões relacionadas ao setor de tecnologia para o ano de 2024. [Site da base de dados](https://aijobs.net/salaries/download/)

## Objetivo do Projeto
O principal objetivo deste projeto é analisar o conjunto de dados fornecido para extrair insights valiosos sobre os salários de cientistas de dados. A análise inclui uma comparação com outras áreas dentro do setor de tecnologia, considerando diferentes variáveis como o nível de experiência, tipo de emprego, localização e outras métricas relevantes. A meta é identificar padrões e tendências que possam ser úteis para empregadores, profissionais e outros interessados no mercado de trabalho de ciência de dados.

## Ferramentas Utilizadas
Para realizar as análises, utilizamos a linguagem de programação Python, amplamente reconhecida por suas bibliotecas poderosas e versatilidade em manipulação e visualização de dados. Python é uma escolha ideal para análises exploratórias e para a preparação de dados para modelos de aprendizado de máquina.

## Descrição dos Dados
O conjunto de dados contém as seguintes colunas, com suas respectivas descrições:

| Coluna                     | Descrição                                                                                                                                                      |
|----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **ano_de_trabalho**            | O ano em que o salário foi pago.                                                                                                                               |
| **nivel_experiencia**          | O nível de experiência no trabalho durante o ano: Júnior (EN), Intermediário (MI), Sênior (SE) e Diretor (EX).                                                                                                              |
| **tipo_emprego**               | O tipo de emprego para a função: Tempo parcial (PT), Tempo total (FT), Contrato (TC) e Freelance (FL).                                                                                                                              |
| **cargo**                      | A função exercida durante o ano.                                                                                                                           |
| **salario**                    | O valor total do salário bruto pago.                                                                                                                           |
| **salario_moeda**              | A moeda do salário pago, usando o código de moeda ISO 4217.                                                                                                         |
| **salario_em_usd**             | O salário convertido para USD (utilizando a taxa de câmbio média do respectivo ano), baseado em dados estatísticos do BIS e dos bancos centrais.                |
| **residencia_do_funcionario**  | País de residência principal do funcionário durante o ano de trabalho, como um código de país ISO 3166.                                                         |
| **proporcional_remoto**        | A proporção total de trabalho realizado remotamente.                                                                                                              |
| **localizacao_empresa**        | O país da sede do empregador ou da filial contratante, como um código de país ISO 3166.                                                                             |
| **tamanho_empresa**            | O número médio de funcionários que trabalharam para a empresa durante o ano.                                                                                         |

## Metodologia
A metodologia para este projeto segue os seguintes passos principais:

1. Planejamento: Definir o escopo da análise e os resultados desejados, garantindo que as perguntas de negócios sejam respondidas de maneira eficaz.

2. Exploração e Preparação de Dados: Utilização de técnicas de Análise Exploratória de Dados (EDA) para entender melhor as características dos dados, identificar valores ausentes e detectar possíveis outliers ou eventos anômalos. Esta etapa envolve a utilização de gráficos e estatísticas descritivas para resumir e visualizar as variáveis.

3. Análise Detalhada: Realização de análises comparativas entre diferentes variáveis, como níveis de experiência e tipos de emprego, para identificar tendências salariais e padrões de mercado.

4. Visualização de Dados: Criação de visualizações interativas e informativas para comunicar os insights encontrados de maneira clara e concisa aos usuários de negócios e outros stakeholders.

## Conclusões:

Os insights revelam um panorama detalhado sobre a estrutura salarial de Data Scientists em 2024:

1. **Salário Médio**: O salário médio é de $164 mil.
2. **Valorização do cargo 'Junior'**: AI Data Scientist e AI Software Engineer são os que mais valorizam os iniciantes da área em comparação com as demais profissões.
3. **Comparação por Tipo de Trabalho**: Não existe diferença significativa entre o salário do trabalho presencial e do remoto, porém, há uma redução no salário do tipo híbrido.
4. **Profissões Mais Comuns**: Data Scientist é a mais frequente entre as 5 profissões principais (Data Engineer, Software Engineer, Data Analyst, Machine Learning Engineer).
5. **Diferença Salarial Significativa**: A diferença entre Data Scientist e Data Architect ultrapassa $600 mil, e entre Data Scientist e Software Engineer supera $100 mil.

### Análises Específicas

1. **Segmentação com K-Means**: Profissionais foram agrupados em clusters com base em características salariais, revelando perfis de mercado diferenciados.
2. **Regressão Linear**: Experiência e localização são os principais fatores que influenciam o salário, com previsões precisas para diferentes combinações de atributos.
3. **Distribuição Salarial**: Diretores ganham quase o dobro dos juniors, refletindo a alta valorização da experiência.
4. **Comparação de Profissões**: Data Scientists, especialmente em posições seniores, estão entre os mais bem pagos do setor.
5. **Impacto do Trabalho Remoto**: Salários de trabalho remoto são competitivos com os presenciais, refletindo a valorização crescente desse formato.
6. **Evolução Salarial**: A tendência de crescimento salarial indica uma demanda crescente por cientistas de dados.

### Conclusão Final

Essas análises oferecem uma visão abrangente das variações salariais em 2024, auxiliando tanto profissionais quanto empresas na tomada de decisões estratégicas sobre carreira e remuneração.




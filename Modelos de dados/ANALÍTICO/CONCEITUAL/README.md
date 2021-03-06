# Desafio-Final-Modulo-1

Objetivos
Exercitar os seguintes conceitos trabalhados no Módulo:
✓ Arquiteturas de Dados em Nuvem;
✓ Implementação de Data Lake em solução Cloud de Storage;
✓ Implementação de Processamento de Big Data;
✓ Esteiras de Deploy, utilizando o Github;
✓ IaC com Terraform.
Enunciado
Você é Engenheiro(a) de Dados de uma Startup da área de Educação. A Startup está expandindo seu negócio para outras áreas do Brasil. A principal fonte de dados para entender o cenário atual da educação básica e do ensino médio no Brasil é o Censo Escolar, uma base de dados desafiadora!
Você deve fazer a ingestão do Censo Escolar 2020 em uma estrutura de Data Lake na AWS (ou em outro provedor de sua escolha). Depois disso, você deve utilizar alguma tecnologia de Big Data para converter os dados para o formato parquet. Em seguida, disponibilize os dados para consulta no AWS Athena (ou outra engine de Data Lake de outra nuvem ou no BigQuery, no caso do Google Cloud) e faça uma consulta para demonstrar a disponibilidade dos dados. Por fim, utilize a ferramenta de Big Data ou a engine de Data Lake para realizar investigações nos dados e responder às perguntas do desafio.
Atenção! Toda a infraestrutura em nuvem deve ser implantada utilizando o Terraform (ou outra solução de IaC de sua escolha) e esteiras de deploy no Github (ou Gitlab, ou Bitbucket, ou outro de sua escolha). O dado que vamos trabalhar no desafio é grande. Evite fazer consultas desnecessárias.
DIVIRTA-SE!
Atividades
Os alunos deverão desempenhar as seguintes atividades:
1. Realizar a ingestão dos dados do Censo Escolar 2020 no AWS S3 ou outro storage de nuvem de sua escolha. Dados disponíveis em: https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/censo-escolar. O método de ingestão é livre. Os dados devem ser ingeridos na zona raw ou zona crua ou zona bronze do seu Data Lake.
2. Utilizar alguma tecnologia de Big Data para transformar os dados no formato parquet e escrevê-los na zona staging ou zona silver do seu Data Lake.
3. Fazer a integração com alguma engine de Data Lake. No caso da AWS, você deve:
a. Configurar um Crawler para a pasta onde os arquivos na staging estão depositados;
b. Validar a disponibilização no Athena.
4. Caso deseje utilizar o Google, disponibilize os dados para consulta usando o Big Query. Caso utilize outra nuvem, a escolha da engine de Data Lake é livre.
5. Use a ferramenta de Big Data ou a engine de Data Lake (ou o BigQuery, se escolher trabalhar com Google Cloud) para investigar os dados e responder às perguntas do desafio.
6. Quando o desenho da arquitetura estiver pronto, crie um repositório no Github (ou Gitlab, ou Bitbucket, ou outro de sua escolha) e coloque o código IaC para a implantação da infraestrutura. Nenhum recurso deve ser implantado manualmente.




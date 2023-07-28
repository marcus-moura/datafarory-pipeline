# Projeto de Estudo sobre Azure Data Factory

Este é um projeto de estudo sobre como utilizar o Azure Data Factory para orquestrar fluxos de dados entre diferentes fontes e destinos no Azure, incluindo Azure SQL Database e Azure Data Lake Gen2. O projeto contém código e configurações necessárias para criar pipelines de dados eficientes usando os componentes do Azure Data Factory, Linked Service e Datasets.

## Descrição do Projeto
O objetivo deste projeto é permitir que você compreenda como o Azure Data Factory funciona e como criar pipelines para mover e transformar dados entre fontes e destinos no ecossistema do Azure. Neste projeto, estaremos trabalhando com três principais componentes:

1. Azure Data Factory (ADF): É um serviço de orquestração de dados na nuvem que permite criar, agendar e gerenciar fluxos de trabalho de dados. Utilizaremos o ADF para definir nossos pipelines, atividades e fluxos de controle.

2. Linked Service: Representa uma conexão configurada para uma fonte ou destino de dados específicos. Neste projeto, configuraremos Linked Services para Azure SQL Database e Azure Data Lake Gen2, permitindo que o ADF se conecte a esses serviços.

3. Datasets: Representam conjuntos de dados que servem como entradas ou saídas para as atividades do pipeline. Os Datasets definem a estrutura dos dados, a localização e a forma como os dados serão acessados. Vamos criar Datasets para Azure SQL Database e Azure Data Lake Gen2.

## Pré-requisitos
Antes de começar a trabalhar com este projeto, certifique-se de ter o seguinte:

1. Conta do Azure: Você precisa ter uma conta ativa do Microsoft Azure para criar e configurar os recursos necessários.

2. Azure Data Factory: Crie uma instância do Azure Data Factory no portal do Azure para poder definir e executar os pipelines de dados.

3. Azure SQL Database: Provisione um banco de dados no Azure SQL Database para servir como um dos destinos de dados no nosso pipeline.

4. Azure Data Lake Gen2: Crie um Data Lake Gen2 no Azure para servir como outro destino de dados no pipeline.

### Avisos
Este projeto é apenas para fins de estudo e aprendizado.

### Recursos Adicionais
[Documentação do Azure Data Factory](https://learn.microsoft.com/en-us/azure/data-factory/)

[Documentação do Azure SQL Database](https://learn.microsoft.com/en-us/azure/azure-sql/?view=azuresql-vm)

[Documentação do Azure Data Lake Gen2](https://learn.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-introduction)

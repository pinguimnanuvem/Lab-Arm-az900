Introdução

Este relatório descreve o processo de aprendizado e prática de gerenciamento e otimização de recursos de armazenamento na nuvem utilizando o Microsoft Azure. O objetivo foi explorar as diferentes opções de armazenamento oferecidas pelo Azure, entender suas características e configurá-las especificamente para atender a diversas necessidades de armazenamento e recuperação de dados.

1. Acesso ao Portal do Azure

Iniciei o processo acessando o Portal do Azure , que é o ponto central para gerenciar todos os serviços e recursos no Azure. A navegação pelo portal permitiu acesso às opções de armazenamento e suas respectivas configurações.

Imprimir Fictício: Tela Inicial do Portal Azure

2. Tipos de Armazenamento no Azure

O Azure oferece várias soluções de armazenamento, cada uma adequada para diferentes cenários e necessidades. As principais opções incluem:

Contas de Armazenamento : Fornece acesso a vários serviços de armazenamento, como blobs, arquivos, filas e tabelas.
Armazenamento de Blobs do Azure : armazenamento de objetos para dados não estruturados.
Arquivos do Azure : Compartilhamento de arquivos na nuvem acessível via SMB.
Azure Table Storage : Armazenamento NoSQL para dados estruturados.
Azure Disk Storage : Discos gerenciados para máquinas virtuais.
Imprimir Ficção: Tipos de Armazenamento no Azure

3. Configuração de Contas de Armazenamento

3.1. Criação de uma Conta de Armazenamento

Para criar uma conta de armazenamento:

Acesse "Contas de Armazenamento" no Portal do Azure e selecione "Criar".
Preencha os detalhes necessários, como o nome da conta, região, e tipo de redundância (Locais, Geo-replicado, etc.).
Escolha o tipo de conta (General Purpose v2 é o mais versátil) e clique em "Revisar + Criar".
Imprimir Ficção: Configuração da Conta de Armazenamento

3.2. Armazenamento de Blobs

Após criar a conta, explore o Blob Storage para armazenar grandes quantidades de dados não estruturados.

Navegue até a conta de armazenamento e selecione "Blobs".
Crie um novo contêiner e faça o upload de arquivos.
Imprimir Ficção: Armazenamento de Blobs

3.3. Armazenamento de Arquivos

Para usar o Azure Files :

Na conta de armazenamento, selecione "Arquivos" e crie um novo compartilhamento de arquivos.
Defina o nome do compartilhamento e o tamanho máximo permitido.
Imprimir Ficção: Armazenamento de Arquivos

3.4. Configuração de Tabelas

O Azure Table Storage é usado para dados NoSQL.

Na conta de armazenamento, selecione "Tabelas" e crie uma nova tabela.
Insira os dados na tabela conforme necessário.
Imprimir Fictício: Configuração de Tabelas

3.5. Discos de Armazenamento

Para Azure Disk Storage :

Acesse a seção "Discos" e selecione "Adicionar".
Configure o disco, escolha o tipo (HDD padrão, SSD padrão, SSD Premium) e tamanho.
Imprimir Ficção: Configuração de Discos de Armazenamento

4. Gerenciamento e Segurança do Armazenamento

4.1. Monitoramento

Utilize o Azure Monitor para monitorar o desempenho e o uso do armazenamento. Configure alertas para notificar sobre problemas como alta utilização de espaço.

Imprimir Ficção: Monitoramento do Armazenamento

4.2. Backup e Recuperação

Configure o Backup do Azure para criar cópias de segurança automática dos dados armazenados. Isso garante a proteção contra perda de dados e permite recuperação rápida em caso de falha.

Imprimir Ficção: Configuração de Backup

5. Escalabilidade e Redundância

5.1. Escalabilidade

Ajuste a capacidade de armazenamento conforme necessário. No Blob Storage , por exemplo, você pode escalar a capacidade e o desempenho ajustando as opções de redundância e desempenho.

Imprimir Ficção: Escalabilidade do Armazenamento

5.2. Redundância

Escolha o tipo de redundância protegida (LRS, GRS, RA-GRS) para garantir que seus dados sejam replicados e protegidos contra falhas.

Imprimir Ficção: Configuração de Redundância

6. Conclusão

A experiência de configuração e gerenciamento de recursos de armazenamento no Azure mostrou-se enriquecedora e prática. O Azure oferece uma variedade de opções de armazenamento que podem ser ajustadas e dimensionadas para atender a diferentes necessidades, desde arquivos e blobs até tabelas e discos de VMs. A utilização de ferramentas como Azure Monitor e Azure Backup é crucial para garantir o desempenho, segurança e integridade dos dados.

7. Próximos Passos

Os passos seguintes são:

Explore o Azure Data Lake Storage para armazenamento de dados em larga escala e análise.
Investigue os níveis de acesso do Azure Blob Storage para otimização de custo com base no acesso dos dados.
Implementar práticas avançadas de gerenciamento de dados e automação para melhorar a eficiência e a segurança dos recursos de armazenamento.

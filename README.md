# Criando Dashboard Vendas Xbox Excel

## Índice 

* [Índice](#índice)
* [Descrição](#descrição)
* [Tecnologia Utilizadas](#tecnologias-utilizadas)
* [Estrutura do Projeto](#estrutura-do-projeto)
* [Base de Dados](#base-de-dados)
* [Funcionalidades Principais](#funcionalidades-principais)
* [Metodologia de Desenvolvimento](#metodologia-de-desenvolvimento)
* [Visualizações e Insights](#visualizações-e-insights)
* [Como Utilizar](#como-utilizar)
* [Atualização de Dados](#atualização-de-dados)
* [Licença](#licença)
* [Acesse o Projeto](#acesse-o-projeto)
* [Autor](#autor)


## 📊 Descrição do Projeto

Este projeto consiste em um dashboard desenvolvido em Excel para análise de dados de assinaturas de serviços. O dashboard foi criado para transformar dados brutos em informações estratégicas através de tabelas dinâmicas e visualizações gráficas.

## Tecnologias Utilizadas

- Microsft Office
- Microsft Copilot

## 🗂️ Estrutura do Projeto

O arquivo Excel está organizado em quatro abas principais:

1. **Assets**: Contém recursos visuais como logomarcas, paletas de cores e ícones utilizados no dashboard.
2. **Bases**: Armazena todos os dados brutos que serão analisados.
3. **Cálculos**: Contém todas as tabelas dinâmicas e cálculos que sustentam as análises exibidas no dashboard.
4. **Dashboard**: Apresenta a visualização final dos dados através de gráficos dinâmicos.

## 📋 Base de Dados

A base de dados utilizada contém as seguintes colunas:

| Coluna | Descrição |
|--------|-----------|
| Subscriber ID | ID único de registro de cada assinatura |
| Name | Nome do assinante |
| Plan | Plano contratado pelo assinante |
| Start Date | Data de início da assinatura |
| Auto Renewal | Informação sobre renovação automática (Sim/Não) |
| Subscription Price | Valor da assinatura principal |
| Subscription Type | Tipo de assinatura (Anual, Mensal ou Trimestral) |
| EA Play Season Pass | Indica se o usuário possui assinatura da plataforma EA (Sim/Não) |
| EA Play Season Pass Price | Valor pago pela assinatura do EA Play Season Pass |
| Minecraft Season Pass | Indica se o usuário possui assinatura da plataforma Minecraft (Sim/Não) |
| Minecraft Season Pass Price | Valor pago pela assinatura do Minecraft Season Pass |
| Coupon Value | Valor do cupom de desconto utilizado (se aplicável) |
| Total Value | Valor total da assinatura incluindo todos os componentes |

## 📈 Funcionalidades Principais

O dashboard foi desenvolvido para responder às seguintes perguntas de negócio:

1. Qual o faturamento Total de vendas de planos anuais (contendo todas as assinaturas agregadas)?
2. Qual o faturamento Total de vendas de planos anuais, separados por renovação automática e sem renovação automática?
3. Total de vendas de Assinaturas do EA Season Pass.
4. Total de vendas de Assinaturas do Minecraft Season Pass.
5. Evolução do Total de Vendas de Assinaturas do EA Season Pass.
6. Evolução do Total de Vendas de Assinaturas do Minecraft Season Pass.

## 🛠️ Metodologia de Desenvolvimento

### Criação de Tabelas Dinâmicas

1. Todo o intervalo de dados foi selecionado na aba Bases.
2. Na guia "Inserir", foi selecionada a opção "Tabela Dinâmica".
3. O intervalo de dados foi especificado e a tabela dinâmica foi criada na aba "Cálculos".
4. Para cada pergunta de negócio, campos específicos foram arrastados para as áreas de:
   - Filtros
   - Colunas
   - Linhas
   - Valores

### Criação de Gráficos Dinâmicos

1. Para cada tabela dinâmica, um gráfico dinâmico correspondente foi criado.
2. Os gráficos foram formatados utilizando as cores e estilos definidos na aba Assets.
3. Todos os gráficos foram inseridos na aba Dashboard, proporcionando uma visualização centralizada e intuitiva dos dados.

## 📊 Visualizações e Insights

O dashboard final apresenta:

- Cartões com KPIs principais
- Gráficos de barras para comparação de faturamento por planos com auto-renovação e sem auto renovação
- Gráficos de barras mostrando a evolução mensal das vendas EA Play e Minecraft
- Segmentações de dados (slicers) para filtragem interativa pelos períodos mensal, trimestral e anual.

## 💻 Como Utilizar

1. Abra o arquivo Excel (recomendado Excel 2016 ou superior).
2. Navegue até a aba "Dashboard" para visualizar todos os gráficos e KPIs.
3. Utilize as segmentações de dados para filtrar as informações conforme necessário.
4. Para atualizar os dados, substitua apenas as informações na aba "Bases" - todas as tabelas dinâmicas e gráficos serão atualizados automaticamente.

## 🔄 Atualização de Dados

Para atualizar o dashboard com novos dados:

1. Acesse a aba Dashboard e clique com botão direito para aparecer a opção reexibir.
2. Na opçao Reexibir selecione a aba "Bases".
2. Substitua ou adicione novos dados aos existentes, mantendo a mesma estrutura de colunas.
3. Atualize todas as tabelas dinâmicas (clique com o botão direito em qualquer tabela dinâmica e selecione "Atualizar").
4. Ainda na aba "bases" clique com o botão direito e selecione a opção ocultar, para ocultar a aba "Bases" deixando apenas a aba dashboard para visualização.

## 📜 Licença

Este projeto está licenciado sob a licença MIT 

## 🔗 Acesso ao Projeto

Você pode acessar e baixar este projeto através do seguinte link:
GitHub - [Dashboard de Análise de Assinaturas](https://github.com/FredericoSander/Criando_Dashboard_Vendas_Xbox_Excel/blob/main/Report/Relat%C3%B3rio.xlsx)

Ou clone o repositório usando o comando:
git clone https://github.com/FredericoSander/Criando_Dashboard_Vendas_Xbox_Excel.git

- Requisitos para execução: Microsoft Excel 2016 ou superior
- Recomendado: 4GB de RAM para melhor desempenho com grandes volumes de dados.

## 👤 Autor
| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/136928502?s=96&v=4" width=115><br><sub>Frederico Sander</sub>](https://github.com/FredericoSander)
| :---: | 

Este README é parte da documentação do projeto de Dashboard Excel para análise de assinaturas, desenvolvido como parte do curso do Bootcamp HeineKen - Inteligência Artificial Aplicada a Dados com Copilot.



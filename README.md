A proposta de sistema de revendedora de carros precisa ser revisada, pois contém elementos que não se encaixam em um site/app/software de revendedora de carros. Abaixo está a versão corrigida do texto:

**Projeto Integrador - RevCar**
Início do projeto: 27/02/2023.

Alunos: Murilo Watanabe (https://github.com/MuriloWatanabe), Phelipi Moser (https://github.com/PhelipiM) e William Nunes (https://github.com/Nunes-Willi)

Links do projeto: 
[Link do projeto]()

**Situação Problema:**

O sistema será desenvolvido pela empresa RevCar, responsáveis por uma franquia de revenda de carros no Brasil a mais de um ano, os principais funcionários serão os que terão acesso ao sistema.

A empresa segue a seguinte a forma: o cliente está procurando um carro usado e veio até nossa concessionaria.ele ja tinha algumas preferências em mente e um orçamento limite ja definido.No entanto o cliente esta indeciso com a decisão do carro, e precisa de ajuda para escolher algum de sua necessidade.O representante da nossa empresa já com as preferências do cliente em mente e a quantia que pode ser paga , faz um orçamento numa planilha e em seguida impressos numa impressora para organização dos pedidos,porém devido a demanda grande de carros a revender a organização fica fajuta e não permite organizar os orçamentos nem as documentações do cliente e as vias para um tempo sem atrasos ou problemas de compra.

Notamos a falta de recursos para organização de orçamentos no software da empresa, e dificuldades para fazer documentos do veículo sem que prejudique o tempo de venda.


**Descrição da proposta:**
A nossa proposta de solução para a revendedora de carros é implementar um sistema integrado que automatize o processo de venda de veículos. O sistema permitirá o registro das características dos veículos, gerenciamento de informações do cliente e agendamento de revendas. Essas soluções visam agilizar o processo, reduzir o uso de papel e aumentar a eficiência operacional da empresa.

**Regras de negócio:**

RN01 – Criação de Orçamentos: Para cada cliente que demonstra interesse em comprar um carro, um orçamento deve ser criado no sistema, levando em consideração suas preferências e o orçamento máximo definido.

RN02 – Organização de Orçamentos: Os orçamentos devem ser arquivados em ordem cronológica e separados por categoria de carros, para facilitar a consulta e acompanhamento das negociações.

RN03 – Registro de Preferências: O sistema deve permitir que os representantes registrem as preferências dos clientes, como marca, modelo, ano e recursos desejados, para que sejam considerados ao montar os orçamentos.

RN04 – Documentação do Veículo: Após a venda, o sistema deve gerar automaticamente os documentos necessários para a transferência de propriedade do veículo, incluindo contrato de compra e venda e requerimentos legais.

RN05 – Controle de Estoque: O sistema deve manter um registro atualizado do estoque de carros disponíveis para venda, incluindo informações sobre marca, modelo, ano, quilometragem e preços.

RN06 – Acesso Restrito: Apenas funcionários autorizados, como representantes de vendas e gerentes, devem ter acesso ao sistema para garantir a segurança das informações dos clientes e dos carros disponíveis.

RN07 – Acompanhamento de Vendas: O sistema deve permitir o acompanhamento do processo de venda, registrando quando um orçamento é convertido em uma venda efetiva e atualizando o estoque automaticamente.

RN8 – Relatórios de Vendas: O sistema deve gerar relatórios regulares de vendas, mostrando informações como carros mais vendidos, média de preços, desempenho dos representantes e outras métricas relevantes.

RN09 – Classificação de Orçamentos: Os orçamentos devem ser classificados em diferentes estágios do processo de venda, como "Em análise", "Aguardando decisão do cliente", "Negócio fechado" e "Negócio não concluído", para facilitar o acompanhamento e a gestão.

RN10 – Validade dos Orçamentos: Os orçamentos terão uma validade de 10 dias a partir da data de emissão. Após esse período, o cliente deverá ser consultado novamente para confirmar seu interesse antes de prosseguir com a venda.

RN11 – Registro de Histórico de Comunicação: O sistema deve permitir o registro de todas as interações e comunicações entre os representantes e os clientes, incluindo telefonemas, e-mails e reuniões presenciais.

RN12 – Controle de Prazos de Documentação: O sistema deve gerenciar prazos de documentação, lembrando os representantes sobre a necessidade de coletar e entregar documentos específicos dos clientes para a conclusão das vendas.

RN13 – Notificações de Acompanhamento: O sistema deve enviar notificações automáticas aos representantes e gerentes para lembrar o acompanhamento e o follow-up dos orçamentos em aberto, garantindo que nenhum cliente seja negligenciado.

**Requisitos funcionais:**

*ENTRADA*
RF001 - Cadastro de veículos: O sistema deve permitir o cadastro de veículos com suas respectivas características.

RF002 - Análise de crédito: O sistema deve realizar uma análise de crédito automatizada com base nas informações fornecidas pelo cliente.

RF003 - Documentação digitalizada: O sistema deve permitir o armazenamento e o acesso digitalizado dos documentos relacionados à venda de veículos.

RF004 - Cadastro de clientes: O sistema deve permitir o cadastro de clientes com informações pessoais e histórico de compras.

RF005 - Agendamento de revendas: O sistema deve permitir o agendamento de revendas de veículos, registrando a data e hora da revenda.

RF006 - pagamentos: o sistema para processar os pagamentos dos clientes por meio de várias opções, como cartões de crédito, PayPal, dinheiro vivo ou outros métodos de pagamento. Tendo as opções de pagar à vista ou parcelado.

RF007 - Transferência de documentos: O sistema deverá abrir uma nova janela pedindo a transferência de documento do veículo

*SAIDA*

<!-- Essas são apenas algumas das funcionalidades que o sistema proposto pode ter. Mais detalhes e telas específicas serão.apresentados na etapa de especificação de requisitos. É importante ressaltar que o sistema deve ser intuitivo e fácil de usar, proporcionando uma experiência agradável tanto para os clientes quanto para os funcionários da revendedora. -->

**Requisitos não funcionais:**

RNF001: Usabilidade: O sistema deve ser fácil de usar e intuitivo, com uma interface amigável para os usuários.

RNF002: Performance: O sistema deve ser rápido e responsivo, garantindo tempos de resposta baixos.

RNF003: Segurança: O sistema deve garantir a segurança das informações dos clientes e dos dados da revendedora, utilizando medidas como criptografia e controle de acesso.

RNF004: Escalabilidade: O sistema deve ser escalável, capaz de lidar com um aumento no número de veículos, clientes e transações.

RNF005: Confiabilidade: O sistema deve ser confiável, garantindo a integridade e disponibilidade dos dados.

RNF 06 - Sistema operacional: O sistema deverá ser usado em sistemas operacionais windows, linux.

<!-- RNF 07 - Processador: É recomendado para o sistema no mínimo um processador Intel i3, similar ou superior a geração 7100, para que o servidor funcione em sua melhor performance. -->

**Conclusão:**
Com a implementação desse sistema de revendedora de carros, esperamos proporcionar uma melhor experiência para a empresa e seus clientes, otimizando o processo de venda de veículos, reduzindo custos operacionais e aumentando a eficiência. Além disso, o uso de tecnologias modernas e a automação de tarefas ajudarão a revendedora a se manter competitiva no mercado.
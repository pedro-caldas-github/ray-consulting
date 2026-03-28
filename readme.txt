📊 Perguntas de Negócio Respondidas
O dashboard foi projetado para responder a perguntas críticas para a tomada de decisão:

Performance Financeira: Qual é o faturamento total acumulado e como ele oscila mês a mês? Qual a nossa média de ticket médio atual?

Geografia das Vendas: Quais cidades (New York vs. London) trazem o maior volume financeiro para a empresa?

Análise de Mix: Quais categorias e produtos (como o Thüringer Rostbratwurst) lideram em valor vendido e quais possuem maior giro de estoque?

Gestão de Talentos: Quem são os vendedores com maior participação no faturamento e como está o ranking de produtividade do time?

Eficiência Logística: Quantos pedidos estão atrasados e qual o impacto financeiro (valor em risco) dessas entregas fora do prazo?

🎨 Justificativa do Design
A escolha do design baseou-se nos princípios de Data Storytelling e UX/UI Design:

Navegação Segmentada: O uso de páginas específicas (Pedidos, Produtos, Vendas, Entregas) evita a sobrecarga cognitiva, permitindo que o usuário foque em um domínio de cada vez.

Identidade Visual: Utilização de cores sóbrias com destaque para o azul (identidade da marca) e uso semântico de cores (Vermelho para atrasos/negativos e Verde para metas/prazo), facilitando a leitura rápida dos dados.

Hierarquia de Informação: KPIs principais posicionados à esquerda e no topo, seguindo o padrão de leitura em "Z", garantindo que os números mais importantes sejam vistos primeiro.

Interatividade: Inclusão de segmentadores de data (Slicers) e filtros de categoria para permitir que o usuário faça o "drill-down" e personalize sua própria análise.

📈 Explicação dos Indicadores (KPIs)
Faturamento (R$ 24,11 Mi): Soma total do valor dos pedidos considerando os descontos aplicados (OrderTotal[discounted]). É o termômetro principal de sucesso da operação.

Ticket Médio (R$ 11,19 Mil): Calculado como Total Faturamento / Total de Pedidos. Indica o valor médio gasto por cliente em cada transação.

Contagem de Pedidos: Quantidade absoluta de ordens de venda processadas no período.

Dias para Entrega: Coluna calculada via criação de nova coluna com transformar dados para identificar a velocidade da entrega de cada pedido.

Pedidos Atrasados (92 pedidos / 678 Mil Valor): KPI baseado na regra de data prometida versus data de envio. É um indicador de risco e satisfação do cliente.

Participação de Vendas (Share): Medida percentual que mostra o quanto cada vendedor representa do faturamento total da companhia.
# TripleTen-10-Projeto_Analise_Eventos


Projeto Integrado 2

Luiz Guilherme Graciano Ribeiro Pereira

A atividade consiste em um trabalho para em uma startup ficticia que vende produtos alimentícios. Você precisa analisar o comportamento do usuário para o aplicativo da empresa.

Primeiro estude o funil de vendas. Descubra como os usuários chegam à etapa de compra. Quantos usuários realmente chegam a essa etapa? Quantos ficam presos nas fases anteriores? Quais etapas em particular?

Em seguida, veja os resultados do teste A/A/B. Os designers gostariam de alterar as fontes de todo o aplicativo, mas os gerentes temem que os usuários achem o novo design intimidador. Eles decidem tomar a decisão com base nos resultados de um teste A/A/B.

Os usuários são divididos em três grupos: dois grupos de controle recebem as fontes antigas e um grupo de teste recebe as novas. Descubra qual conjunto de fontes produz melhores resultados.
Descrição dos dados

Cada entrada de diário é uma ação do usuário ou um evento.

    EventName — nome do evento
    DeviceIDHash — dentificador de usuário exclusivo
    EventTimestamp — hora do evento
    ExpId — número do experimento

Descrição dos gruos de experimento:

246 - grupo de controle;

247 - grupo de controle;

248 - grupo de teste;

Descrição dos tipos de eventos:

MainScreenAppear: Indica o momento em que um usuário acessou a tela principal do aplicativo. Essa é geralmente a primeira tela que os usuários veem após abrir o aplicativo.

OffersScreenAppear: Indica o momento em que um usuário acessou a tela de ofertas no aplicativo. Isso pode acontecer quando os usuários navegam pelas promoções ou descontos disponíveis.

CartScreenAppear: Indica o momento em que um usuário visualizou o carrinho de compras no aplicativo. O evento provavelmente é acionado quando o usuário acessa a página do carrinho para revisar os itens selecionados.

PaymentScreenSuccessful: Indica o momento em que um usuário concluiu com sucesso uma transação de pagamento no aplicativo. Esse evento geralmente ocorre após o usuário inserir as informações de pagamento e a transação ser processada com êxito.

# Conclusão

Os usuário médio ao entrar no site, faz a seguinte sequência, visualiza a tela principal, seguido da tela de ofertas, com a visualização do carrinho de compras e por fim a finalização do pagamento com a compra do produto. Aqueles usuários que virão o tutorial antes de acessar a tela principal tem uma chance maior de comprar. Logo, para melhorar a conversão, devesse incentivar o usuário a fazer o tutorial.

O teste A/B demonstrou que a mudança nas fontes do aplicativo, não faz os usuários acessarem nenhum evento com mais frequência, e não aumenta o nível de conversão.


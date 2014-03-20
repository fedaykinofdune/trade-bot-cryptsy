Bitcoin Trade BOT (cryptsy)
==============

Trade bot para cryptsy, qualquer altcoin.


Uso:
==============

Para inciar a utilizar você precisa ativar a API na sua conta e inserir sua Public e Private Key

Você encontrará isso na sessão API Keys em suas configurações do Cryptsy

https://www.cryptsy.com/users/settings


Alteração:
==============

É preciso muita atenção na configuração do BOT. Ele está inicialmente configurado para trabalhar com a
AuroraCoin.


$addPrice

Valor para ser adicionado ao valor de compra quando o lucro é menor que o prejuizo


$fee

Valor cobrado pela exchange por cada transação ( em porcentagem ), no caso do cryptsy usarei 0.3


$tempo

Tempo em minutos que uma ordem de compra fica ativa antes de ser refeita.



Dicas:
==============

Procure não utilizar o projeto em horários com pouco movimentação na exchang ou em periodos com muita ALTA ou muita BAIXA da Altcoin. Isto pode fazer suas ordens demorarem mais para fechar.


De forma alguma, altere, cancele ou abra novas ordens enquanto o programa estiver rodando. Caso queira cancelar uma ordem manualmente, ou criar uma ordem manualmente, feche o programa.

Tenha paciência, algumas ordens podem levar vários minutos para fechar. E o lucro nem sempre é grande suficiente, este aplicativo foi criado para rodar várias horas a fim de obter lucro.

Criado baseado no trabalho de ipsBruno
github.com/ipsBruno/trade-bot-btce
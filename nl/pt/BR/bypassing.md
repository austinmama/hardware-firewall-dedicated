---

copyright:
  years: 2017
lastupdated: "2018-11-30"

keywords: bypass, firewall, rules,

subcollection: hardware-firewall-dedicated

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:download: .download}
{:note: .note}
{:important: .important}

# Efetuando bypass das regras do Hardware Firewall (Dedicated)
{: #bypassing-hardware-firewall-dedicated-rules}

Para efetuar bypass das regras de firewall,

1. Em seu navegador, abra o [Portal do cliente ![Ícone de link externo](../../icons/launch-glyph.svg "Ícone de link externo")](https://control.softlayer.com/){: new_window} e efetue login em sua conta.
2. Na navegação do Portal do cliente, acesse **Rede > Gerenciamento de IP > VLANs** e clique no dispositivo de firewall do qual você deseja efetuar bypass.
3. Na página **Detalhes do dispositivo**, é possível usar o menu suspenso **Ações** para escolher **Configurar bypass de regra** ou, na seção **Status**, é possível clicar no botão **Ignorar regras**. De qualquer maneira, é necessário receber um diálogo de confirmação. Clique em **Sim** para confirmar a ação. A realização de bypass das regras leva aproximadamente dois minutos para entrar em vigor. Enquanto no modo bypass, o "Status"
será "Efetuando bypass de todas as regras".

	Outra opção é rotear ao redor do firewall quando você estiver fazendo a resolução de problemas ou etc; é possível usar o menu suspenso **Ações** para escolher **Configurar bypass de rota** ou, na seção **Status**, é possível clicar em **Rotear ao redor**.

## Ativar as regras novamente
{: #enable-the-rules-again}

Para ativar as regras novamente, siga as instruções acima para acessar a página **Detalhes do
dispositivo**, clique no menu suspenso **Ações** e escolha **Configurar
bypass de rota**. Você obterá um diálogo de confirmação. Clique em **Sim** para confirmar a ação. O "status" retornará para "Roteamento POR MEIO do firewall" em dois minutos.

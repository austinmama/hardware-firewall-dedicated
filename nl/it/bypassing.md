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

# Esclusione delle regole di Hardware Firewall (Dedicated)
{: #bypassing-hardware-firewall-dedicated-rules}

Per escludere le regole del firewall,

1. Dal tuo browser, apri [Customer Portal ![Icona link esterno](../../icons/launch-glyph.svg "Icona link esterno")](https://control.softlayer.com/){: new_window} e accedi al tuo account.
2. Nella navigazione del portale del cliente, passa a **Network > IP Management > VLANs** e fai clic sul dispositivo firewall che vuoi escludere.
3. Nella pagina **Device Details**, puoi utilizzare il menu a discesa **Actions** per scegliere **Set Rule Bypass** oppure, nella sezione **Status**, puoi fare clic sul pulsante **Bypass Rules**. In entrambi i casi, dovrebbe comparire una finestra di dialogo di conferma. Fai clic su **Yes** per confermare l'azione. L'esclusione delle regole ha effetto dopo circa due minuti. Durante la modalità di esclusione, "Status" sarà "Bypassing All Rules".

	Un'altra opzione è l'instradamento intorno al firewall, ad esempio quando stai eseguendo la risoluzione dei problemi; puoi utilizzare il menu a discesa **Actions** per scegliere **Set Route Bypass** oppure, nella sezione **Status**, puoi fare clic su **Route Around**.

## Riabilita le regole
{: #enable-the-rules-again}

Per riabilitare le regole, segui le istruzioni sopra riportate per raggiungere la pagina **Device Details**, fai clic sull'elenco a discesa **Actions** e scegli **Set Route Bypass**. Visualizzerai una finestra di dialogo di conferma. Fai clic su **Yes** per confermare l'azione. "Status" ritornerà "Routing THROUGH firewall" in due minuti.

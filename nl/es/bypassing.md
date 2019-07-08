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

# Ignorar las reglas del cortafuegos de hardware (dedicado)
{: #bypassing-hardware-firewall-dedicated-rules}

Para ignorar las reglas de cortafuegos:

1. En el navegador, abra el [Portal de clientes ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono de enlace externo")](https://control.softlayer.com/){: new_window} e inicie sesión en su cuenta.
2. En la navegación del Portal de clientes, vaya a **Red > Gestión de IP > VLAN** y pulse el dispositivo de cortafuegos que desea ignorar.
3. En la página **Detalles de dispositivo**, utilice el menú desplegable **Acciones** para seleccionar **Definir omisión de regla** o pulse el botón **Ignorar reglas** en la sección **Estado**. En cualquier caso, obtendrá un diálogo de confirmación. Pulse **Sí** para confirmar la acción. La omisión de las reglas tarda aproximadamente dos minutos en aplicarse. En la modalidad de omisión, el "Estado" será "Ignorando todas las reglas".

	Otra opción es sortear el cortafuegos si está resolviendo problemas, o puede utilizar el menú desplegable **Acciones** para seleccionar **Definir omisión de ruta** o pulse **Ignorar reglas** en la sección **Direccionar alrededor**.

## Habilitar las reglas de nuevo
{: #enable-the-rules-again}

Para volver a habilitar las reglas, siga las instrucciones anteriores para llegar a la página **Detalles del dispositivo**, pulse el menú desplegable **Acciones** y elija **Definir omisión de ruta**. Obtendrá un diálogo de confirmación. Pulse **Sí** para confirmar la acción. El "estado" cambiará de nuevo a "Direccionando A TRAVÉS del cortafuegos" pasados dos minutos.

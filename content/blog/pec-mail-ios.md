---
title: "Come configurare la PEC Aruba su Mail per iOS e iPadOS"
date: 2021-10-16T08:00:28+02:00
draft: false
author: "Claudio Stoduto"
description: "Come configurare la propria posta certificata PEC sul proprio iPhone e iPad sull'applicazione Mail."
categories: ["Tecnologia"]
url: /configurazione-pec-aruba-ios/
featuredImage: "https://res.cloudinary.com/claudiostoduto/image/upload/v1605100311/Nasci_sbagli_e_cresci_podcast.jpg"
tags: [pec aruba iphone, pec aruba ipad, pec aruba macos,come configurare la pec aruba su iphone, come configurare la pec aruba su ipad, come configurare la pec aruba su mac, pec aruba imap, pec aruba]
lua:
  image:
    url: "https://res.cloudinary.com/claudiostoduto/image/upload/v1605100311/Nasci_sbagli_e_cresci_podcast.jpg"
    width: 100%
    height: 100%
---
## Come configurare la propria posta certificata PEC sul proprio iPhone e iPad sull'applicazione Mail.

<img class="aligncenter size-full" src="https://res.cloudinary.com/claudiostoduto/image/upload/v1634367605/aruba-pec-2.png" width="100%" height="100%" />

Dovendo resettare l'iPhone e sistemare l'applicazione Mail ho deciso di fare una breve guida per chi non vuole avere installata l'applicazione Aruba PEC e sfruttare il client di posta già presente su iPhone e iPad. Vediamo quindi come configurare manualmente la **PEC Aruba su iOS e iPadOS**.

### iOS e iPadOS

<img class="aligncenter size-full" src="https://res.cloudinary.com/claudiostoduto/image/upload/v1634367374/xacp7tethjgmdb33m1is.png" width="100%" height="100%" />

<img class="aligncenter size-full" src="https://res.cloudinary.com/claudiostoduto/image/upload/v1634367390/vpf8zlosaakqfmm2d0s8.png" width="100%" height="100%" />

* Aprire l'applicazione **Impostazioni**;
* Clicchiamo su **Mail**;
* A questo punto **Account**;
* Infine **Aggiungi account**;
* Selezioniamo **Altro** fra le opzioni disponibili dei provider;
* Sotto Mail premiamo **Aggiungi account Mail**;
	* Nome: **Nome e Cognome** vostro;
	* E-mail: **nomecognome@pec.it** o il vostro indirizzo di posta PEC Aurba;
	* Password: chiaramente la vostra **password**;
	* Descrizione: io ho messo un banale **PEC**;
	* Avanti;
* Facciamo attenzione che in alto ci troviamo nella sezione **IMAP**;
* In **Server posta in arrivo** mettiamo:
	* Nome host: **imaps.pec.aruba.it**;
	* Nome utente: **nomecognome@pec.it** (la vostra email PEC);
	* Password: la medesima **password** già inserita in precedenza;
* In **Server posta in uscita** mettiamo:
	* Nome host: **smtps.pec.aruba.it**;
	* Nome utente: **nomecognome@pec.it** (la vostra email PEC);
	* Password: la medesima **password** già inserita in precedenza.
* Premere **Avanti**.

La procedura a questo punto è completata per il vostro iPhone o iPad.

Tenete presente che, non essendo un client predefinito per la PEC, alcuni allegati potrebbero non essere visibili o leggibili.  Se vi serve solo la consultazione della PEC allora va benissimo Mail. Io preferisco così, giusto per non avere un'altra applicazione inutile installata.

Ricordate sempre **[#DOMORE](https://claudiostoduto.com/domore/) & #VIVALAVIDA**.

<hr />
<p style="text-align: center;"><em>Perch&eacute; non ci sono i <strong>commenti?</strong> Semplice, se vuoi scrivermi qualcosa in merito a questo articolo contattami su&nbsp;<a href="Https://t.me/claudiostoduto">Telegram</a> o <a href="Http://www.twitter.com/claudiostoduto">Twitter</a>.</em></p>
<hr />
 
<p style="text-align: center;">Iscriviti alla mia <strong>newsletter</strong> <strong>settimanale</strong>&nbsp;<strong>gratuita</strong>, serve solo la tua email</p>

 <form style="border:1px solid #ccc;padding:3px;text-align:center;" action="https://tinyletter.com/claudiostoduto" method="post" target="popupwindow" onsubmit="window.open('https://tinyletter.com/claudiostoduto', 'popupwindow', 'scrollbars=yes,width=800,height=600');return true"><p><label for="tlemail">Inserisci il tuo indirizzo email:</label></p><p><input type="text" style="width:140px" name="email" id="tlemail" /></p><input type="hidden" value="1" name="embed"/><input type="submit" value="Iscriviti" /><p><a href="https://claudiostoduto.com" target="_blank">by Claudio Stoduto</a></p></form>
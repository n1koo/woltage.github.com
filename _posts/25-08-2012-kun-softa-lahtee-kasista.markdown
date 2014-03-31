---
layout: post
title: Irssi ConnectBot - Kun softa lähtee käsistä
---
Irkkaaminen mobiililaitteella on aina ollut hankalaa varsinkin jos käytössä on Irssi ja SSH-yhteys. Itse käytin iPhonessa monenlaisia terminaaliohjelmia SSH-yhteyden muodostamiseksi, mutta kaikki toimivat yhtä heikosti.

Vannoin iPhoneen nimeen kauan, mutta kalenterin puuttuminen lukkovalikosta (joka myöhemmin sinne laitettiinkin) ja rajoittunut iOS turhautti. Kaverini Jonne Backhaus (se hörhö androidsuomi.fi:stä) valisti minulle Androidin ilosanomaa. Innostuin ja aloin tutustumaan emulaattorin avulla käyttöjärjestelmän ominaisuuksiin.

Androidille oli kohtuullisen hyvä SSH-asiakasohjelma olemassa ConnectBot. Tästäkin asiakasohjelmasta puuttui se jokin, käyttöliittymää ei ollut optimoitu irkkaukseen.

Ajauduin tutkimaan ConnectBotin lähdekoodeja, jonka seurauksena huomasin kehittäväni softaa mobiililaitteelle jota en edes omista. Emulaattorilla tehtiin ensimmäiset kokeet ja sain muutaman idean jolla käytettävyyttä voitaisi parantaa:

Yksi näistä oli tuplaklikkaus, joka lähettäisi meta+a komennon. Se on Irssistä tuttu näppäimistöyhdistelmä, joka vaihtaa ikkunaa priosoidusti: 1. privaatti ikkuna, 2. nimi mainittu, 3. yleistä puhetta, 4. kaikki muut.

Toisenan ideana keksin käyttää pitkää painallusta, jonka avulla voitaisi syöttää esivalintaisia komentoja. Tämä helpottaa käyttäjää suuresti, kun näppäimistöyhdistelmiä ei tarvitse syöttää pienien painikkeiden kautta.

Tarjosin näitä ominaisuuksia myös ConnectBottiin, josta tuomittiin muutokset ja niitä ei haluttu sotkea päähaaran kanssa. Petyin hieman, mutta pettymyksen jälkeen syntyi idea omasta forkista. Tällä tavalla pystyttiin tarjoamaan ConnectBotin päälle käyttöä helpottavia ominaisuuksia. Nimeksi syntyi lopulta loogisesti Irssi ConnectBot (lyhenne: ICB).

Tällä hetkellä Irssi ConnectBotissa on yllämainittujen ominaisuuksien lisäksi myös symbolimerkistö, ennustavatekstinsyöttö, “force size” -muisti ja korjauksia mm. HTC Desire Z:n ääkkös ongelmaan.

Irssi ConnectBotin piti aluksi olla pelkästään omaan käyttööni tarkoitettu sovellus, jolla helpotan irkkaamistani. Kuitenkin Irssi ConnectBot sai paljon huomiota Android yhteisöltä. Tästäkin kiitokset Jonnelle, joka julkaisi muutamankin artikkelin Irssi ConnectBotista. Yhteisöt ovat antaneet kullanarvoisia ideoita kehitykseen ja myös sparranneet (=vittuilleet, varsinkin #android.fi) ohjelmistoa eteenpän.

Tällä hetkellä Irssi ConnectBotilla on yli 23 000 aktiivista käyttäjää ja melkein 55 000 asennusta. Irssi ConnectBot lähti käsistäni totaalisesti ja hommassa on ollut auttajia useita. Erityisesti kiitokset menevät Jonne Backhausille, Timo Reunaselle, Ville Kermiselle ja Jani Penttiselle. Kiitoksia, kun olette olleet mukana kehittämässä mobiilisen Irssin vallankumousta.

![center](http://f.cl.ly/items/060z0I0V2C1B2I3E313a/Screen%20Shot%202011-11-24%20at%2022.30.04.png)	

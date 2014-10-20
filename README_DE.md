Task Force Arma 3 radio
=======================
# Bitte unterstützt TFAR auf ["MakeArmaNotWar"](http://makearmanotwar.com/entry/pMP8c7vSS4#.VA1em_nV9UD)!

Arma 3 Team Speak Radio Erweiterung ([Dokumentation](https://github.com/michail-nikolaev/task-force-arma-3-radio/wiki))
_v0.9.5 (16-10-2014)_

#####Kompatibel mit den Versionen 0.9.3 sowie 0.9.4, jedoch NICHT mit 0.9.2

###Installation

* Die Datei herunterladen und entpacken [0.9.5 radio archive](https://www.dropbox.com/s/7xs9t71716uf5cf/0.9.5.zip?dl=1).
* Kopiere den Inhalt des `TeamSpeak 3 Client` Ordners ins das TeamSpeak Hauptverzeichnis.
* Kopiere den Inhalt des  `Arma 3` Ordners in das Verzeichnis `...\SteamApps\common\Arma 3 Ordner`.

> TFAR verwendet die aktuelle Version der MOD "CBA" (Community Base Addons). Falls Du bereits CBA installiert haben solltest wird Windows die Frage stellen, ob der Ordner ersetzt werden soll.


###Einrichtung

* Stelle sicher, dass die  `Feststelltaste` nicht bereits im Teamspeak eine Verwendung hat
* Deaktiviere das "voice over network" (VON) innherhalb von Arma oder stelle sicher, dass nicht die `Feststelltaste` hierfür fungiert (Um Stimmdopplungen zu vermeiden).
* Öffne die Pluginliste von Teamspeak: `Einstellungen > Plugins`.
  1. Aktiviere `Task Force Arma 3 Radio`.
  2. Es ist ratsam - um Konflikte zu vermeiden - `ACRE` sowie `radio ts ARMA3.ru` zu deaktivieren (Falls diese installiert       sein sollten)
  3. Nur für den Fall – Verwende den Knopf `Alles Aktualisieren` links unten.
* Make sure the volume of alerts is not turned off in Team Speak: `Options > Payback > Sound Pack Volume` - set a positive value.
* Start the game with `@CBA_A3` & `@task_force_radio` add-ons (Community Base Addons: A3 Beta & Task Force Arrowhead Radio). It can be done by adding the mod names to the game shortcut after the EXE file `…\arma3.exe -mod=@CBA_A3;@task_force_radio`, however, it is recommended to enable the necessary mods in the game settings (`Settings -> Expansions`).
* Join the same channel with other players using the radio, or you will be navigated to the `TaskForceRadio` channel, if there is one at the start of a mission.

> You will get the same nick both in the game profile and TeamSpeak - plugin will change your nickname in TS during the game.

> Stelle sicher, dass dein Arma-Spielname mindestens 3 Buchstaben lang ist.

> Es ist nicht ratsam das Plugin zu verwenden, während man sich auf unterschiedlichen Teamspeakservern aufhält.

> Es ist empohlen die Teamspeak eigenen Geräusche zu deaktivieren: `Einstellungen> Meldungen> Sound Pack: "Sounds Deactivated"`. Um die Einstellung anzuwenden muss Teamspeak neu gestartet werden.


###Tastenbelegung

| Taste | Funktion |
| --- | --- |
| Push-to-talk Knopf im Teamspeak | Direktes Sprechen. |
| `Feststelltaste` | Verwendung des Funkgerätes. |
| `STRG`&nbsp;+&nbsp;`Feststelltaste` | Verwendung des Langstreckenfunkgerätes. |
| `STRG`&nbsp;+&nbsp;`P` | Öffnet die Funkgerätoberfläche (Das Funkgerät musss sich im Inventar befinden.). Falls mehrere Funkgeräte mit sich geführt werden kann das Benötigte ausgewählt werden. Ebenso besteht die Möglichkeit ein Funkgerät als aktuell verwendetes zu makieren. (Dasjenige welches zum Funken verwendet werden wird.) Ebenso können Einstellungen eines anderen Funkgerätes mit der gleichen Verschlüsselung auf das verwendete übertragen werden. . |
| `STRG`&nbsp;+&nbsp;+&nbsp;`[/]` | Wechsel zwischen verfügbaren Kurzstreckenfunkgeräten. | 
| `STRG`&nbsp;+&nbsp;`Pfeiltasten: HOCH/LINKS/RECHTS ` | Rapid switching of shortwave stereo mode. |
| `NUM[1-8]` | Rapid switching of shortwave radio channels. | 
| `ALT`&nbsp;+&nbsp;`P` | To open a long range radio interface (a long range radio must be put on your back, or you should be in a vehicle in a position of a driver, shooter, or pilot assistant). If a number of radios are available – you’ll be offered to choose one. Besides, one of them can be set as active. Also it is possible to load radio settings from another radio with same encryption code. |
| `STRG`&nbsp;+&nbsp;`ALT`&nbsp;+&nbsp;`[/]` | Cycle through available long range radios. | 
| `ALT`&nbsp;+&nbsp;`Up/Left/Right Arrow` | Rapid switching of long range stereo mode. |
| `STRG`&nbsp;+&nbsp;`NUM[1-9]` | Rapid switching of long range radio channels. |
| `STRG`&nbsp;+&nbsp;`TAB` | To change the direct speech volume. You can talk: Whispering, Normal or Yelling. Does not affect the signal volume in the radio transmission. |
| `SHIFT`&nbsp;+&nbsp;`P` | To open an underwater transceiver interface (you should be wearing a rebreather). | 
| `STRG`&nbsp;+&nbsp;`~` | To talk on underwater transceiver. |
| `STRG`&nbsp;+&nbsp;`]`| Select next personal radio. |
| `STRG`&nbsp;+&nbsp;`[`| Select previous personal radio. |
| `STRG`&nbsp;+&nbsp;`ALT`&nbsp;+&nbsp;`]`| Select next long range radio. |
| `STRG`&nbsp;+&nbsp;`ALT`&nbsp;+&nbsp;`[`| Select previous long range radio. |
| `STRG`&nbsp;+&nbsp;`[←,↑,→]`| Change personal radio stereo mode. |
| `ALT`&nbsp;+&nbsp;`[←,↑,→]`| Change long range radio stereo mode. |
| `T` | Transmit on additional channel of personal radio. |
| `Y` | Transmit on additional channel of long range radio. |
| `ESC` | To exit from the radio interface. |


###Information

#####Radios

| Radio | Side | Range/Distance | 
| --- | --- | --- | --- | 
| Radio [AN/PRC-152](http://en.wikipedia.org/wiki/AN/PRC-152) (personal) | <font color="blue">BLUEFOR<font> | 30-512Mhz / 5 km |
| Рация [RF-7800S-TR](http://rf.harris.com/capabilities/tactical-radios-networking/rf-7800s-tr.asp) (rifleman) | <font color="blue">BLUEFOR<font> | 30-512Mhz / 2 км | 
| Radio [RT-1523G (ASIP)](http://en.wikipedia.org/wiki/SINCGARS#Models) (long range) | <font color="blue">BLUEFOR<font> | 30-87Mhz / 20 km (30 for inbuilt) | 
| Radio [AN/ARC-210](http://www.rockwellcollins.com/~/media/Files/Unsecure/Products/Product%20Brochures/Communcation%20and%20Networks/Communication%20Radios/ARC-210%20Integrated%20Comm%20Systems%20white%20paper.aspx) (airborne) | <font color="blue">BLUEFOR<font> | 30-87Mhz / 40 km |
| Radio [AN/PRC-154](http://www.gdc4s.com/anprc-154a-rifleman-radio.html) (rifleman) | <font color="blue">INDEPENDENT<font> | 30-512Mhz / 2 km | 
| Radio [AN/PRC148-JEM](https://www.thalescomminc.com/ground/anprc148-jem.asp) (personal) | <font color="green">INDEPENDENT</font> | 30-512Mhz / 5 km | 
| Radio [AN/PRC-155](http://www.gdc4s.com/anprc-155-2-channel-manpack.html) (long range)| <font color="green">INDEPENDENT</font> | 30-87Mhz / 20 km (30 for inbuilt) | 
| Radio [AN/ARC-164](https://ru.wikipedia.org/wiki/AN/ARC-164) (airborne) |  <font color="green">INDEPENDENT</font> | 30-87Mhz / 40 km |
| Radio [FADAK](http://www.military.com/video/forces/military-foreign-forces/iran-unveils-3-new-military-products/2363087176001/) (personal) | <font color="red">OPFOR</font> | 30-512Mhz / 5 km | 
| Radio [PNR-1000A](http://elbitsystems.com/Elbitmain/files/Tadiran%2520PNR1000A_2012.pdf)  (rifleman) | <font color="blue">OPFOR<font> | 30-512Mhz / 2 km | 
| Radio [MR3000](http://www.railce.com/cw/casc/rohde/m3tr.htm) (long range) | <font color="red">OPFOR</font> | 30-87Mhz / 20 km (30 for inbuilt) | 
| Radio [MR6000L](http://www.rohde-schwarz.com/en/product/mr6000l-productstartpage_63493-9143.html) (airborne) | <font color="red">OPFOR</font> | 30-87Mhz / 40 km | 
| Underwater transceiver | All | 32-41kHz / 70-300 m. (depending on waves) | 

> Not all radios presented here, also next airborne 40km radios are supported : "AN/ARC-201", "AN-ARC-164", "MR6000L"

> Personal and long range radios of one faction support a single protocol, therefore they can communicate with each other. If the transmission is carried out from the personal one – the sound will be high-frequency. In the case of long range transmission – it’ll be low-frequency.

> Radio propagation is affected by terrain. Worst case - if you right behind the steep hill. If you go from hill edge into direction from transmitter you will get better signal propagation. Best case - line of sight.

> Personal and long range radios support transmitting and receiving on two channels simultaneously. By pressing "Setup additional channel" switch on radio current channel will be marked as additional. After switching to another channel you will hear both - active and additional channels. It is possible to setup different stereo modes for active and additional channels. Use 'T' to transmit on additional channel of personal radio, 'Y' - for long range radio.

#####Radios distribution
* By default, a long range radio is given to squad leaders. If a player is wearing a backpack – he will automatically put it on the ground.

* A short range radio is given to players who have `ItemRadio` in the inventory. Radio distribution may take a few seconds (follow messages in the center of the screen).

#####Vehicles
* A long range radio is available for a driver, commander, shooter, and pilot assistant. Not all the vehicles support built-in radios.

* Each vehicle slot has its own radio, which must be configured separately. If you plan to change the position in a vehicle – configure the radio in all the slots beforehand (for instance, on a driver or shooter slot).

* Vehicles are classified into open and closed (isolated). If you are in an isolated vehicle, you will almost not hear voices from outside (and vice versa). However, if you turn out of the vehicle, you will hear voices both from inside and outside.

#####Radio interception

* Radio can be taken from killed players, and given to each other. Thus, they retain all the settings (channels, frequency, volume).

> It is recommended to take radios opening the inventory at the place where it is (so that it is not lost because of the game bugs).

* In vehicles radio settings are also saved.
* By default, radios of each faction use their own encryption codes, so you will not hear enemy talks, even setting the enemy’s frequency. To listen to the enemy’s net (and talk on the air) - it’s necessary by any means to capture an enemy radio station. 

> To listen to an enemy’s long range radio (backpack) it is recommended to be in your own vehicle. In this case, you will be able to listen to the enemy’s net using a backpack and transmit broadcast to your allies using the radio in the vehicle as the active one.

#####Divers
* You can not talk underwater (even wearing a diving suit). However, at close distance your companion can hear some indistinct speech (exception - if you are underwater in an isolated vehicle).
* Being underwater, you can faintly hear muffled voices on land.
* Use an underwater transceiver for communication among divers.
* You can not use radio communication underwater (neither to talk nor to hear). If you want to pass some message on land - surface. Exception - submarine in the periscope depth (divers can use a long range radio there).

#####Plugin operation modes
The plugin supports two operation modes - **serious** and **lightweight modes**.

* **Lightweight mode** — is a default mode. It is designed mainly for cooperative games. Its special feature is that using the plugin players can hear the dead, users not playing, users playing on a different server and users playing without the plugin avoiding the radio (just like with TeamSpeak). This makes games against people less convenient, but allows your friend to easily find out where you play, what's your frequency, etc. Naturally, those who play on the same server with activated addons and plugins will hear each other according to "radio laws": taking into account the radio frequency and distance.

* **Serious mode** — designed for games, where players act against other players. To enable it, you need to create a TeamSpeak channel called `TaskForceRadio` (password – `123`). Players must enable the radio plugin, go to the server and plan the mission joining parties’ channels. At the start of the mission in a few seconds players will be directed to `TaskForceRadio` channel. In this case, players will hear only live players with the enabled plugin playing on the same server. Dead players, in turn, can communicate with each other. In case of a dead player respawn - he will hear only live players again. After the game ends, the players are transferred to the channel used for planning before the mission start.

#####Solving problems
* `Pipe error 230` - most likely you’ve forgot to enable the plugin in TeamSpeak.
* In TS the plugin is red and not loaded - most likely you will have to update TeamSpeak.
* Try to reaload plugin.
* `Caps Lock` actions aren’t working - perhaps because of gaming keyboards, where `Caps Lock` code is different. Try to change the active keys (by editing the `userconfig`).
* If due to an error or something else you cannot hear other players any more, even outside the game, open `Setup 3D Sound` in TeamSpeak and click `Center All`.
* To eliminate possible errors with the plugin, developers may need the TeamSpeak log. To copy it, select `Tools -> Client Log`, select all the checkboxes above and, selecting all the text by `CTRL A`, copy it to the clipboard.
* If TeamSpeak stops working (Heaven forbid!) using the plugin - it shows a window with a description where you can find a dump (the path to the file). I would be very grateful to receive this file.

#####To TeamSpeak servers admins
To be on the safe side, reduce the level of flood protection: `Right-click on the server> Edit Virtual Server> More> Anti Flood`, set 30, 300, 3000 values (top to bottom).


#####To Developers
If this implementation ever becomes popular, it’d be great to avoid piles of incompatible forks. For this reason, if you’d like to contribute to the project, contact me - it is very likely that your implementations will be merged to the main branch. Looking forward to your Pull Requests :)

#####Many Thanks to
* [Task Force Arrowhead](http://forum.task-force.ru/) squad for testing, support, patience and all the help.
* [MTF](http://forum.task-force.ru/index.php?action=profile;u=7) ([varzin](https://github.com/varzin)) for the help with graphics and documentation.
* [Hardckor ](http://forum.task-force.ru/index.php?action=profile;u=14) for the help with graphics.
* [Shogun](http://forum.task-force.ru/index.php?action=profile;u=13) for the help with graphics.
* [Blender](http://arma3.ru/forums/index.php/user/41-blender/) for the fonts.
* [vinniefalco](https://github.com/vinniefalco) for [DSP Filter](https://github.com/vinniefalco/DSPFilters).
* [WOG](http://wogames.info/) and [TRUE](http://wogames.info/profile/TRUE/) personally for the help in testing.
* [Music DSP Collection](https://github.com/music-dsp-collection) for the compressor.
* [Avi](http://arma3.ru/forums/index.php/user/715-avi/) for the code review.
* [andrey-zakharov](https://github.com/andrey-zakharov) ([Vaulter](http://arma3.ru/forums/index.php/user/1328-vaulter/)) for the help in development.
* Dina for translating.
* [Zealot](http://forums.bistudio.com/member.php?125460-zealot111) for the help in development and useful scripts.
* [NouberNou](http://forums.bistudio.com/member.php?56560-NouberNou) for advice and competition.
* [Megagoth1702](http://forums.unitedoperations.net/index.php/user/2271-megagoth1702/) for its old job of emulating the radio sound.
* [Naught](http://forums.unitedoperations.net/index.php/user/6555-naught/) for code review.
* [Andy230](http://forums.bistudio.com/member.php?100692-Andy230) for translating.
* [L-H](http://forums.bistudio.com/member.php?87524-LordHeart) for code changes.
* [NorX_Aengell](http://forums.bistudio.com/member.php?99450-NorX_Aengell) for French translation.
* [lukrop](http://forums.bistudio.com/member.php?78022-lukrop) for code changes.
* [nikolauska](http://forums.bistudio.com/member.php?75014-nikolauska) ([GitHub](https://github.com/nikolauska)) for sqf code improvements.
* [Kavinsky](https://github.com/kavinsky) for AN/PRC-154 and RF-7800S-TR and other radios.
* [JonBons](http://forums.bistudio.com/member.php?81374-JonBons) for code changes.
* [ramius86](https://github.com/ramius86) for Italian translation.
* KK for [tutorials](http://killzonekid.com/arma-scripting-tutorials-float-to-string-position-to-string/)
* [Krypto202](http://www.armaholic.com/users.php?m=details&id=45906&u=kripto202) for sounds.
* [pastor399](http://forums.bistudio.com/member.php?128853-pastor399) for backpacks model and textures.
* [J0nes](http://forums.bistudio.com/member.php?96513-J0nes) for help with models.
* [Raspu86](http://forums.bistudio.com/member.php?132083-Raspu86) for backpacks models.
* [Gandi](http://forums.bistudio.com/member.php?111588-Gandi) for textures
* [Pixinger] (https://github.com/Pixinger) for help with Zeus.
* [whoozle] (https://github.com/whoozle) for sound engine and help.
* [MastersDisaster] (https://www.freesound.org/people/MastersDisaster/) for [Rotator switch sound] (https://www.freesound.org/people/MastersDisaster/sounds/218115/)
* [CptDavo](http://forums.bistudio.com/member.php?75211-CptDavo) for help with textures.
* [KoffeinFlummi](https://github.com/KoffeinFlummi) for help with code.
* [R.m.K Gandi](http://steamcommunity.com/profiles/76561197984744647/) for backpack textures.
* [Pomigit](http://forums.bistudio.com/member.php?97133-pomigit) for texture patterns.
* [Priestylive](https://plus.google.com/u/0/113553519889377947218/posts) for BWMOD textures.
* RHS developers for help in integration.
* Everyone user (especially who report bugs).
* Sorry guys if I’ve forgot someone by chance.

# Pla de Sostenibilitat Integral: Coworking Mataró

## Fase 1: Diagnòstic i Auditoria (Checklist)

La infraestructura actual té tres "punts negres" crítics:
* **20 PCs de sobretaula (2018):** Tenen discs HDD (lents i consumeixen més), només 4GB de RAM (insuficient, provoca que el processador treballi al 100%) i problemes de sobreescalfament (més despesa en climatització).
* **1 Servidor físic:** Sobredimensionat i encès 24/7 (malbaratament energètic massiu).
* **Magatzem:** Monitors i cables vells sense inventariar (residus electrònics i capital immobilitzat).

### Proposta de Checklist d'Auditoria (Lliurable 1)

| ID Equip | Tipus / Model | Estat Tècnic | Impacte Ambiental / Punts Negres | Valoració (1-5) | Acció Circular Proposta |
| :--- | :--- | :--- | :--- | :---: | :--- |
| **01 a 20** | 20 PCs Sobretaula (2018) | **Dolent.** Obsolescència funcional per falta de RAM (4GB) i lentitud (HDD). | **Alt.** El sobreescalfament augmenta el consum elèctric i redueix la vida útil. | 2/5 | **Revitalització (Upgrade):** Canvi a SSD, ampliació a 8GB/16GB de RAM i neteja de ventiladors. |
| **SRV-01** | Servidor Físic Central | **Bo (Tècnicament).** Sobredimensionat per a les necessitats reals. | **Molt Alt.** Consum ininterromput 24/7 d'energia base. | 1/5 | **Migració / Virtualització:** Moure serveis al núvol verd o programar apagats automàtics nocturns. |
| **MAG-01** | Magatzem de residus | **Desconegut.** Material acumulat i sense inventariar. | **Moderat-Alt.** Risc de contaminació per components RAEE si no es reciclen. | 1/5 | **Inventari i Triatge:** Separar el que funciona per a reutilitzar i reciclar la resta via punt blau. |

---

## Fase 2: Solucions - Hardware Circular (Catàleg)

En lloc de comprar equips nous (que generaria petjada de carboni per fabricació), prioritzarem la **"Revitalització"**.

### Catàleg de Hardware Recomanat (Lliurable 2)

1. **Unitats d'emmagatzematge: SSD Crucial/Kingston (SATA 2.5")**
   * *Justificació:* Substituir els vells HDD per SSD redueix el consum elèctric del disc en un 60-80%, elimina la generació de calor i multiplica per 5 la velocitat de l'equip, allargant la seva vida útil **3 o 4 anys més**.
2. **Memòria RAM: Mòduls DDR4 4GB/8GB (Crucial o similars)**
   * *Justificació:* Ampliar els equips a un minim de 8GB o 16GB de RAM evita que el processador s'estressi (reduint el sobreescalfament) i permet treballar amb programari actual sense necessitat de canviar la placa base ni el xassís.
3. **Components nous (si cal substituir alguna pantalla o perifèric):**
   * *Criteris de selecció:* Només es adquiriran productes amb certificació **Energy Star** (eficiència energètica garantida) i **EPEAT Gold/Silver** (dissenyats per ser desmuntats, reparats i reciclats fàcilment).

---

## Fase 3: Guia de Bones Pràctiques Digitals (Infografia)

Aquest contingut s'ha d'estructurar en format d'**infografia visual** per als usuaris del Coworking:

* **Combat el "Dark Data" (Dades fosques):**
  * Neteja el teu correu electrònic (elimina spam i fils antics).
  * No acumulis còpies de seguretat duplicades al núvol. Sabies que emmagatzemar dades inútils als servidors consumeix tanta energia com un país sencer?
* **Configuració de l'Entorn de Treball (S.O.):**
  * Activa el "Mode Estalvi d'Energia" a Windows/Linux/macOS.
  * Configura la pantalla perquè s'apagui després de 5 minuts d'inactivitat (evita els salvapantalles animats, consumeixen més).
* **🔌 Protocol de tancament i control remot:**
  * **Apagada Total:** En marxar del coworking, desconnecta completament l'equip (evita el mode *Stand-by*).
  * **Tancament Remot:** Implementació d'un sistema automatitzat que apagui de manera remota tots els equips que hagin quedat encesos a partir de les 21:00h.

---

## Fase 4: El Pla de Sostenibilitat Integral (Document Final)

Aquest és el resum de l'estratègia que recull tot el projecte i l'alinea amb els criteris d'avaluació oficials:

### 1. Full de ruta de millora
* **Curt termini (1-3 mesos):** Neteja física dels 20 PCs (ventiladors), inventari del magatzem, instal·lació de programari de control d'apagada automàtica i llançament de la infografia digital.
* **Mig termini (3-6 mesos):** Compra i instal·lació dels kits d'ampliació (SSD + RAM) per als 20 PCs. Migració del servidor físic cap a una solució de núvol híbrid (reduint l'encesa a oficines).
* **Llarg termini (1 any):** Auditoria de seguiment per comprovar la reducció del 20% de la factura elèctrica i sol·licitud de la certificació ISO 14001 o el segell EPEAT d'oficina verda.

### 2. Protocol de gestió de residus (RAEE)
* **Regla de les 3R aplicada a la informàtica:**
  1. *Reduir:* Allargar la vida útil dels PCs actuals gràcies al pla de revitalització.
  2. *Reutilitzar:* Els monitors trobats al magatzem que funcionin es posaran a disposició dels usuaris com a segona pantalla (millorant la seva ergonomia i productivitat).
  3. *Reciclar:* El material obsolet o trencat (com els vells discs HDD danyats o cables fets malbé) s'entregarà a un gestor de residus autoritzat **RAEE** (Residus d'Aparells Elèctrics i Electrònics) de Mataró per recuperar els seus materials preciosos (coure, or, terres rares).

### 3. Càlcul de KPIs (Mètriques)

* **PUE (Power Usage Effectiveness - Eficiència de Potència del Servidor):**
  $$PUE = \frac{\text{Energia total consumida per la infraestructura informàtica}}{\text{Energia consumida exclusivament pels equips de càlcul}}$$
  * *Objectiu:* Actualment el PUE és molt alt (ineficient) perquè el servidor està sobredimensionat i genera calor residual constant. Amb la virtualització/núvol, volem acostar el PUE a un valor òptim d'**1.2**.
* **Taxa de Reutilització de Hardware:**
  $$\text{Taxa de Reutilització} = \left( \frac{\text{Equips actualitzats o reaprofitats}}{\text{Total d'equips inventariats}} \right) \times 100$$
  * *Càlcul estimat:* Si actualitzem els 20 PCs i reutilitzem el 50% dels monitors del magatzem, aconseguirem una taxa superior al **85%**, minimitzant radicalment la compra de hardware nou.

### 4. Contribució als ODS (Objectius de Desenvolupament Sostenible)
* **ODS 7 (Energia assequible i no contaminant):** Reducció de la factura elèctrica i optimització del consum del servidor 24/7.
* **ODS 12 (Producció i consum responsables):** Aplicació de l'economia circular mitjançant la reparació, reutilització de pantalles i reciclatge controlat RAEE.
* **ODS 13 (Acció climàtica):** Reducció de la petjada de carboni digital en disminuir el consum energètic de la infraestructura del Coworking.

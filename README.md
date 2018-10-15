# Maskinlæringskurs med Norkart
### Fra buzz til virkelighet
Maskinlæringskurs, Tensorflow.js

## Pass på å ha installert:
* _Windowsbrukere:_ Windos Subsystems for Linux (WLS)
    [(guide)](https://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/)
* Node (versjon 8.9 eller nyere)
* Yarn
  ```
  npm install -g yarn
  ```

## For å kjøre koden:

Clone repositoriet, gå inn i mappen, installer dependencies og start prosjektet med følgende kommandoer i terminalen:

```bash
$ git clone https://github.com/Norkart/ML_kurs.git
$ cd ML_kurs
$ yarn
$ yarn watch

```

## Oppgaven - tolke håndskrevne tall

Dere har hett fått en del kode som skal hjelpe dere med å lage en algoritme som kan tolke håndskrevne tall.

Modellen vil regne ut nøyaktighet over et sett med 1000 eksempler, og plotte nøykatigheten til modellen underveis.

## Datasett

Datasettet dere skal trene på er et klassisk datasett for maskinlæring - MNIST - en samling av håndskrevne tall. Koden for innlesing av datasettet er allerede skrevet, slik at bildene blir konverter til `Tensor`s.

## Ordliste

- Epoch: antall ganger modellen får "se" hele datasettet
- Loss: Summert feil for hvert eksempel i trening/valideringssett
- Strides: Antall steg(piksler) et filter flytter seg for hver gang den regner ut en aktiveringsverdi
- Softmax classifier: et lag som konverterer score for hver klasse gitt av nettverket til sannsynlighets-verdier

## Link til slides
Her kan dere se [slides](https://docs.google.com/presentation/d/1M-QzLvP5velcT9ld6aiEtBEF6W-8LovFHFMhw6cxZWs/edit?usp=sharing) fra presentasjonen.
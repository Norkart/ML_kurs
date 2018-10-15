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

Dere har hett fått en del kode som skal hjelpe dere med å lage en algoritme som kan tolke håndskrevne tall

This model will compute accuracy over 1000 random test set examples every 5
steps, plotting loss and accuracy as the model is training. Training time can
be reduced by computing accuracy over fewer examples less often.

## Datasett
Datasettet dere skal trene på er et klassisk datasett for maskinlæring - MNIST, en samling av håndskrevne tall. Koden er allerede satt

Note: currently the entire dataset of MNIST images is stored in a PNG image we have
sprited, and the code in `data.js` is responsible for converting it into `Tensor`s.

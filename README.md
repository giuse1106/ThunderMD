# ThunderMD - WhatsApp Bot

ThunderMD è un bot per WhatsApp costruito con la libreria **Baileys**. Questo bot ti consente di interagire automaticamente con gli utenti su WhatsApp utilizzando WhatsApp Web. Segui questa guida per installare il bot su Termux (Android) o su una macchina Linux.

## Prerequisiti

Prima di iniziare, assicurati di avere i seguenti requisiti:

- **Termux** (per Android) o **Terminale Linux** (Ubuntu, Debian, etc.)
- **Node.js** (versione 16.x o superiore)
- **npm** (che viene installato automaticamente con Node.js)
- **git** (per clonare il repository)
- Una connessione a Internet attiva per connetterti a WhatsApp Web

### Installare Termux (solo su Android)

Se stai utilizzando Termux su Android, puoi scaricarlo dal [Google Play Store](https://play.google.com/store/apps/details?id=com.termux) o da [F-Droid](https://f-droid.org/packages/com.termux/).

## Clonare il Repository [(Metodo Termux 2025)]

1. Apri **Termux** e vai nella directory in cui vuoi clonare il repository.
2. Clona il repository **ThunderMD** utilizzando **git**:

   ```bash
   git clone https://github.com/giuse1106/ThunderMD.git
   cd ThunderMD
   ```

  ```bash
  pkg update
  pkg upgrade
  pkg install nodejs
  pkg install git
```
Installa le dipendeze nodejs
```
  npm install
```

Avvia il bot:

```
  npm start
```

## Clonare il repository [(metodo Terminale Linux 2025)]

```
  git clone https://github.com/giuse1106/ThunderMD.git
  cd ThunderMD
```

Installa le nodejs:
```
sudo apt update
sudo apt install nodejs npm git
```

Installa le dipendenze:
```
npm install
```

Avvia il bot

```
npm start
```

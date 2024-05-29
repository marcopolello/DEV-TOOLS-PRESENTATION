# WORKSHOP DEV TOOLS:

![icon](codeium.svg)

Codeium è una piattaforma di sviluppo integrato (IDE) che fornisce funzionalità avanzate di assistenza ai programmatori. È stato creato per aiutare gli sviluppatori a scrivere codice più velocemente, con meno errori e in modo più efficiente.

## Strumento per sviluppatori

Codeium è un'estensione di IDE che può essere integrata con una vasta gamma di editor di codice popolari, come VS Code, Jetbrains, Neovim, Jupyter Notebooks e molti altri. Offre funzionalità come completamento automatico del codice, ricerca di codice, assistenza alla documentazione e chat-based assistant.

## Installazione e Utilizzo come estensione VsCode

https://codeium.com/vscode_tutorial

## Esempi Utilizzo

#### dal codice
![example1](code1.png)

#### dai commenti

![example2](code2.png)

### suggerimenti alternativi 
![suggestion1](suggestion_1.png)

Suggerimento: Come scelta rapida per accettare una suggerimento, puoi utilizzare ⌥ + ] e ⌥ + [ (su MacOSX) o Alt + ] e Alt + [ (su Windows / Linux) per il successivo e il precedente rispettivamente.

![suggestion2](suggestion_2.png)

ecco un esempio dopo il click di suggerimento successivo: 

![suggestion3](suggestion_3.png)


Oltre all'utilizzo su vscode è possibile integrarlo su Vim o NeoVim per i più PRO

🌐 Fonti
[Codeium.com](https://codeium.com/)
[Github Codeium](https://github.com/Exafunction/codeium.vim)
[Installazione e Utilizzo](https://codeium.com/vscode_tutorial)

🌐 Corso Prompt engineering
[Prompt Eng Per Developer](https://www.freecodecamp.org/news/prompt-engineering-for-web-developers/)

******************************
##### fine primo argomento
******************************

# Estensione Jam per Browser 🗒️

Panoramica dell'estensione Jam per browser, il suo scopo e i suoi benefici.

## Installazione

#### Passo 1: Installa l'estensione Jam
Scarica l'estensione per browser (cliccando sul grosso pulsante su jam.dev)
Ricorda di aggiungere l'estensione alla barra del browser per una più veloce accessibilità!

![step1](step1-1.gif)

Quando richiesto, inserisci la tua email per creare il tuo account.
Ora sei pronto per individuare il tuo primo bug con Jam.

#### Passo 2: Cattura il tuo primo bug con Jam
Clicca sull'icona di Jam nel tuo browser.

![step2](step2.webp)

Scegli il metodo di registrazione dello schermo - screenshot, video o replay istantaneo (suggerimento: non devi riprodurre il bug con il replay istantaneo!).
Redige il tuo report di bug e premi "Crea"!

![step2.1](step2.1.gif)

#### Passo 3: Controlla il tuo primo Jam!
Il tuo Jam appena creato si aprirà automaticamente in una nuova scheda. Vai a controllarlo!

![step3](step3.avif)

Nel Jam, vedrai:
- Metadati: URL, timestamp, paese, dispositivo, browser, informazioni sul sistema operativo e velocità di rete
- Log degli sviluppatori: console logs, richieste di rete completamente ispezionabili
- Contesto: Screenshot ritagliato e completo (se il tuo Jam serve per catturare uno screenshot)
- JamGPT: un assistente AI che fornisce suggerimenti agli ingegneri su come risolvere i bug
- Integrazioni dell'app: invia il tuo Jam al sistema di ticketing (come Jira, Asana, ecc.)
- Selettore dello spazio di lavoro: organizza i tuoi Jam nei workspace di squadra
- Impostazioni di condivisione e accesso
Il tuo Jam viene salvato automaticamente (e lo troverai sempre nel dashboard di Jam su jam.dev) e il link non scadrà mai (a meno che tu non elimini esplicitamente il Jam).
Per condividere il tuo Jam, copia semplicemente il link e invialo ai tuoi colleghi di squadra. Oppure, puoi condividerlo con i tuoi colleghi tramite email cliccando sul pulsante "Invita".
I tuoi colleghi non avranno bisogno di creare un account per visualizzarlo. (A meno che tu non cambi le impostazioni di accesso del Jam per richiedere il login per la visualizzazione).
Riceverai una notifica quando qualcuno visualizza il tuo Jam per la prima volta!

#### Passo 4: Invita i tuoi colleghi
Aiuta i tuoi colleghi a segnalare i bug più velocemente, con tutti i dettagli tecnici necessari inclusi automaticamente. Chiunque può creare uno spazio di lavoro di squadra in Jam e invitare il proprio team a unirsi.
Per creare uno spazio di lavoro di squadra in Jam, accedi al dashboard su jam.dev e clicca su "Invita colleghi" (o il pulsante potrebbe dire "Aggiungi squadra").

![step4](step4.avif)

#### Passo 5: Collega i tuoi strumenti
Puoi collegare gli strumenti che già usi a Jam in modo che si adatti perfettamente al tuo flusso di lavoro esistente.
Per vedere con quali app si integra Jam, vai alle impostazioni del tuo account o della squadra in Jam.

![step5.1](step5.gif)

Poi, puoi selezionare queste app quando crei i Jam per inviarli ai tuoi altri strumenti:

![step5.2](step5.2.avif)

E, puoi inviare i Jam esistenti ai tuoi strumenti in seguito.

🌐 Fonti
[jam.dev - Inizia | Documentazione di Jam](https://jam.dev/docs/get-started#step-1-install-the-jam-extension)
[jam.dev - Estensione browser](https://jam.dev/s)


******************************
##### fine secondo argomento
******************************

# SqlChat

![icon](sqlchat.webp)

SQL Chat è un client SQL basato su chat, che utilizza il linguaggio naturale per comunicare con il database per implementare operazioni come query, modifica, aggiunta ed eliminazione del database.

![icon](sqlchat1.webp)

![icon](sqlchat2.webp)

![icon](sqlchat3.webp)

#### Why

Mentre entriamo nell'era degli Strumenti per sviluppatori 2.0, c'è un'enorme opportunità di ricostruire gli strumenti esistenti utilizzando l'interfaccia basata su chat. SQL Client non fa eccezione. Invece di navigare tra molti controlli dell'interfaccia utente, un'interfaccia basata su chat è molto più intuitiva. 

SQL Chat è costruita tramite [Next.js](https://nextjs.org/), supporta i seguenti database:

- MySQL
- PostgreSQL
- MSSQL
- TiDB Cloud

## [sqlchat.ai](https://sqlchat.ai)

### IP Whitelisting

If you use [sqlchat.ai](https://sqlchat.ai) to connect to your database, you need to add 0.0.0.0 (allow all connections)
to the database whitelist IP. Because sqlchat.AI is hosted on [Vercel](https://vercel.com/) which [uses dynamic IP](https://vercel.com/guides/how-to-allowlist-deployment-ip-address). If this is a concern, please consider the self-host option below.

### Data Privacy

See [SQL Chat Privacy Policy](https://sqlchat.ai/privacy).


## Self-host

### Docker

per uso personale, costanti da settare e comando da lanciare:

- `NEXTAUTH_SECRET`
- `OPENAI_API_KEY`

```bash
docker run --name sqlchat --platform linux/amd64 --env NEXTAUTH_SECRET="$(openssl rand -hex 5)" --env OPENAI_API_KEY=<<YOUR OPENAI KEY>> -p 3000:3000 --hostname localhost sqlchat/sqlchat
```

- Passa una stringa arbitraria a NEXTAUTH_SECRET altrimenti next-auth andrà in errore
- se chatti con il database nello stesso host, serve usare `host.docker.internal` come host nel database connection setting.

<img src="https://raw.githubusercontent.com/sqlchat/sqlchat/main/docs/docker-connection-setting.webp" />

## Startup options

### OpenAI related

- `OPENAI_API_KEY`: OpenAI API key. Si può creare a prendere da qua: [link openAI](https://platform.openai.com/api-keys).

- `OPENAI_API_ENDPOINT`: OpenAI API endpoint. Defaults to `https://api.openai.com`.

- `NEXT_PUBLIC_ALLOW_SELF_OPENAI_KEY`: settare a  `true` per permettere agli utenti di portare la loro chiave openAI personale.

### Database related

- `NEXT_PUBLIC_USE_DATABASE`: settare a `true` per inizializzare SQLchat con database. questo abiliterò le seguenti features:
  1. Account system.
  1. Applicazione della quota per utente.
  1. Pagamento.
  1. Raccolta dei dati di utilizzo.
- `DATABASE_URL`: Applicabile se `NEXT_PUBLIC_USE_DATABASE` è `true`. 
Stringa di connessione Postgres per archiviare i dati. esempio `postgresql://postgres:YOUR_PASSWORD@localhost:5432/sqlchat?schema=sqlchat`.

## Local Development

1. Installazione dipendenze

   ```bash
   pnpm i
   ```

1. Generare Prisma client

   ```bash
   pnpm prisma generate
   ```

1. Fare una copia del file variabili d'ambiente:

   ```bash
   cp .env.usedb .env
   ```

1. Aggiungere la tua [API key](https://platform.openai.com/account/api-keys) and OpenAI API Endpoint(optional) al nuovo fiule creato .env.

### Setup database

1. Avvia un'istanza di Postgres. Per Mac, puoi usare [StackbBricks](https://stackbricks.app/), [DBngin](https://dbngin.com/) o [Postgres.app](https://postgresapp.com/).

1. Creare un database:

   ```sql
   CREATE DATABASE sqlchat;
   ```

   Nel `.env` file, assegnare la stringa di connessione alla variabile di ambiente `DATABASE_URL` e `DATABASE_DIRECT_URL`. [Questo articolo](https://www.prisma.io/docs/data-platform/data-proxy/prisma-cli-with-data-proxy#set-a-direct-database-connection-url-in-your-prisma-schema) spiega perché abbiamo bisogno di due URL.

1. Set up database schema

   ```bash
   pnpm prisma migrate dev
   ```

1. (Optional) Seed data

   ```bash
   pnpm prisma db seed
   ```

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=sqlchat/sqlchat&type=Date)](https://star-history.com/#sqlchat/sqlchat&Date)


## Common Error Message

<details><summary>Iscriviti per ottenere una quota gratuita</summary>
<p>

Guarda [questo issue](https://github.com/sqlchat/sqlchat/issues/141).

</p>
</details>

<details><summary>Hai superato la quota attuale, controlla il tuo piano e i dettagli di fatturazione</summary>
<p>

![openai quota](https://raw.githubusercontent.com/sqlchat/sqlchat/main/public/error-exceed-openai-quota.webp)

La tua chiave OpenAI ha esaurito la quota. Per favore controlla il tuo [OpenAI account](https://platform.openai.com/account/api-keys).

</p>
</details>

<details><summary>Impossibile richiedere il messaggio, controlla la tua rete</summary>
<p>

![network error](https://raw.githubusercontent.com/sqlchat/sqlchat/main/public/error-network.webp)

Assicurati di disporre di una connessione di rete stabile che possa accedere all'endpoint API OpenAI.

```bash
ping api.openai.com
```

Se non riesci ad accedere all'endpoint API OpenAI, puoi provare a impostare `OPENAI_API_ENDPOINT` nell'interfaccia utente o nella variabile di ambiente.

</p>
</details>

## Alternative a pagamento (ma con più feature di SQL chat)

[datalang.io](https://datalang.io/)
[askyourdatabase](https://www.askyourdatabase.com/)

******************************
##### fine terzo argomento
******************************

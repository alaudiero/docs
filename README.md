# Welcome 😄

Un caloroso benvenuto a tutte e tutti 💪

In questa fase preliminare prepareremo gli account ed installeremo un po' di software necessario ad affrontare il corso, partendo dall'IDE per programmare al software per comunicare durante queste settimane insieme.

## Servizi

### Zoom

Le lezioni verranno effettuate principalmente con Zoom, scaricabile [qui](http://zoom.us/).

### Discord

Per le comunicazioni in tempo reale, sia in testo che in video call, useremo [Discord](https://discord.com/). Dovreste aver ricevuto via mail un invito per registrarvi al server del corso. Nel frattempo, potete scegliere se installare il [client per desktop](https://discord.com/download) o usare la version web.

### Github

Per gestire i sorgenti dei nostri progetti useremo Github. Se non avete ancora un account, registratevi [qui](https://github.com/). Una volta che avrete un account verrete aggiunti all'_organization_ del corso e potrete aggere ai repository privati.

## Software

### JetBrains Toolbox

La prima applicazione che installeremo è JetBrains Toolbox che trovate [qui](https://www.jetbrains.com/toolbox-app/). Toolbox ci consentirà di installare e far convivere "senza stress" alcuni dei programmi di cui avremo bisogno durante il corso e nella nostra carriera futura.

Una volta installato e avviato Toolbox, avremo qualcosa del genere:

![image](https://user-images.githubusercontent.com/19003/104443194-630a3200-5596-11eb-97c0-20a9b08df1b1.png)

### Android Studio

Scrollando la lista di applicazioni disponibili, possiamo installare Android Studio. Il menu ci proporrà varie versioni:

* _Canary_ è la versione in sviluppo attivo. Avremo la possibilità di provare le prossime funzionalità in anteprima, ma dobbiamo aspettarci crash e bug mentre lavoriamo.
* _Beta_ contiene le funzionalità che qualche settimana fa erano nella Canary. I bug più grossi sono probabilmente stati sistemati, ma possiamo aspettarci ancora qualche piccolo _singhiozzo_ di tanto in tanto.
* _Stable_ è la versione un po' vecchiotta, ma che ha avuto più cure nel tempo, quindi possiamo aspettarci pochi bug e un po' più di stabilità.

![image](https://user-images.githubusercontent.com/19003/104459250-c7d08700-55ac-11eb-821b-afa84ce6b686.png)

Per questa nostra avventura, la versions **Stable** andrà benissimo 😄

Una volta avviato Android Studio, possiamo iniziare con la configurazione:

Scegliamo **Standard**

![1](https://user-images.githubusercontent.com/98166/104752899-2afa1f00-574f-11eb-8657-adef242558b7.png)

Nella schermata successiva scegliamo il tema che preferiamo:

![2](https://user-images.githubusercontent.com/98166/104752902-2afa1f00-574f-11eb-98ef-4a51213ad6b5.png)

Possiamo completare la configurazione e attende l'installazione dei componenti:

![3](https://user-images.githubusercontent.com/98166/104752904-2b92b580-574f-11eb-85f8-9a3cd0608d0a.png)
![4](https://user-images.githubusercontent.com/98166/104752906-2c2b4c00-574f-11eb-970d-24ab35113878.png)
![5](https://user-images.githubusercontent.com/98166/104752908-2c2b4c00-574f-11eb-8da6-b06187abd3b5.png)

#### Plugin Utili
Android Studio fornisce diversi plugin che consentono di semplificare la vita dello sviluppatore. Per procedere all'installazione di un plugin bisogna seguire i seguenti step:

1. Aprire Android studio
1. Cliccare sulla voce "File" situata in alto a sinistra
1. Cliccare sulla voce "Settings"
1. Cliccare sulla voce "Plugins" e selezionare la tab "Marketplace"

Di seguito vengono proposti una serie di plugin utili:

- Rainbow Bracket: consente di associare un colore alle perentesi in modo tale da evitare errori dovuti alla mancata chiusura di una parentesi.
- Kotlin Fill Class: consente l'autocompletamento dei parametri di una classe (dopo che questa è stata definita).
- Presentation Assistant: consente di mostrare a video i tasti che vengono premuti nell' IDE.

## Come eseguire un'APP
Per eseguire l'app che verrà sviluppata durante il corso è possibile scegliere se
* usare un device fisico collegato al pc
* usare un device emulato da Android Studio

### Device Fisico
Nel caso in cui si voglia usare un device fisico bisognerà attivare la modalità sviluppatore sul proprio device.In questo caso è fortemente consigliato scaricare e installare il software gratuito vysor (reperibile al sito https://www.vysor.io/download/?return=https%3A%2F%2Fwww.vysor.io%2F).
Questo software consente di fare il mirroring dello schermo del proprio device fisico, in modo tale che  anche gli altri partecipanti possano vedere l'app in esecuzione.

***N.B. Usando vysor viene mostrato a video lo schermo del vostro smartphone e, di conseguenza, gli altri vedranno tutto quello che accade sul vostro smartphone (notifiche di messaggi, notifiche di email, chiamate in arrivo, etc.). Per tutelare la vostra privacy si consiglia di mettere lo smartphone in modalità Aereo in modo tale da non
ricevere messaggi o chiamate private.***

### Device Emulato da Android Studio
Se vogliamo utilizzare un device simulato dobbiamo:
1. Aprire l'IDE Android Studio.
2. Aprire un progetto già esistente o crearne uno nuovo
3. Cliccare sul menù "No Devices" e cliccare sulla voce "AVD Manager"

![1](https://user-images.githubusercontent.com/53529795/104844510-ef875e00-58d0-11eb-9432-e633fa938304.PNG)

4. Cliccare su "Create Virtual Device"

![2](https://user-images.githubusercontent.com/53529795/104844511-f2824e80-58d0-11eb-81f5-c1b7a3537701.PNG)

5. Selezionare il tipo di device che si vuole simulare. Nel nostro caso scegliamo "Phone" e, una volta selezionato il modello,
   clicchiamo su Next
   
![3](https://user-images.githubusercontent.com/53529795/104844513-f4e4a880-58d0-11eb-8714-3ca431f7d8d0.PNG)

6. Scegliamo una "System Image" e scarichiamola cliccando sul pulsante "Download". 

![4](https://user-images.githubusercontent.com/53529795/104844514-f615d580-58d0-11eb-81c8-05cddab6343d.PNG)

![5](https://user-images.githubusercontent.com/53529795/104844516-f7470280-58d0-11eb-940f-83481b01c111.PNG)

7. Dopo aver terminato con il download clicchiamo su "Next" e, se non dobbiamo selezionare delle impostazioni avanzate, possiamo cliccare su "Finish"
![6](https://user-images.githubusercontent.com/53529795/104844517-f7df9900-58d0-11eb-9fd9-76d2f88ea550.PNG)

A questo punto il device che abbiamo creato comparirà nella lista "Your Virtual Devices".

![7](https://user-images.githubusercontent.com/53529795/104844518-f8782f80-58d0-11eb-8e2d-d7639df8202c.PNG)

Se abbiamo un solo device questo verrà selezionato in automatico da Android Studio se, invece, abbiamo più device emulati dobbiamo cliccare sul menù mostrato in figura e scegliere quale device simulato vogliamo usare.

![8](https://user-images.githubusercontent.com/53529795/104844519-f9a95c80-58d0-11eb-883a-b66d5d074804.PNG)

Una volta che abbiamo cliccato sul tasto run Android Studio farà la build dell'applicazione, manderà in esecuzione il virtual device, e installerà ed eseguirà la nostra app

![9](https://user-images.githubusercontent.com/53529795/104844508-ec8c6d80-58d0-11eb-8b3f-329fd277db31.PNG)

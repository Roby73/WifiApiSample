# WifiApiSample

# ENGLISH 
WifiApiSample show how to use the native API for WiFi of Window, with a C console application. With the application, via menus, you can view the interfaces wifi, the availables network and the profiles list of your system; you can connect and disconnect to/from a net.

Project Description
WifiApiSample show how to use the native API for WiFi of Window, with a C console application. With the application, via menus, you can view the interfaces wifi, the availables network and the profiles list of your system; you can connect and disconnect to/from a net.

Requirements
To compile the project it requires:
Windows XP SP 3, or earlier
WDK release 7600.16385.0 correctly installed

Build
Start a build enviroment (checked or free) and lanch the command:

BLD -eZ

from the directory where are the project's sources files.
In the bin/<platform> directory you can find the WiFiMan.exe application.
Executable release
The bin version contains the executable file, ready to be used in Windows XP.
Use of program
The program (sources) shows how to use the native Wifi API of windows (limited
to Windows XP features). The program, using simple menu, allows to the user to
manage some wifi aspects.
The following is a more detailed description.

When started, the program opens an handle to the wifi API server and displays
the highest version of the WLAN API that the client supports. Right values are

1 Client version for Windows XP with SP3 and Wireless LAN API for
Windows XP with SP2.

2 Client version for Windows Vista and Windows Server 2008

To continue the user must press a key, then the program show the main menu.
From here you can select 1, to go the "Interfaces" menu or 2, for the "Net
and profiles" menu.

In the "Interfaces" menu, you can list the interfaces wifi in the system and
select one of them. To exit use the 0 option.

In the "Net and profiles" menu, you can list the available nets and select one
of them, connect to the selected network and disconnect from the current network,
show all the available profile names. To exit use always the 0 option.

Credits
Roberto AGOSTINO produced (using the WDK documentation)
Italy, Rome, October 2010

==============================================================================
  
# ITALIANO
  
Descrizione del progetto
WifiAPIexample mostra come usare la API Native per Wifi di Windows con un' applicazione scritta in C. Usando una semplice interfaccia utente a menu testuali, puoi elencare le interfacce wi-fi presenti nel sistema; le reti disponibili e i nomi di tutti i profili del sistema; infine connettersi ad una rete selezionata o disconnettersi dalla rete corrente.

Requisiti
Si può compilare con la versione 7600.16385.0 del WindowsDevelopmentKit,
correttamente installata.

Compilazione dei sorgenti
Avvia un ambiente di sviluppo (checked or free) e lancia il seguente comando da
dentro la cartella con i file del progratto sopra elencati.

BLD -eZ


Nella cartella bin/<platform> dovrebbe trovarsi il programma WiFiMan.exe .
Versione eseguibile
Scaricando la versione bin, si ha già una versione del programma compilato e
pronta all'uso con Windows XP.
Uso del programma
Questo programma (in particolare i sorgenti) rappresenta un esempio di uso delle
API native Wifi di Windows (limitatamente alle caratteristiche implementate per
Windows XP). Il programma, usando semplici menu, permette all'utente di gestire
alcuni aspetti della tecnologia Wifi.

A seguire, una descrizione più dettagliata del funzionamento.

Quando avviato, il programma apre una connessione verso la parte del sistema,
a cui spetta l'interfacciamento e gestione delle periferiche wifi, e mostra la
più alta versione di WLAN API che il sistema offre. Valori restituiti possibili
sono:

1 Versione del sistema Windows XP con SP3 e Wireless LAN API for
Windows XP con SP2.

2 Versione del sistema Windows Vista e Windows Server 2008

Per continuare l'utente deve premere un tasto. Appare allora il menu principale.
Da qui si potrà accedere al menu "Interfacce", premendo 1, o al menu "Reti e
profili" premendo 2.

Dal menu "Interfacce", è possibile visionare la lista delle interfacce nel
sistema ed è possibile selezionarne una. Per uscire è sufficiente scegliere 0
dal menu.

Dal menu "Reti e profili", si possono elencare le reti disponibili e selezionarne
una, connettersi a questa rete, o disconnettersi dalla rete correntemente in uso;
infine mostrare i nomi dei profili attualente registrati. Per uscire è
sufficiente scegliere 0 dal menu.

Diritti di autore
Sviluppato da Roberto AGOSTINO (usando la documentazione acclusa al WDK)
Italia, Roma, Ottobre 2010

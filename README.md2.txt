         # PraticaS1-L4

      Esercizio: 
● Mettere in comunicazione il laptop-PT0 con IP 192.168.100.100 con il PC-PT-PC0 con IP 192.168.100.103 
● Mettere in comunicazione il laptop-PT0 con IP 192.168.100.100 con il laptop-PT2 con IP 192.168.200.100 
● Spiegare, con una relazione, cosa succede quando un dispositivo invia un pacchetto ad un altro dispositivo di 
   un'altra rete.


      answer:

 In questo Esercizio abbiamo una rete costitiuta da due sottorete collegate tra di loro attraverso un ROUTER. la prima rete  costitiuto da un Switch e tre host(due Laptop e un PC) e  la seconda rete da uno Switch e due host(un laptop e un PC).questi dispositivi communicano tra di loro tramitte indirizzo IP,che inserisce il creatore della rete andando alla scheda "Desktop"  nella finestra di configurazione clicando su "IP Configuration".
      Quando un dispositivo invia un pachetto a un altro dispositivo di un'altra rete,specifica l'indirizzo del host di cui sta mandando il pachetto; e cosi il pachetto attraverso prima il Switch della sua sottorete poi il ROUTER,il Switch della seconda sotto rete e poi guinge l'Host di cui a ricevuto l'indirizzo IP.
      Tuttavia,importante notare che per attraversare il ROUTER gli indirizzi IP Gateway devono essere configurati corettamente e il ROUTER deve essere attivato premendo su "ON" dopo la configurazione degli indrizzi IP nel caso contrario il pachetto non potra transitare attraverso il ROUTER.
      In fine per verificare se tutto funziona corettamente usiamo la comand "PRING"  clicando su un host e inserendo l'indirizzo IP del host di cui vogliamo fare la Verificazione.
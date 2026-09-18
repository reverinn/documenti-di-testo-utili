**CAPITOLO 1**: LOGICA RUDIMENTALE:
- Proposizioni Logiche & Connettivi Logici
- 4 Proprietà dei connettivi logici: scrivi le tautologie
- Quando una proposizione si dice tautologia, contraddizione o contingenza?
- [Proposizione] quando due forme proposizionali si dicono equivalenti?
- Leggi di De Morgan
- Tautologie delle implicazioni
	- A cosa è equivalente la doppia implicazione? 
	- [Proposizione] p ==> q equivale a dire? 
	- [Proposizione con Dimostrazione] p ==> q <==> (~q ==> ~p)
	- [Proposizione] ~(p ==> q)
	- [Proposizione] a cosa equivale la negazione della doppia implicazione?
- a cosa è equivalente dire che p è disgiunto esclusivamente con q ? 
- Quantificatori
	- Quando una formula si dice valida ? 
	- Universale vs Esistenziale
	- Esistenziale Unico
		- Da che equivalenza è definito?
		- Negazione di Esso
		- Quando Fallisce?
	- Che significa che una variabile è libera o vincolata?
	- Cosa è un predicato unario o uno binario ? 
	- Quantificatori ristretti, quale implica l'altro?

**CAPITOLO 2: TEORIA DEGLI INSIEMI:**
- Definizione di insieme, com'era visto inizialmente?
- Assioma di Separazione
- Assioma di Estensionalità
- Inclusione di insiemi
	- Formula
	- Dati insiemi noti h e k, che vuol dire che h è incluso in k?
	- cosa cambia se a è incluso esclusivamente in b? 
	- P(x)
		- Da cosa è composto
		- Com'è possibile che non è mai vuoto ? 
		- N-arie
	- [Teorema della doppia inclusione + Dimostrazione]
	- Operazioni Insiemistiche
		- Intersezione
		- Unione
		- Differenza Insiemistica
		- Differenza Simmetrica
		- Leggi di De Morgan
	- Operazioni Unarie
		- Unione unaria
		- Intersezione Unaria
	- Prodotto Cartesiano
	- [Proposizione] Coppia Ordinata di Kuratowski 
		- [Dimostrazione] {{a}, {a,b}} = {{c}, {c,d}} implica che a = c AND b = d
	- Cosa è una terna ordinata?

**CAPITOLO 3: CORRISPONDENZE E RELAZIONI DI EQUIVALENZA**
* Corrispondenze e Relazioni Binarie
	* quando, dati due insiemi a e b parliamo di corrispondenza ? 
	* come si dice l'insieme G?
	* come facciamo a scrivere che due elementi sono in corrispondenza mediante p?
	* Cosa indica il simbolo Corr(a,b)? 
		* Formula
		* Cosa è una relazione binaria ? 
			* relazione binaria identica & totale
	 * relazione opposta di p = (s,s,G)
	 * proprietà delle relazioni binarie [Con Formule!]
* Prodotto Relazionale
	* Definizione di Prodotto Relazionale
	* Associatività del Prodotto Relazione [Teorema con Dimostrazione]
	* idA & idB
* Applicazioni
	* cosa è un applicazione ? come la si indica ? 
	* come viene chiamato b se f(a) = b?
	* come si chiama e come viene indicato l'insieme delle applicazioni da A a B?
	* Serie di Definizioni:
		1. Immagine
		2. Costante (e funzione costante h)
		3. Restrizione & Immersione [Con L'Osservazione]
		4. Riduzione
	*  Applicazione Immagine e Anti-immagine [2 Proposizioni] 
		* Osservazione su C € P(A) e Y € P(B)
	* Composizione tra applicazioni [Proposizione + Dimostrazione]
	* Suriettività
		* definizione di applicazione iniettiva
		* [Proposizione] retrazione iniettiva
		* [Proposizione] f iniettiva sse il modulo dell'antimmagine del singleton Y € B è <= 1 [Con Dimostrazione]
		* [Proposizione] f,g iniettiva => f o g iniettiva [Con Dimostrazione]
		* [Proposizione] f o g iniettiva => f iniettiva [Con Dimostrazione]
	* Iniettività
		* definizione di applicazione suriettiva
		* [Proposizione] f suriettiva sse il modulo dell'antimmagine del singleton Y non è vuoto [Con Dimostrazione]
		* [Proposizione] negazione della definizione
		* [Proposizione] f, g suriettive => f o g suriettiva
		* [Proposizione] f o g suriettiva => g suriettiva
	* Biettività
		* definizione di applicazione biettiva
		* [Proposizione] tautologie con definizione di applicazione biettiva
		* [Corollario] f, g biettive => f o g biettive, g o f biettiva => g suriettiva e f iniettiva
	* Sezione e Retrazione
		* Definizione di Sezione
		* [Teorema] f è suriettiva sse f ha una sezione [Con Dimostrazione]
		* Definizione di Retrazione
		* [Teorema] f è iniettiva sse A è vuoto e f ha una retrazione [Con Dimostrazione]
	* Applicazioni Inverse
		* [Teorema] se f: A-->B, f ha una sezione sigma e una retrazione p, allora sigma=p è un'inversa di f e inoltre è l'unica [Con Dimostrazione]
		* Corollario: Come si indica l'inversa di f ? a cosa equivale ? 
	* Relazioni di Equivalenza
		* proprietà delle relazioni di equivalenza
		* come si indica l'insieme delle relazioni di equivalenza?
		* definizione di classe di equivalenza
		* [Teorema Fondamentale Sulle Partizioni] definizione di biezione canonica e dimostrazione che essa è biettiva
		* definizione di proiezione canonica, è suriettiva/iniettiva o biettiva?
		* nucleo di equivalenza e coimmagine di f
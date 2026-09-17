**CAPITOLO 1: LOGICA RUDIMENTALE:**

* Proposizioni Logiche & Connettivi Logici

    * *4 Proprietà dei Connettivi Logici:* scrivi le tautologie

    * *Osservazione:* Quando si usa lo stesso connettivo, ha senso l'ordine delle parentesi ?

* Quando una proposizione logica si dice tautologia, contraddizione o contingente?

* *Proposizione*: Quando due forme proposizionali sono equivalenti?

* Leggi di De Morgan: a cosa servono le due tautologie?

    * Tautologie dell'implicazioni: A cosa è equivalente la doppia implicazione? se A => B, A e B che rapporto hanno?

        * *Proposizione:* (p => q) <==> ?

        * *Proposizione con Dimostrazione:* (p==>q) <==> (~q==>~p)

        * *Proposizione:* Come si scrive ~(p==>q) ?

        * *Proposizione:* Transitività dell'operatore di implicazione

        * *Proposizione:* (~(p<==>q)) <==> ? [3 Opzioni]

* Che informazioni fornisce dire che un'implicazione è falsa?

* Tautologie dello XOR [P.S. d.e. sta per disgiunto esclusivamente]

    * Proprietà Associativa della Disgiunzione Esclusiva + Dimostrazione        

    * *Osservazione:* p d.e. q <==> ?? [2 Opzioni]

    * *Proposizione:* a /\ (b d.e. c) <==> (a /\ b) d.e. (a /\ c)

* Quantificatori

    * Quando una formula si dice valida ?  

    * Quantificatore *universale* e *esistenziale*

    * Qual è il terzo quantificatore più frequente?

        * da quale equivalenza è definito ? [Mini-Dimostrazione]

    * Che vuol dire che una variabile è a occorrenza libera o vincolata?

        * data la definizione precedente, quando una formula si dice chiusa ?

        * data la definizione precedente, cosa è un predicato unario/binario?

        * *Quantificatori Ristretti*: i due quantificatori sono precisamente uguali? entrambi implicano l'altro ?

  

**CAPITOLO 2: TEORIA DEGLI INSIEMI:**

* Definizione di insieme --> com'era visto inizialmente?

    * Perchè è fallita poi come definizione? cosa possiamo fare se restringiamo il campo a un insieme s?

* Com'è definita l'estensione di un predicato unario? Con che formula lo si può scrivere ?

* Cosa dice *l'assioma di separazione*?

* Cosa dice *l'assioma di estensionalità*?

* *Osservazione*: 1. la formula per ogni x appartenente al vuoto x =! x è vera ?

                  2. la formula esiste x appartenente al vuoto tale che phi è vera ?

* a e {a} sono la stessa cosa ? come viene chiamato {a} ?

* Inclusione di due insiemi a e b

    * formula

    * come viene detto a ?

    * Dimostra che l'insieme vuoto è un sottoinsieme di qualsiasi insieme, è possibile dire che un insieme è sottoinsieme di se stesso ?

    * dati gli insiemi noti h e k, che vuol dire che h è incluso in k ?

    * cosa cambia se a è incluso *esclusivamente* in b?

* Insieme delle parti di x

    * Da cosa è composto ?

    * Formula

    * Come mai questo insieme è sicuramente non vuoto ?

    * Cos'è l'insieme delle parti n-arie?    

* *TEOREMA CON DIMOSTRAZIONE*: Vale la tautologia a = b <==> ((a ⊆ b) ⋏ (b ⊆ a))

* Operazioni Insiemistiche:

    * Intersezione --> quando due insiemi si dicono disgiunti?

    * Unione --> come posso usare i connettivi logici per esprimere le due operazioni ora citate ?

    * Differenza Insiemistica --> che succede se a è un sottoinsieme di b ? [Mini-Dimostrazione]

    * Differenza simmetrica

* Leggi di De Morgan + Dimostrazione

* Operazioni Unarie:

    * Unione Unaria: Cosa è e formula [RICORDA: Allarga, Esiste]

        * caso con c = {a,b} dove tutti e tre sono insiemi

    * Intersezione Unaria: Cosa è e formula [RICORDA: Restringe, Perogni]

* Prodotto Cartesiano di Insiemi:

    * formula

    * Proposizione + Dimostrazione: {{a}, {a,b}} = {{c}, {c,d}} <==> a = c ⋏ b = d

        * Definizione di coppia ordinata secondo Kuratowski

    * Cosa è una terna ordinata?

        * Cosa succede se ho ((a,b), c) = ((d,e), f)? come si dimostra ?

  

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
	* Suriettività e Iniettività
		* definizione di applicazione iniettiva
		* [Proposizione] retrazione iniettiva
		* [Proposizione] f iniettiva sse il modulo dell'antimmagine del singleton Y € A è <= 1 [Con Dimostrazione]
		* [Proposizione] f,g iniettiva => f o g iniettiva [Con Dimostrazione]
		* [Proposizione] f o g iniettiva => f iniettiva [Con Dimostrazione]
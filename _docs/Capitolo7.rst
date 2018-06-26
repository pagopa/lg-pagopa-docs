
|AGID_logo_carta_intestata-02.png|

+-------------------------------------------------------------------------------------+
|                                                                                     |
|**Linee Guida per l'effettuazione dei Pagamenti Elettronici a favore                 |
|delle Pubbliche Amministrazioni e dei Gestori di Pubblici Servizi**                  |
|                                                                                     |
|*ex articolo 5, comma 4 del decreto legislativo 7 marzo 2005. n. 82 e                |
|s.m.i. recante "Codice dell'amministrazione digitale"*                               |
|                                                                                     |
|**Versione** **1.2 –** **febbraio 2018**                                             |
|                                                                                     |
+-------------------------------------------------------------------------------------+

.. _informazioni-necessarie-per-leffettuazione-del-pagamento:

7. Informazioni necessarie per l’effettuazione del pagamento
============================================================

Al fine di avviare il processo di pagamento, gli Enti Creditori mettono
a disposizione degli utilizzatori finali e dei prestatori di servizi di
pagamento, le seguenti **informazioni minime**:

a\) denominazione dell’Ente Creditore;

b\) identificativo dell’obbligato (il pagatore);

c\) importo del pagamento dovuto;

d\) identificativo univoco di versamento e causale del versamento;

e\) identificativo del conto di pagamento sul quale versare le somme
dovute (IBAN del conto corrente bancario);

f\) identificativo del conto di pagamento postale sul quale versare le
somme dovute (IBAN del conto corrente postale, se nella
disponibilità dell’Ente Creditore);

g\) scadenza (se prevista).

Nel momento in cui l’Ente Creditore crea la posizione debitoria deve
memorizzare in un apposito archivio le informazioni minime richieste per
il relativo pagamento - che costituiscono evidenza informatica dei
pagamenti attesi - al fine di facilitare la fase di riconciliazione. Gli
Enti Creditori possono ampliare i dati resi disponibili, in coerenza con
le proprie soluzioni organizzative.

.. _IUV-e-causale-del-versamento:

7.1 Identificativo univoco di versamento e causale del versamento
-----------------------------------------------------------------

L’identificativo univoco di versamento **(IUV)** da indicare
obbligatoriamente, rappresenta **l’elemento essenziale della** **causale
del versamento,** il cui formato deve essere conforme e generato secondo
quanto specificato nella Sezione I dell’ `Allegato A - Specifiche attuative dei codici identificativi di versamento, riversamento e rendicontazione <https://pagopa-codici.readthedocs.io/it/latest/>`_.


Al fine di consentire le attività di riconciliazione del pagamento da
parte degli Enti Creditori e quelle di riversamento a cura dei
prestatori di servizi di pagamento, ciascun Ente Creditore attribuisce
ad ogni operazione di incasso un **codice identificativo** denominato
“\ **Identificativo Univoco di Versamento**\ ” (IUV) che non potrà mai
essere più associato nel tempo ad alcun altro incasso emesso dal
medesimo Ente Creditore.

Gli Enti Creditori possono demandare ad uno o più soggetti terzi, in
tutto o in parte, la generazione dell’Identificativo Univoco di
Versamento, avendo cura che ne sia mantenuta nel tempo l’univocità.

Per i versamenti al bilancio dello Stato o sui conti aperti presso la
Banca d’Italia nell’ambito del servizio di tesoreria dello Stato di cui
al decreto del Ministro dell'economia e delle finanze (MEF) del 9
ottobre 2006, n. 293 (“*Regolamento recante norme per l'introduzione di
nuove modalità di versamento presso le tesorerie statali*\ ”),
l’indicazione del codice IUV e della causale deve rispettare
integralmente quanto specificato nelle presenti Linee guida anche in
deroga, per la sola componente della causale, alla Circolare della
Ragioneria Generale dello Stato n. 20 dell’8 maggio 2007, tenuto conto
del rapporto di specialità delle presenti Linee guida rispetto alla
circolare della RGS. Le disposizioni di cui alla suddetta Circolare 
RGS n. 20 del 2007 restano integralmente applicabili per i versamenti 
effettuati dagli utilizzatori finali al di fuori del Sistema pagoPA.

7.2 Identificativo del conto di pagamento
-----------------------------------------

L’identificativo del conto di pagamento è costituito dal codice IBAN del
conto di pagamento dell’Ente Creditore aperto presso la banca che svolge
il servizio di tesoriera e/o cassa ovvero presso Poste Italiane S.p.A.

Per i versamenti al bilancio dello Stato o ai conti aperti presso la
Banca d’Italia nell’ambito del servizio di tesoreria dello Stato, il
codice IBAN di cui sopra è quello indicato sul sito web della Ragioneria
Generale dello Stato [2]_ ai sensi del già citato decreto del MEF n.
293/2006.

Sempre al fine di garantire il maggior numero di servizi di pagamento
disponibili, nel caso in cui siano stati istituiti dall’Amministrazione 
centrale uno o più conti correnti postali - intestati alle tesorerie e dedicati a
particolari categorie di versamenti, collegati a specifiche imputazioni
di versamento in tesoreria - dovrà essere fornito al PSP, oltre al codice 
IBAN per l’accredito presso la Banca d’Italia,
anche l’identificativo del conto corrente postale “dedicato” sul quale
effettuare il versamento tramite bollettino postale.

Per evitare che siano eseguite operazioni di pagamento al di fuori del
Sistema pagoPA, gli Enti Creditori non devono esporre in alcun modo,
neppure sul proprio sito web, né sugli avvisi di pagamento, gli
identificativi dei conti di pagamento utilizzati nel Sistema pagoPA.

7.3 Identificativo del pagatore
-------------------------------

Il codice identificativo del pagatore è rappresentato dal codice fiscale
o dalla partita IVA, fatti salvi i micro-pagamenti a favore degli Enti
Creditori per i quali non è necessaria l’identificazione del soggetto
che effettua il versamento.

.. [2]
   `Vedi sito MEF/RGS <http://www.rgs.mef.gov.it/VERSIONE-I/attivita_istituzionali/formazione_e_gestione_del_bilancio/bilancio_di_previsione/quadro_di_classificazione_delle_entrate/index.html>`_
   

.. |AGID_logo_carta_intestata-02.png| image:: media/header.png
   :width: 5.90551in
   :height: 1.30277in

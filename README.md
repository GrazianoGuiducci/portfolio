# Portfolio AI-DND - Graziano Guiducci

Dal 2022 sviluppo il livello operativo attorno all'IA agentica: sistemi che
preservano il contesto, verificano i propri risultati, ricordano i fallimenti,
rendono visibile il proprio stato e integrano le esperienze fatte,
migliorandosi ed evolvendo.

Questo portfolio presenta una selezione di lavori su laboratori autonomi,
kernel cognitivi, interfacce semantiche, logica D-ND, persistenza del contesto
e flussi di lavoro di agenti a lungo termine. È scritto per una revisione
tecnica: cosa esiste, cosa può essere ispezionato, cosa è maturo e cosa rimane
sperimentale.

Il ragionamento di alto livello sul modello D-ND è il livello di base di
questo lavoro. Dà forma a meta-prompt, strumenti, dashboard, misure di
sicurezza, cicli di valutazione e modelli operativi riutilizzabili.

## Da dove partire

1. [Mappa delle evidenze](docs/reviewer-evidence.md) — cosa ispezionare per
   primo e perché.
2. [D-ND Lab](projects/dnd-lab/README.md) — sistema vivo di Lab autonomi.
3. [d-nd-seed](projects/dnd-seed/README.md) — seme attivo e portabile per AI
   coder, con hook, memoria, sicurezza e pattern Lab.
4. [THIA](projects/thia/README.md) e [Gödel / CEC](projects/godel/README.md)
   — superficie operativa, crivello, inversione, memoria, routing e uso
   pubblico.
5. [D-ND Physics Lab](projects/dnd-lab-physics/README.md) — dominio di ricerca
   applicato che mostra il trasferimento del Lab.
6. [D-ND Papers](projects/dnd-papers/README.md) — kernel formale e Paper Zero.
7. [Indice dei progetti](projects/index.md) — traiettoria ampia e livelli di
   maturità.
8. [Profilo di lavoro](work/one-page-profile.md) — profilo compatto per ruoli
   e collaborazioni.

## Il quadro tecnico

Il lavoro nasce da un problema operativo e da una direzione più ampia: rendere
i sistemi di IA capaci di occuparsi di processi complessi in modo affidabile,
ispezionabile e consapevole. La continuità comprende il recupero del contesto e
la capacità del sistema di osservare il proprio stato, verificare le proprie
uscite, imparare dai fallimenti, auto-aggiustarsi e propagare le regole che
funzionano.

Questo quadro include:

- continuità del contesto tra sessioni, compattazioni e passaggi di nodo;
- memoria esplicita di decisioni, fallimenti, residui e prossime azioni;
- cicli claim / contro-claim con crivello CEC, Domandatore, Gödel,
  controprove, Proiettore e cristallizzazione;
- dashboard e superfici che rendono visibile stato, incertezza, vincoli e
  traiettoria;
- kernel cognitivi, meta-prompt, skill, seed installabili e template di Lab;
- autologica e autopoiesi: il sistema osserva il proprio funzionamento e
  trasforma ciò che regge in regola operativa.

Il punto operativo è semplice: il lavoro dell'IA diventa affidabile quando
contesto, verifica, memoria, visibilità e crescita interna diventano
struttura.

## Assi del portfolio

- **Consapevolezza programmabile**: boot, memoria, stato, recupero, verifica e
  regole di passaggio per agenti IA a lungo termine.
- **Lab autonomi di ricerca**: cicli che generano ipotesi, le verificano,
  registrano fallimenti e attraversano domini.
- **CEC, inversione e operatori decisionali**: strumenti che trasformano una
  tensione in crivello, punto di vista spostato, residuo e prossima domanda.
- **UX agentica e superfici di stato**: dashboard e interfacce che espongono
  stato vivo, vincoli, incertezza e percorsi di revisione.
- **Kernel cognitivi portabili**: semi, skill e genomi operativi locali che
  rendono installabile un comportamento agente utile.

## Ambiti di riferimento

Questi ambiti funzionano come indice tecnico del lavoro attuale e della
traiettoria in sviluppo:

- machine learning, AI awareness, kernel cognitivi e strumenti agentici;
- design UX-AI, media cognitivi e dinamiche di trasferimento
  dell'informazione tra umano, modello e sistema;
- logica, semantica, ontologia e teoria dell'informazione.

## Evidenze principali

- **D-ND Lab**: runtime vivo multi-dominio con cicli, report, falsificazione,
  dashboard di stato e template di dominio riutilizzabili.
- **d-nd-seed**: seme attivo e portabile per AI coder, con hook, recupero da
  compattazione, guardrail di sicurezza, skill, profili di installazione e
  pattern Lab.
- **THIA / Gödel / CEC**: superficie operativa viva dove memoria, routing,
  lenti pubbliche/private, crivello, inversione e flussi Lab si incontrano.
- **D-ND Physics Lab**: evidenza applicata del trasferimento del motore Lab in
  un dominio di ricerca.
- **D-ND Papers / Paper Zero**: sorgente formale compatta della logica
  operativa D-ND.

## Superfici pubbliche attuali

- Sito principale: https://d-nd.com
- Sottodominio Lab: https://lab.d-nd.com
- Dashboard Lab: https://lab.d-nd.com/dashboard/
- Repository seed: https://github.com/GrazianoGuiducci/d-nd-seed
- Repository Lab: https://github.com/GrazianoGuiducci/D-ND_LAB
- Repository portfolio: https://github.com/GrazianoGuiducci/portfolio

## Come leggerlo

Il percorso più rapido parte dal piano pratico e arriva al piano teorico:

- aprire la dashboard viva del Lab;
- leggere le schede D-ND Lab e d-nd-seed;
- usare la mappa delle evidenze per decidere quale repository o documento
  ispezionare;
- leggere Paper Zero con i sistemi già in vista.

I progetti precedenti o archiviati forniscono il contesto di traiettoria dei
sistemi attuali.

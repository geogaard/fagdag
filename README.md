# KI presentasjon og workshop
## Ressurser
- Les om prompt engineering i denne [Kode24 artikkelen](https://www.kode24.no/artikkel/prompt-engineer-tror-jobben-hans-er-framtida/79171943).
- Sjekk ut [Segment Anything demo](https://segment-anything.com/demo) for å se AI i handling.
- Prøv [OpenAI Chat](https://chat.openai.com/) for å samhandle med AI.
- Utforsk [Google Bard](https://bard.google.com/) for musikkgenerering med AI.
- Søk etter [Bing AI](https://www.bing.com/search?q=Bing+AI&showconv=1&FORM=hpcodx) for å lære mer om Bing's AI-løsninger.

# Workshop

- Vi skal se på hvordan KI kan genere tekst, behandle data og gjøre oppgaver som kan gjøre dagen litt lettere
- Lage prompts og lage enda bedre prompts
- Lage bilder
- Laste opp data
- Bli kjent med nye verktøy og modeller

Praktiske generelle oppgaver 

1. **Sammendrag av Tekst:**  
   KI kan automatisk generere sammendrag av lange tekster, som kan til med å få et raskt overblikk over dokumenter, e-poster, eller tekniske spesifikasjoner, uten å måtte lese gjennom hele teksten.

2. **Automatisk Generering av tabeller og lister:**  
   KI kan hjelpe med å strukturere ustrukturert data ved å automatisk generere tabeller og lister. Dette kan være spesielt nyttig for å organisere data, feilsøking, eller planlegging av prosjekter.

3. **Automatisert research:**  
   KI kan utføre grunnleggende undersøkelser ved å samle og organisere informasjon fra ulike kilder. Dette kan spare tid og hjelpe til med å holde seg oppdatert på ny teknologi, sikkerhetstrusler, eller bransjenyheter.

# Workshop Oppgaver: KI i Økonomiavdelingen

## Eksempeldatasett: Fiktivt Salgsdata

### Datasett Beskrivelse
Dette datasettet inneholder salgsdata for et fiktivt selskap.

Kolonner:

AnsattID: En unik identifikator for hver ansatt.
Avdeling: Avdelingen hvor den ansatte jobber.
Stilling: Stillingstittel for den ansatte.
Ansettelsesdato: Datoen den ansatte begynte i sin nåværende stilling.
Årslønn: Årslønn for den ansatte.
Bonus: Årlig bonus utbetalt til den ansatte.
Opplæringskostnader: Årlige kostnader tilknyttet opplæring per ansatt.
Andre Utgifter: Andre årlige utgifter knyttet til den ansatte (f.eks. reiseutgifter, utstyr).

'''AnsattID, Avdeling, Stilling, Ansettelsesdato, Årslønn, Bonus, Opplæringskostnader, Andre Utgifter
001, Salg, Salgssjef, 2020-06-01, 550000, 50000, 12000, 8000
002, IT, Utvikler, 2021-01-15, 450000, 30000, 15000, 5000
003, HR, HR Konsulent, 2019-09-01, 400000, 20000, 8000, 4000
004, Salg, Salgsrepresentant, 2022-03-12, 350000, 25000, 7000, 6000
005, IT, Systemadministrator, 2020-08-20, 420000, 35000, 10000, 5500
006, Markedsføring, Markedsføringskoordinator, 2021-05-17, 380000, 22000, 9000, 4500
007, Finans, Økonomisjef, 2018-11-30, 600000, 60000, 13000, 7000
008, HR, Rekrutterer, 2022-01-04, 360000, 18000, 6000, 3500
009, Markedsføring, Digital Markedsfører, 2019-07-08, 340000, 21000, 11000, 3000
010, Finans, Finansanalytiker, 2020-02-20, 480000, 40000, 14000, 6500'''



# Oppgaver for Bearbeiding og Analyse

## Oppgave 1: Grunnleggende Datahåndtering
- **Sorter datasettet etter `Årslønn` i synkende rekkefølge.**
- **Filtrer dataene for å vise kun ansatte i `IT`-avdelingen.**
- **Beregn gjennomsnittlig `Bonus` utbetalt i `Salg`-avdelingen.**

## Oppgave 2: Mellomnivå Analyse
- **Lag en oversikt over total årlig kostnad per avdeling** (sum av `Årslønn`, `Bonus`, `Opplæringskostnader`, og `Andre Utgifter`).
- **Analyser trenden i lønnsutgifter over tid** basert på `Ansettelsesdato` og `Årslønn`.
- **Identifiser topp 5 ansatte med høyest samlede kostnader** (`Årslønn` + `Bonus` + `Opplæringskostnader` + `Andre Utgifter`).

## Oppgave 3: Avansert Analyse og Prognoser
- **Bruk lineær regresjon for å forutsi lønnsveksten i de neste to årene** basert på historiske data.
- **Analyser effekten av `Opplæringskostnader` på `Bonus`** ved å bruke korrelasjonsanalyse.
- **Lag en prognose for forventede totale ansattekostnader for neste år** gitt nåværende ansettelsestrender.


**Bruk eksemplene under for å lage prompts**

## Oppgave
Oppgaven er kjerneinstruksjonen som forteller AI hva den skal gjøre.  
Eksempel: «Oversett teksten til fransk», «Beregn totalen», osv.

## Kontekst
Kontekst gir bakgrunn eller ytterligere informasjon som kan hjelpe AI til å forstå bedre.  
Hva er bakgrunnen? Hvordan ser et riktig resultat ut? Hvilket miljø er det snakk om?  
Eksempel: «Gitt at det regner, hva ville vært den beste måten å beskytte en pappeske på?»  
Eksempel 2: «Jeg er en 80 kg tung mann som ønsker å få 5 kg med muskelmasse på de neste 5 månedene. Jeg rekker bare å gå på treningssenteret to ganger i uken i en time per gang»

## Eksempel

Eksempler kan hjelpe AI med å forstå den ønskede format eller stilen på svaret.  
Eksempel: «Skriv en setning som bruker ordet 'glede' som i følgende eksempel: 'Glede fylte rommet da hun kom inn.’»  
Kan gi veldig gode resultater.

## «Persona»
«Persona» kan hjelpe med å tilpasse svarene til en spesifikk karakter eller rolle.  
Eksempel: «Hvordan ville en lege svart på følgende spørsmål: 'Hva er symptomene på influensa?’»  
Eksempel 2: «Lag en humoristisk kommentar som Chandler Bing om mandager.»

## Format
Formatinstruksjoner hjelper med å organisere svaret på en spesifikk måte.  
Eksempel: «List opp symptomene på influensa i punktform. », «lag resultatet i tabellform»

## Tone
Tonen kan spesifiseres for å matche en bestemt kommunikasjonsstil.  
Eksempel: "Skriv en munter introduksjon til emnet 'dataanalyse'."

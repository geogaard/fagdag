# KI presentasjon og workshop

## Profile
- [Fjellro](https://www.linkedin.com/in/fjellro)

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

Praktiske oppgaver 

1. **Sammendrag av Tekst:**  
   KI kan automatisk generere sammendrag av lange tekster, som kan til med å få et raskt overblikk over dokumenter, e-poster, eller tekniske spesifikasjoner, uten å måtte lese gjennom hele teksten.

2. **Automatisk Generering av tabeller og lister:**  
   KI kan hjelpe med å strukturere ustrukturert data ved å automatisk generere tabeller og lister. Dette kan være spesielt nyttig for å organisere data, feilsøking, eller planlegging av prosjekter.

3. **Automatisert research:**  
   KI kan utføre grunnleggende undersøkelser ved å samle og organisere informasjon fra ulike kilder. Dette kan spare tid og hjelpe til med å holde seg oppdatert på ny teknologi, sikkerhetstrusler, eller bransjenyheter.

# Workshop Oppgaver: AI i Økonomiavdelingen

## Eksempeldatasett: Fiktivt Salgsdata

### Datasett Beskrivelse
Dette datasettet inneholder salgsdata for et fiktivt selskap.

**Kolonner:**
- `Dato`: Datoen for salget.
- `ProduktID`: En unik identifikator for produktet.
- `Produktkategori`: Kategorien produktet tilhører.
- `Antall Solgt`: Antallet enheter solgt.
- `Enhetspris`: Prisen per enhet.
- `Total Salgsverdi`: Totalverdien av salget.

**Eksempeldata:**
Dato, ProduktID, Produktkategori, Antall Solgt, Enhetspris, Total Salgsverdi
2023-01-01, 1001, Elektronikk, 20, 500, 10000
2023-01-01, 1002, Klær, 15, 200, 3000
2023-01-02, 1003, Husholdning, 10, 150, 1500


## Oppgaver

### Oppgave 1: Enkle Tabellmanipulasjoner i Excel
- Sorter dataene etter `Total Salgsverdi` i synkende rekkefølge.
- Filtrer dataene for å vise kun salg fra `Elektronikk`-kategorien.
- Lag en Pivot-tabell for å vise totalt antall solgte enheter per `Produktkategori`.

### Oppgave 2: Mellomnivå Analyse
- Beregn gjennomsnittlig `Enhetspris` per `Produktkategori`.
- Lag en linjegraf som viser daglige `Total Salgsverdi` over en måned.
- Finn ut hvilken `ProduktID` som hadde høyest salg i forrige måned.

### Oppgave 3: Avansert Analyse med Python
- Skriv Python-kode for å importere datasettet og konvertere datoer til et datetime-objekt.
- Beregn månedlig vekst i `Total Salgsverdi` og visualiser dette med en graf.
- Bruk en enkel lineær regresjonsmodell for å forutsi fremtidige salg basert på historiske data.

## Etter Workshop
- Send ut en oppsummering av workshoppen, inkludert viktige punkter, ressurser og eventuelle opptak.
- Samle inn tilbakemeldinger for å forbedre fremtidige workshops.


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

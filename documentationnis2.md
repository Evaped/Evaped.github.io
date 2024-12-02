![GAP-analyse](../assets/img/GAP-analyse.PNG) 

![NIS2-tidsplan](../assets/img/NIS2-tidsplan.PNG) 

Risikoanalyse
Falske positive/negative resultater

Risiko: Et URL-sikkerhedstjek kan enten markere en sikker URL som skadelig (falsk positiv) eller undlade at opdage en skadelig URL (falsk negativ).

Scenarie: Begrænset eller forældet malware- og phishing-database, ineffektiv scanningsteknologi eller misforståede parametre i URL-analyse.

Forkert analyse af URL’er

Risiko: Nogle URL-formater eller teknologier kan være uforenelige med sikkerhedstjek systemet, hvilket kan føre til, at legitime eller farlige URL’er ikke bliver analyseret korrekt.

Scenarie: Sikkerhedstjekket understøtter ikke nyere teknologier, protokoller eller specifikke filtyper.

Uautoriseret adgang til sikkerhedstjek-hjemmesiden

Risiko: Uautoriserede brugere kan få adgang til systemet og potentielt manipulere eller deaktivere tjenesten.

Scenarie: Svage adgangskoder, dårlig adgangskontrol eller manglende to-faktor-autentifikation.

Manipulation af resultater

Risiko: Hackere eller kriminelle kan forsøge at manipulere med resultaterne af sikkerhedstjek for at undgå detektion af skadelige URL’er.

Scenarie: Angribere kan udnytte sårbarheder i analysealgoritmen eller indsætte falske informationer for at ændre tjek-resultaterne.

Manglende opdateringer og vedligeholdelse

Risiko: Uden regelmæssig opdatering kan sikkerhedstjeksystemet blive sårbart over for nye trusler og teknikker, som ikke tidligere er identificeret. Nugget pakker skal også opdateres løbende, ellers forekommer der fejl mens koden køres.

Scenarie: Udfordringer ved at holde systemet opdateret med den hurtige udvikling af nye malware og phishing-teknikker.

Juridiske og regulatoriske krav

Risiko: Sikkerhedstjekket kan overtræde privatlivslovgivning eller regler om databeskyttelse, især når det gælder lagring og håndtering af URL’er og brugerdata.

Scenarie: Manglende overholdelse af GDPR, NIS2, eller andre lokale love vedrørende databeskyttelse.

Risikovurdering – risikoniveau

Der er adskillige faktorer, der kan udgøre en trussel mod sikkerheden i it-systemer. For at håndtere disse potentielle risici effektivt, er det vigtigt at opnå en grundlæggende forståelse af det samlede risikobillede. Dette vil afhjælpe med at sætte sig ind der hvor risikoen er størst og ikke spilder tid og ressourcer på at løse ubetydelige risici.

Når der er udarbejdet en samlet risikovurdering, vil virksomheden have et grundlag for prioritering af risicihåndtering. Efter der er opstillet et sikkerhedsniveau ved hjælp af risikovurdering vil der foretages en handlingsplan. Risikovurdering vil blive udarbejdet på baggrund af de opstillede risikoanalyser som er følgende:

Falske positive/negative resultater

Forkert analyse af URL

Uautoriseret adgang til sikkerhedstjek-hjemmesiden

Manipulation af resultater

Manglende opdateringer og vedligeholdelse

Juridiske og regulatoriske krav

Der tages udgangspunkt i tabellen forneden, når risicien skal vurderes.

![Konsekvens](../assets/img/Konsekvens.PNG)

Heraf fremgår risikovurderingen for vores hjemmeside:

![Sandsynlighed](../assets/img/Sandsynlighed.PNG)

Vurderingen bliver udført således at der først laves en vurdering for hvad sandsynligheden er for at risicien kan opstå og derefter laves der en vurdering for hvad konsekvensen ville være hvis risicien finder sted. Herefter udarbejdes der en handlingsplan, som er en protokol, der har til formål at minimere risicien.

Handlingsplan

For hver hændelse, som udgør en risiko, udarbejdes der en beskrivelse af, hvad der er af eksisterende sikring samt en handlingsplan der fortæller hvilke nye foranstaltninger der skal tages forbehold for.

![Handlingsplan](../assets/img/Handlingsplan.PNG)

Prioritering af kontroller

I ISO/IEC 27001: Annex A fremgår en liste over kontrolmål og kontroller, der fungerer som et framework til informationssikkerhedsstyring. Den er især nyttigt som en tjekliste, hvor virksomheden kan identificere relevante kontroller, de kan implementere for at beskytte informationsaktiver.

Her er de vigtige elementer i Anneks A er:

Informationssikkerhedspolitikker: Retninglinjer for oprettelse og vedligeholdelse af informationssikkerhedspolitikker

Organisering af informationssikkerhed: Kontroller for korrekt ansvarsfordeling og strukturer i organisationen

Informationssikkerhed i forbindelse med HR: Fokus på sikkerhed af medarbejdere gennem hele ansættelsesforløbet

Styring af aktiver: Klassificering og håndtering af information og aktiver

Adgangskontrol: Kontroller der regulerer hvordan adgang til information administreres

Kryptering: Beskytter data ved hjælp af krypteringsteknikker

Fysisk og miljømæssig sikkerhed: Sikkerhedskontroller relateret til den fysiske sikring af bygninger og udstyr

Driftsikkerhed: Beskyttelse mod malware og backup af data

Kommunikationssikkerhed: Kontroller til at beskytte dataoverførsel i netværk og kommunikationskanaler

Systemudvikling og vedligeholdelse: Sikkerhed for it-systemer gennem deres livscyklus

Leverandørstyring: Styring af informationssikkerhed hos tredjepartsleverandører.

Håndtering af sikkerhedshændelser: Procedurer/protekoller til identifikation og håndtering af sikkerhedshændelser.

Driftskontinuitet i informationssikkerhed: Fokus på beredskabsplanlægning og fortsat drift i nødsituationer.

Overholdelse: Sikre, at informationssikkerheden opfylder love og standarder

Kortsagt fungerer Anneks A som et katalog over sikkerhedskontroller og virksomheder kan herfra udvælge de kontroller der er relevante for deres system afhængigt af deres specifikke risikovurdering og forretningsbehov.

Ifølge vores system er der taget udgangspunkt i risikovurderinger om hvorvidt hvilke kontrolområder i Anneks A der er mest relevante at prioritere.

Adgangskontrol:

Begrundelse: Beskytter systemet mod uautoriseret adgang, hvilket er kritisk for et sikkerhedssystem, der analyserer URL’er.

Kontroller: Indførelse af stærk autentificering fx multifaktor og rettighedsstyring for at sikre, at kun autoriserede brugere kan tilgå systemet.

Malwarebeskyttelse og sikkerhed i driften:

Begrundelse: URL-analyser indebærer høj risiko for eksponering mod malware, især hvis systemet aktivt henter eller besøger URL’er.

Kontroller: Isoler og kontroller potentielt skadelige URL’er i et sandbox-miljø, og sørg for opdaterede antivirus- og anti-malware-systemer.

Styring af aktiver:

Begrundelse: Klassificering og beskyttelse af data sikrer, at data håndteres efter dens følsomhed.

Kontroller: Identificér og klassificér URL-data og analyseresultater, og etabler retningslinjer for datalagring og sletning.

Håndtering af sikkerhedshændelser:

Begrundelse: Giver en klar procedure for at reagere på sikkerhedshændelser som identificerer ondsindede URL’er eller fejlklassificeringer.

Kontroller: Oprettelse af hændelsesresponsplan, så sikkerhedshændelser hurtigt kan håndteres, analyseres og logges

Kryptering:

Begrundelse: Beskyttelse af følsomme data fx brugeroplysninger, URL-analyseresultat mm. Både under opbevaring og transmission

Kontroller: Anvendelse af stærk kryptering til lagring af resultater og data relateret til URL-analyser

Leverandørstyring:

Begrundelse: Eksterne leverandører, som blandt andet tredjepartsdatabaser til URL-blacklist eller phisingsider.

Kontroller: Overvej leverandørernes sikkerhedsstandarder hvorefter databeskyttelse og informationssikkerhed sikres

Informationssikkerhed i forbindelse med HR:

Begrundelse: Sikre at alle medarbejder der har adgang til systemet har den rette uddannelse og sikkerhedsbevidsthed

Kontroller: Udførelse af baggrundstjek af medarbejder der arbejder med URL, hvorefter der gives en træning i at håndtere ondsindede URL’er

Driftskontinuitet i informationssikkerhed:

Begrundelse: Forhindring af driftsafbrydelser, så URL-tjeksystemet stadig kan fungere under nødsituationer

Kontroller: Udarbejdelse af en beredskabsplan for at sikre, at systemet kan fungere selvom der opstår tekniske problemer eller sikkerhedshændelser

Implementering + Pentesting  

Ved implementering og løbende evaluering af en hjemmeside der sikkerhedstjekker URL’er kræver en systematisk tilgang, der omfatter automatisering, periodisk kontrol og tilpasning af kontroller i takt med ændringer i risici og trusselsbilledet.

Herunder befinder der en trinvis vejledning til effektiv udførelse:

Trin 1: Automatisering af sikkerhedskontroller

Ved automatisering af sikkerhedskontroller reduceres behovet for manuel kontrol og det gør systemet mere reaktivt overfor potentielle trusler.

Automatisk URL-filtrering og klassificering: Dette indebærer blandt andet implementering af algoritmer til at scanne og kategorisere URL’er baseret på kendte trusler, som fx malware, phising og spam.

Automatiserede sandbox-tests: De potentielt skadelige URL’er vurderes i et sandbox miljø, så systemet tager mindst skade af det

Realtidsmonitorering: Realtidsalarmer og overvågning af systemets ydeevne og sikkerhed. Dette inkluderer overvågning af brugernes interaktioner og systemets reaktioner på potentielle trusler.

Automatisk logning og analyse: Implementering af logning af alle aktiviteter, som følgende URL-analyseresultater og fejlmeddelelser, da disse informationer skal beskyttes. Ved at implementer logning, automatiseres analyser af disse logs for at identificere mønstre, der kan indikere sikkerhedsproblemer.

Trin 2: Periodisk evaluering af kontrolfunktionernes effektivitet

Løbende evaluering sikrer, at kontrollerne fungerer som de skal og fortsat er relevante i forhold til de aktuelle trusler.

Test og vurdering af kontroller: Planlæg og udfør regelmæssige sikkerhedstest, som penetrationstests, for at vurdere hvordan systemet håndterer aktuelle trusler og ændringer i URL-trusselsbilledet.

Gennemgang af hændelseslogfiler: Analysering af logfiler for at evaluere om kontrollerne korrekt identificerer og blokerer skadelige URL’er.

Håndtering af falske positiver og falske negativer: Evauler nøjagtigheden af systemet ved at kontrollere, om uskyldige URL’er fejlagtigt blokeres, altså falske posetiver, eller om skadelige URL’er tillades, altså falske negativer. Juster klassificeringsalgoritmer for at minimere fejl.

Trin 3: Justering af kontroller ved ændringer i trusselsbilledet

Ændringer i sikkerhedstrusler sker konstant, og det er afgørende, at sikkerhedskontroller løbende tilpasses.

Overvåg trusselsopdateringer: Følg op på nye trusselsmønstre, fx opdaterede lister over ondsindede domæner eller nye teknikker inden for phishing

Tilpas kontroller og algoritmer: Opdater filtrerings- og klassificeringsalgoritmer baseret på ny viden om trusler og skadelige URL-kategorier

Inddrag feedback fra brugere og hændelsesrapporter: Indsaml og anvend feedback fra brugere og sikkerhedshændelser til forbedring af systemet, hvilket vil hjælpe med at identificere protentielle svagheder i de eksisterende kontroller.

Trin 4: Gennemfør regelmæssige audits og reviews

Audits sørger for om kontrollerne fungerer effektivt og er i overensstemmelse med sikkerhedsstandarder

Interne sikkerhedsreviews: Udfør halvårlige eller kvartalsvise interne sikkerhedsreviews. Dette vil sikre at alle kontroller fortsat er relevante og i overensstemmelse med ISO/IEC 27001 standarderne.

Ekspertevalueringer: Anvendelse af eksterne sikkerhedseksperter til vurderinger. Dette sikre at der fås nye perspektiver og at alle aspekter af systemet er dækket.

Compliance-gennemgang: Sikre at alle kontroller overholder lovgivningskrav, især hvis systemet håndterer data med personoplysninger, som i dette tilfælde er vores login-system.

Trin 5: Dokumentation og forbedringsplaner

Dokumentation undervejs af alle ændringer og opdateringer af kontrollerne er vigtig for at sikre sporbarhed og konsistens.

Kontrolhistorik: Detaljeret dokumentation af implementerede kontroller og eventuelle ændringer vil afhjælpe med at give en forståelse for hvornår og hvorfor kontrollerne blev justeret/udført.

Forbedringsplaner: Lav forbedringsplaner for kontroller, der viser sig at være mindre effektive. Planen kan indeholde opdatering af teknologi, uddannelse af medarbejdere eller implementering af nye automatiseringsværktøjer.

Trin 6: Uddannelse og opmærksomhedstræning

Oplæring af relevante medarbejdere i opdaterede kontrolforanstaltninger og de nyeste trusselsbilleder.

Sikkerhedstræning: Træning i systemets opdaterede funktioner, så medarbejdere har en forståelse i de nye sikkerhedsforanstaltninger.

Bevidsthed om trusler: Træning i at identificere og reagere på nye typer af URL-baserede trusler.

Ved systematisk automatisering, evaluering, tilpasning og dokumentering af sikkerhedskontrollerne kan der sikres en kontinuerlig og opdateret beskyttelse af URL-sikkerhedssystemet.

PDCA-modellen

PDCA-modellen (Plan-Do-Check-Act) er en iterativ metode, der hjælper med kontinuerlig forbedring af sikkerhedskontrollerne i et system til URL-sikkerhedstjek. Således anvendes modellen:

Plan (planlæg)

I denne fase identificeres og planlægges sikkerhedskontrollerne baseret på en risikovurdering, trusselsbillede og forretningsmål. For et URL-sikkerhedstjeksystem vil dette omfatte:

Risikovurdering: Analysér de største trusler, fx phishing-URL’er og malware-hostede sider. Udarbejd en risikomatrix, der indeholder sandsynlighed og konsekvens af forskellige trusler.

Identifikation af kontroller: Vælg passende sikkerhedskontroller fra ISO/IEC 27001 Anneks A, som fx adgangskontrol, kryptering og hændelseshåndtering, baseret på de identificerede risici.

Mål og succesparametre: Definér målbare mål, som fx nedsættelse af falske negativer (onde URL’er markeret som sikre) og en nøjagtighedsprocent for identificering af skadelige URL’er.

Udvikling af procedurer: Udarbejd procedurer for implementering af kontrollerne, fx guidelines for kryptering af kommunikation og logningskrav for hændelser.

Do (Udfør)

Implementér de planlagte kontroller og procedurer. For et URL-sikkerhedstjeksystem vil denne fase omfatte:

Implementering af teknologiske løsninger: Opsæt automatiserede filtre, realtidsmonitorering og sandbox-miljøer for sikker test af mistænkelige URL’er.

Træning af personale: Uddan medarbejdere i nye sikkerhedsprocedurer, fx identificering af ondsindede URL’er og håndtering af sikkerhedshændelser.

Konfiguration af overvågnings- og logningssystemer: Opsæt overvågning for at kunne analysere systemets ydeevne og sikkerhed i realtid, inklusiv automatisk logning af URL-analyseaktiviteter.

Dokumentation: Dokumentér alle ændringer og den fulde proces for at sikre, at den valgte plan følges, og at implementeringen er gennemsigtig og sporbar.

Check (Kontrollér)

I denne fase vurderes effektiviteten af de implementerede kontroller, og der samles data til evaluering af resultaterne.

Overvågning og vurdering af resultater: Evaluer nøjagtigheden af URL-analyse ved at gennemgå logdata for falske positive og falske negative resultater.

Audit og gennemgang: Gennemfør interne og eksterne audits for at sikre, at systemet overholder både interne sikkerhedsstandarder og ISO/IEC 27001 krav.

Risiko- og hændelsesanalyse: Analyser hændelser eller alarmer for at identificere mønstre i URL-sikkerhedstrusler, og vurder, om kontrollerne virker efter hensigten.

Sammenligning med mål: Vurder, om de oprindelige mål (fx nøjagtighedsniveau og reaktionstid på sikkerhedshændelser) er nået, og identificér eventuelle afvigelser.

Act (Justér)

Justér og forbedre systemet baseret på de indsamlede data og evalueringerne i Check-fasen. Denne fase indebærer:

Opdatering af kontroller: Tilpas kontrollerne for at forbedre systemets sikkerhed baseret på identificerede svagheder. For eksempel kan algoritmer til URL-filtrering justeres for at reducere falske positive.

Opdatering af procedurer og træning: Justér procedurerne regelmæssigt og sørg for, at medarbejdere trænes i eventuelle nye processer eller forbedrede sikkerhedskontroller.

Kontinuerlig forbedring: Udarbejd en plan for løbende overvågning og tilpasning af kontroller, så systemet kan reagere hurtigt på ændringer i trusselsbilledet.

Feedback-loop: Etabler et feedback-system, hvor resultater og erfaringer fra hver PDCA-cyklus bruges som input til næste cyklus for at skabe en tilgang til kontinuerlig forbedring.

Ved at følge PDCA-modellen sikres der, at sikkerhedskontrollerne for URL-sikkerhedssystemet løbende tilpasses og forbedres i takt med nye trusler og teknologiske ændringer. Dette skaber en robust og dynamisk sikkerhedsramme, der beskytter systemet effektivt.
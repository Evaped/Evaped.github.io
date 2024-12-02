---
layout: page
title: Uge 46
permalink: /week46/
---

1. Forstå NIS2-kravene

   Denne strategi vil være baseret på de 10 basiskrav, der gælder for alle organisationer.

   Forpligtelser som rapportering, risikohåndtering og tekniske sikkerhedsforanstaltninger:
 
   Indenfor 24 timer efter opstået kendskab skal hændelsen rapporteres til CSIRT (Computer Security Incident Response Team) eller den nationale myndighed, såsom Datatilsynet.

   Indenfor 72 timer efter opstået kendskab skal der indsendes en hændelsesmeddelelse.

   Indenfor en måned efter opstået kendskab skal en endelig rapport indsendes.

   Konsekvenserne for manglende overholdelse, f.eks. bøder eller sanktioner:

   Jeg har valgt at klassificere mit projekt som en kritisk aktør, da det ikke vil blive bredt brugt, men kun vil tilhøre én virksomhed. Det betyder, at sanktionen for overtrædelse vil være minimum €10.000.000 eller 2% af virksomhedens globale årlige omsætning fra det forrige år – afhængigt af, hvad der er højest.


2. Analysér organisationens nuværende tilstand

   GAP-analyse: Undersøg, hvor organisationen allerede opfylder kravene, og hvor der er mangler.

Kortlæg eksisterende sikkerhedspolitikker, procedurer og systemer.

Der ligger en risikoanalyse med handlingsplan under dokumentation for NIS2.

Evaluer organisationens risikohåndtering, overvågning og rapporteringsprocesser.

Der ligger en risikoanalyse med handlingsplan under dokumentation for NIS2.

Identificér eventuelle svage punkter i forsyningskæden eller samarbejdspartnere.

Der ligger en GAP-analyse under dokumentation for NIS2.

3. Definér projektets mål

   Overholdelse af NIS2-kravene inden for en bestemt deadline.

   Der ligger en tidsplan under dokumentation for NIS2.

   Implementering af en robust cybersikkerhedsstrategi.

   Projektet vil blive en del af en større etableret IT-virksomhed, og de tiltag, der er tænkt i forhold til risikoanalysen, vil bidrage til at opbygge en stærk cybersikkerhedsstrategi.

   Styrkelse af organisationens evne til at opdage og håndtere sikkerhedstrusler.

   Hvis vi beholdt projektet selv, kunne der opsættes automatiserede rapporter, som kører med jævne mellemrum, hvilket ville muliggøre automatiseret opdagelse og håndtering af sikkerhedstrusler.

4. Opret en projektstruktur

   Projektleder: Ansvarlig for at lede NIS2-implementeringen.

   Projektet vil blive videregivet til en anden aktør, men ellers ville jeg stå som ansvarlig.

   Core team: IT-afdelingen, juridisk afdeling, compliance-specialister og evt. eksterne konsulenter.

   Projektet vil ende i et hus, hvor de har både en udviklingsafdeling og en IT-sikkerhedsafdeling, som vil sikre, at programmet altid overholder de nødvendige standarder.

   Styregruppe: Øverste ledelse og nøgleinteressenter for at sikre forankring og ressourcer.

   Lederen af IT-sikkerhedsafdelingen.

   Udviklingsafdelingen.

   Offentlige myndigheder.

5. Udarbejd implementeringsplanen

   Del planen op i faser med klare deadlines og milepæle:

Fase 1: Forberedelse

Implementering af risikostyringsforanstaltninger.

Etablering af en incident response-plan.

Overholdelse af rapporteringskrav.

Sikring af netværks- og informationssystemer mod cyberangreb.

Beskyttelse af data mod uautoriseret adgang.

Gennemførelse af træning og opmærksomhed om cybersikkerhed blandt ansatte.

Løbende opdatering og vedligeholdelse af sikkerhedssystemer.

Audit og dokumentation af sikkerhedsforanstaltninger.

Involvering af leverandører og samarbejdspartnere i sikkerhedsprocedurer.

Overholdelse af regulative krav og standarder.

Interessentanalyse: Identificér nøgleinteressenter og kommunikationsbehov.

Der ligger en interessentanalyse med kommunikationsplan for projektet under dokumentation for projektkoordinering.

Kommuniker projektet: Informér medarbejdere og ledelse om NIS2-implementeringen.

Der vil blive afholdt et overdragelsesmøde for medarbejderne i udviklingsafdelingen og IT-sikkerhedsafdelingen.

Det vil være vigtigt at tilkoble eksperter inden for NIS2 og ISO-standarderne til projektet, alternativt have HR til at afsætte timer til træning.

Fase 2: Risikovurdering

Gennemfør en risikovurdering: Identificér trusler mod netværk, systemer og data.

Ligger under dokumentation for NIS2.

Prioritér risici: Opdel i høj, middel og lav prioritet baseret på sandsynlighed og konsekvens.

Ligger i risikoanalysen under dokumentation for NIS2.

Fase 3: Implementering af foranstaltninger

Teknologiske foranstaltninger:

Installér og konfigurér avancerede cybersikkerhedssystemer (firewalls, SIEM, IDS/IPS).

Programmet er opsat med autentifikation for at øge sikkerheden omkring login, ud over at der er opsat SSO-login, som kræver adgang til et virksomhedslogin.

Sikr kryptering af følsomme data.

Der er opsat en database gennem Docker, og programmet er bygget op omkring microservices og masstransit.

Processuelle foranstaltninger:

Implementér politikker for adgangskontrol og databeskyttelse.

Alle brugere skal logge ind med et virksomhedslogin, som udleveres af virksomheden.

Etabler en incident response-plan.

Hvis en uautoriseret bruger får adgang, vil det blive håndteret i de eksisterende procedurer for misbrugte login, hvor IT-sikkerhedsafdelingen eller data-breach-afdelingen skal underrettes straks.

Organisatoriske foranstaltninger:

Træn medarbejdere i sikkerhedsbevidsthed og NIS2-krav.

IT-sikkerhedsafdelingen skal optrænes i NIS2, så de kan fortsætte med at opretholde NIS2-standarderne.

Opret en intern kommunikationskanal for sikkerhedshændelser.

Medarbejdere skal informeres om, hvad de skal gøre, hvis de oplever, at deres login er blevet kompromitteret, eller hvis de får besked om en skadelig hjemmeside.

Fase 4: Dokumentation og rapportering

Dokumentér alle implementerede foranstaltninger og procedurer.

Alle indmeldte hændelser skal dokumenteres og gemmes i op til 3 måneder for at sikre dokumentation under hele hændelsens livscyklus.

Alle henvendelser til offentlige myndigheder omkring brud skal gemmes i op til 3 måneder.

Opret en plan for løbende compliance-monitorering og rapportering til myndigheder.

Så snart en henvendelse modtages, skal den rapporteres videre til Datatilsynet. Det samme gælder for rapporter.

Alle meldinger skal dokumenteres og rapporteres til nærmeste leder (lederen af IT-sikkerhed eller data-breach).

Fase 5: Tidsplan og budget

Udarbejd en realistisk tidsplan med deadlines for hver fase.

Prioritér aktiviteter baseret på deres kritikalitet for compliance.

Der ligger en tidsplan under dokumentation for NIS2.
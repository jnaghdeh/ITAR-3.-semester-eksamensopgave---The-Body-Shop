Den stærkeste røde tråd opnås ved **ikke** at behandle _Forretningsudvikling og innovation_ og _Forretningsprocesser og optimering_ som to adskilte siloer, men i stedet flette dem sammen i en **4-faset tragt**: fra helikopterperspektiv (AS-IS) ned i de konkrete arbejdsgange og rodårsager, op i den strategiske vurdering og tilbage i det fremtidige design (TO-BE). Hvis I laver BMC TO-BE, før I har analyseret processerne og fundet spild og rodårsager, kommer jeres fremtidige forretningsmodel til at mangle dokumenteret grundlag.

Nedenfor er den optimale rækkefølge på jeres 11 udvalgte analyser, hvordan de fodrer hinanden, og hvordan I sætter et skarpt scope, så I holder jer inden for eksamenskravet på maksimalt 30 normalsider.

## Den anbefalede rækkefølge (Overblik)

| Fase                                | Trin & Analyse                    | Emneområde           | Input → Output (Den røde tråd)                                                                                     |
| ----------------------------------- | --------------------------------- | -------------------- | ------------------------------------------------------------------------------------------------------------------ |
| **1. Overblik & Afgrænsning**       | **1. BMC (AS-IS)**                | Forretningsudvikling | Kortlægger The Body Shops nuværende forretningsmodel og sætter rammen for, hvordan butiksdriften skaber værdi.     |
|                                     | **2. BME (Omverden)**             | Forretningsudvikling | Afdækker eksterne krav (arbejdstidslov, tidsregistreringslov, GDPR, sæsonudsving), som lægger pres på driften.     |
|                                     | **3. Scope**                      | Procesoptimering     | Afgrænser analysen fra hele forretningen til de specifikke interne vagtprocesser (start, slut, aktører, frekvens). |
| **2. Proceskortlægning & Diagnose** | **4. SIPOC**                      | Procesoptimering     | Giver det hurtige makrobillede af input/output i de valgte processer og udpeger første tegn på spild.              |
|                                     | **5. BPMN (AS-IS) + Waste**       | Procesoptimering     | Kortlægger nuværende vagtplanlægning/vagtbytte i detaljer og markerer konkrete flaskehalse og Lean-spild.          |
|                                     | **6. 5 Why's**                    | Procesoptimering     | Graver sig fra symptomerne i BPMN AS-IS (f.eks. WhatsApp-rod) ned til den egentlige rodårsag.                      |
| **3. Strategi & Modenhed**          | **7. SWOT + Prioritering → TOWS** | Forretningsudvikling | Samler interne fund (trin 1, 5, 6) og eksterne fund (trin 2) og omsætter dem til strategiske handlemuligheder.     |
|                                     | **8. Digital modenhed & GAP**     | Procesoptimering     | Vurderer nuværende vs. realistisk modenhed og definerer præcis, hvad der skal til for at lukke kløften.            |
| **4. Fremtidigt design (TO-BE)**    | **9. VPC**                        | Forretningsudvikling | Oversætter chefens og medarbejdernes jobs, pains og gains til det konkrete værditilbud for løsningen.              |
|                                     | **10. BPMN (TO-BE)**              | Procesoptimering     | Viser de nye, digitaliserede arbejdsgange, hvor det nye system fjerner spild og overholder lovkrav automatisk.     |
|                                     | **11. BMC (TO-BE)**               | Forretningsudvikling | Lukker cirklen på virksomhedsniveau og viser den samlede forretningsmæssige effekt af den nye løsning.             |

## Gennemgang af de 4 faser og sammenhængen mellem metoderne

### Fase 1: Forretningsforståelse og afgrænsning (Makro AS-IS)

I starter på virksomhedsniveau (_Enterprise level_) for at forstå forretningskonteksten, før I zoomer ind på de enkelte arbejdsgange (_Business process level_).

- **1. BMC (AS-IS):** Kortlæg kort The Body Shops eksisterende butiksmodel med særligt fokus på de byggeklodser, der påvirkes af bemanding: _Key Activities_ (butiksdrift og bemandingsplanlægning), _Key Resources_ (medarbejdere, nøglepersoner og butikschef) og _Cost Structure_ (lønbudget og administrativ tid).
    
- **2. BME (Business Model Environment):** Analysér omverdenen rundt om forretningsmodellen. Her får I guldkorn direkte fra jeres case: **lovpligtige arbejdstidsregler** (11-timers reglen, ugentligt fridøgn, 48-timers reglen og pausekrav), **loven om tidsregistrering** (gældende fra 1. juli 2024), **GDPR-krav** ved brug af private telefonnumre i WhatsApp samt detailhandlens **spidsbelastninger** (julehandel, udsalg, helligdage).
    
- **3. Scope (flyt denne før SIPOC):** I jeres udkast stod Scope nederst og SIPOC som start, men i BPM-metoden er _Scoping og planlægning_ altid trin 1. Brug et klassisk scoping-skema til at fastlægge procesnavn, start-trigger, slutstadie, volumen/frekvens og direkte aktører. Det er her, I beviser over for censor, hvorfor I fokuserer på interne bemandingsprocesser og ikke hele The Body Shops forsyningskæde.
    

### Fase 2: Proceskortlægning og problemdiagnose (Mikro AS-IS)

Nu bevæger I jer ind i BPM-metodens fase 2 og starten af fase 3.

- **4. SIPOC:** Brug SIPOC som det overordnede bindeled mellem Scope og BPMN. Her ser I hurtigt, at inputtet til bemandingskabalen (ønsker, sygdom, vagtbytter) kommer ustruktureret ind via WhatsApp, hvilket skaber de første indikationer på spild.
    
- **5. BPMN (AS-IS) + Waste:** Kortlæg nu de nuværende arbejdsgange i BPMN med tydelige roller/lanes (fx Medarbejder, Kollega og Butikschef). På selve diagrammet – eller i en ledsagende analyse – udpeger I Lean-spild (_waste_) og flaskehalse: ventetid på svar i WhatsApp, dobbeltarbejde ved manuel opdatering af vagtplan, samt risiko for fejl (ulovlige vagtkombinationer eller manglende åbne-/lukkeansvarlig).
    
- **6. 5 Why's:** Vælg de 1–2 mest kritiske problemer fra jeres BPMN AS-IS og kør 5 Why's. Pointen er at undgå symptombehandling: Problemet er ikke blot "at de bruger WhatsApp", men at **kommunikation, vagtdata og lovgivningsregler er adskilt uden én samlet kilde til sandhed (_single source of truth_)**.
    

### Fase 3: Strategisk vurdering og modenhed (Broen fra AS-IS til TO-BE)

Nu samler I alle jeres analytiske fund, så overgangen til jeres løsning ikke virker grebet ud af luften.

- **7. SWOT + Prioriteringsmatricer → TOWS:** Fordelen ved at placere SWOT/TOWS _her_ (i stedet for lige efter BMC AS-IS) er, at jeres _Svagheder_ nu er dokumenteret gennem både BMC, BPMN-spild og 5 Why's, mens _Trusler og Muligheder_ kommer direkte fra BME. Brug prioriteringsmatricer til at skære støjen fra og par kun de vigtigste faktorer i TOWS for at udlede de konkrete strategiske tiltag, som jeres IT-løsning skal realisere.
    
- **8. Digital modenhed & GAP-analyse:** Vurdér The Body Shops nuværende digitale modenhed på vagtplanlægning (lav/manuel, ad-hoc via WhatsApp) over for den _realistiske_ måltilstand inden for projektets rammer (datadrevet planlægning med automatisk regelkontrol og samlet kommunikation). GAP-analysen opsummerer derefter præcis, hvilke teknologiske og procesmæssige mangler der skal lukkes for at nå derhen.
    

### Fase 4: Fremtidigt design og værdiskabelse (TO-BE)

Her omsætter I indsigterne til den løsning, I faktisk skal bygge i de tekniske fag.

- **9. VPC (Value Proposition Canvas):** Brug VPC til at skærpe værditilbuddet for jeres **to interne målgrupper**: Butikschefen og Butiksmedarbejderne (krav i opgaven er mindst to målgrupper). Start med _Customer Profile_ (Jobs, Pains fra fase 2 og Gains), og design derefter _Value Map_ med de konkrete funktioner som _Pain Relievers_ og _Gain Creators_ (fx kontekstbaseret chat direkte på en vagt, realtidsadvarsler ved 11-timers brud og ét-kliks godkendelse).
    
- **10. BPMN (TO-BE):** Tegn den nye proces med jeres vagtplansystem som en aktiv deltager/lane. Her demonstrerer I visuelt, hvordan de spildpunkter, I fandt i trin 5, forsvinder, fordi systemet selv tjekker hviletid og kompetencer og opdaterer planen automatisk ved godkendelse.
    
- **11. BMC (TO-BE):** Løft til sidst perspektivet tilbage til hele forretningen og vis ændringerne i forretningsmodellen (marker gerne ændringer med en ny farve). Her viser I, hvordan et internt IT-system ændrer _Key Resources_ (egen applikation og tidsdata), _Key Activities_ (effektiv, lovmedholdelig bemanding) og _Cost Structure_ (sparet ledelsestid, bedre match mellem lønprocent og travlhed samt minimeret risiko for godtgørelseskrav).
    

## Forslag til et skarpt Scope (og sideøkonomi)

Med 11 modeller i _Forretningsdesign og analytics_ samt fuld dokumentation for _Systemudvikling_ og _Softwarearkitektur/IT-infrastruktur_ skal I styre benhårdt efter grænsen på **max. 30 normalsider**.

- **Vælg maks. 2 kerneprocesser i jeres Scope:** I stedet for at modellere al HR og drift i The Body Shop, så afgræns jer knivskarpt til to tæt forbundne processer:
    
    1. _Udarbejdelse og udgivelse af vagtplan_ (primært Butikschefens flow inkl. ønsker og lovkontrol).
        
    2. _Vagtbytte / akut dækning inkl. kontekstbaseret chat_ (primært Medarbejdernes og Chefens fælles flow).
        
- **Afgræns jeres VPC-perspektiv i metodeafsnittet:** Klassisk bruges VPC mod slutkunderne i butikken, men da eksamensopgaven specifikt fokuserer på interne processer og interne brugere, bør I i metodeafsnittet eksplicit argumentere for, at I anvender VPC med _butikschefen_ og _medarbejderne_ som interne "kunder" for den nye digitale service. Det viser stærk metodebevidsthed.
    
- **Brug bilag klogt:** Indsæt kun de vigtigste modeller direkte i rapporten (fx BPMN AS-IS/TO-BE, TOWS, VPC og BMC TO-BE) og læg store støttemodeller som fuld BME, prioriteringsmatricer og SIPOC-detaljer i bilag, mens I præsenterer de skarpe delkonklusioner i hovedteksten.
    

## Sådan binder I den røde tråd videre til de andre fag

For at score højt på sammenhængen på tværs af semesteret bør I lade Fase 4 fungere som direkte afsæt til resten af rapporten:

- **Til Systemudvikling:** Pains fra **BPMN AS-IS**, **5 Why's** og **VPC** føder direkte ind i jeres _Brugerrejse_ og derefter ind i kravspecifikationen (_constitution_ og _specify_) i GitHub Spec Kit.
    
- **Til Softwarearkitektur og IT-infrastruktur:** Kravene fra **BME** (GDPR, lovpligtig tidsregistrering, 11-timers regel) og **GAP-analysen** bliver jeres direkte begrundelse for valg af _kvalitetsattributter_ (sikkerhed, integritet, tilgængelighed), rollebaseret adgangsstyring (_401 vs. 403_ mellem chef og medarbejder) og valg af _relationel database_ som single source of truth til strukturerede vagt- og lovdata.
# Sýn og Afmörkun 

## Númer teymis og höfundar
Teymi 1 <br>
Arnþór Atli Atlason <br>
Kristín Sesselja Róbertsdóttir <br>

## Heiti kerfis
Sjálfvirkt bókasafnskerfi.


## Efnisyfirlit 
- [Breytingasaga](#revision-history)
- [1. Viðskiptakröfur](#1-business-requirements)
    - [1.1 Bakgrunnur](#11-background)
    - [1.2 Viðskiptatækifæri](#12-business-opportunity)
    - [1.3 Viðskiptamarkmið](#13-business-objectives)
    - [1.4 Árangursmælikvarðar ](#14-success-metrics)
    - [1.5 Sýn](#15-vision-statement)
    - [1.6 Viðskiptaáhætta](#16-business-risks)
    - [1.7 Viðskiptaforsendur og háðleiki](#17-business-assumptions-and-dependencies)
- [2. Umfang og takmarkanir](#2-scope-and-limitations)
    - [2.1 Helstu fídusar](#21-major-features)
    - [2.2 Umfang fyrstu útgáfu](#22-scope-of-initial-and-subsequent-releases)
    - [2.3 Takmarkanir og útilokanir](#23-limitations-and-exclusions)
- [3. Samhengi viðskipta](#3-business-context)
    - [3.1 Prófílar hagsmunaaðila](#31-stakeholder-profiles)
    - [3.2 Forgangsröðun verkefnis](#32-project-priorities)
    - [3.3 Innleiðingarsjónarmið](#33-deployment-considerations)

---

> 
## 1. Viðskiptakröfur
### 1.1 Bakgrunnur


### 1.2 Viðskiptatækifæri


### 1.3 Viðskiptamarkmið
Markmið kerfisins er að gera bókasafnsferla einfaldari og hraðari. Helstu markmið eru:
- Sjálfvirk skráning og stjórnun á bókum.
- Einfalt útlánakerfi sem auðveldar notendum að fá bækur lánaðar.
- Sjálfvirkar áminningar þegar bækur eru ekki skilaðar á réttum tíma.
- Betri yfirsýn fyrir starfsfólk bókasafnsins til að sjá hvaða bækur eru í boði og hverjar eru í útláni.
- Að auka ánægju notenda og minnka biðtíma.

### 1.4 Árangurs mælikvarðar


### 1.5 Framtíðarsýn

Framtíðarsýn kerfisins er að bókasöfn verði orðin sjálfvirkari og aðgengilegri. Notendur geta sjálfir séð hvaða bækur eru lausar, tekið þær í útlán og fengið sjálfvirkar áminningar án þess að þurfa að tala við starfsfólk. Starfsfólk getur þá frekar einbeitt sér að þjónustu og fræðslu frekar en endalausri skráningu og eftirliti. Með tímanum gæti kerfið tengst öðrum bókasöfnum eða rafrænum gagnagrunnum og þannig aukið aðgengi að efni fyrir alla. Þetta getur sparðað bókasafnseigenda pening í starfskrafti til lengri tíma. Þetta er skref í átt að nútímalegra bókasafni sem þjónar þörfum bæði bókasafnsrekenda og lánþega.

### 1.6 Viðskiptaáhætta


### 1.7 Viðskiptaforsendur og háðleiki


---

## 2. Umfang  og takmarkanir 
### 2.1 Helstu fídusar


### 2.2 Umfang fyrstu útgáfu

#### Sjálfsafgreiðsla lána og skil á bókum
- Notendur geta sjálfir skráð bækur út og inn í gegnum sjálfsafgreiðslustöð, sem dregur úr biðtíma og léttir álag á starfsfólki.
#### Notendavænt viðmót
- Skjár með skýrum leiðbeiningum, þannig að flestir eigi að geta notað kerfið án aðstoðar.
#### Bækur
- Kerfið mun geyma helstu upplýsingar um bækur (titil, höfund og útgáfuár) og geta tengt við láns- og skilaferlið.
#### Notendur
- Notendur skrá sig inn með bókasafnsskírteini eða QR kóða sem tryggir að hver bók sé tengd réttum lánþega.
#### Tilkynningar 
- Tilkynningar með áminningum munu berast með tölvupósti til að minna á skiladag.

#### Ávinningur
- Fyrir notendur: Styttri afgreiðslutími og meiri þægindi við að nýta þjónustuna
- Fyrir bókasafnsstarfsmenn: Minna álag við afgreiðslu.
- Fyrir bókasafnið í heild: Bætt upplifun gesta og einfaldari yfirsýn yfir útlán.

#### Gæði
- Áreiðanleiki í útlánum og skilum
- Viðmótið hannað með einfaldleika að leiðarljósi
- Kerfið mun styðja við áframhaldandi þróun fyrir seinni útgáfur.



### 2.3 Takmarkanir og útilokanir


---

## 3. Samhengi viðskipta
### 3.1 Prófílar forgangs hagsmunaaðila 

Í þessu kerfi eru safngestir eini notendahópurinn sem er skráður sem forgangs hagsmunaaðili.

### Safngestir
- **Staða:** [x] Forgangs  [ ] Óæskilegir  [ ] Aðrir  [ ] Óbeinn  
- **Stærð:** ~[10.000 skráðir notendur, 300 á dag]  
- **Lýsing:** [Fólk pantar, skilar og endurnýjar bækur sjálft í gegnum kerfið. Markmið er að stuðla að einfaldleika og hraða í þjónustu]

| Hagsmunaaðili | Helsti ávinningur| Viðhorf |  Hagsmunir  | Takmarkanir  | 
|---------------|------------------|---------| ------------| ------------ | 
| **Safngestir**  | EInfaldari og hraðari þjónusta, minni biðtími, betri yfirsýn yfir lán, færri starfsmenn, sparnaður í rekstri| Jákvæð, kerfið sparar tíma og veitir frelsi. Sumir þurfa aðstoð til að læra á sjálfsafgreiðslukerfið í byrjun.  | Sjálfsafgreiðsla ( útlán, skil og endurnýjun), aðgengi að lánasögu, einfalt og skýrt viðmót, áminningar í tölvupósti um skiladag og gjöld | Það þarf að hafa í huga að kerfið styður við mismunandi aldurshópa, og notendaviðmót þarf að hafa íslensku, ensku og pólsku, þetta þarf einnig að vera aðgengilegt fyrir sjónskerta.| 







### 3.2 Forgangsröðun verkefnis 


### 3.3 Innleiðingarsjónarmið 


## Breytingasaga

PS C:\Users\rober\OneDrive\tolvur\Krofugreiningar-Verkefni-3>  git log -n 5 --pretty=format:"| %an | %ad | %s | %h |" --date=short -n 10 -- VISIONSCOPE.md 

| Author        | Date       | Message               | Commit   |
|---------------|------------|-----------------------|----------|
| Kristin111222 | 2025-10-03 | Update VISIONSCOPE.md | 9d2927e  |
| Kristin111222 | 2025-10-03 | Update VISIONSCOPE.md | 30c1678  |
| Kristin111222 | 2025-10-03 | Update VISIONSCOPE.md | 7d1b020  |
| Kristin111222 | 2025-10-03 | Update VISIONSCOPE.md | 08ba997  |
| Kristin111222 | 2025-10-03 | Update VISIONSCOPE.md | 0197cf4  |
| Kristin111222 | 2025-10-03 | Update VISIONSCOPE.md | 18a960d  |
| Kristin111222 | 2025-10-03 | Update VISIONSCOPE.md | e2f81e9  |
| Kristin111222 | 2025-10-03 | Update VISIONSCOPE.md | 7a20851  |
| Kristin111222 | 2025-10-02 | Update VISIONSCOPE.md | 0ff25df  |
| ArnthorAtli   | 2025-10-02 | 1.3 og 1.5            | 9cdd8d1  |


<!--
Í stað þess að halda utan um alla commit-sögu er aðeins skráð formleg útgáfa (milestones) með Git tags (merkjum).  
Hver lína í töflunni samsvarar tag (merki) sem hefur verið sett í Git repositoryið.
> 🔖 Revision History er viðhaldið með **Git tags**.  
> Þegar ný útgáfa (t.d. drög eða baseline) er tilbúin, búið til tag í Git (`git tag -a vX.Y -m "message" && git push origin vX.Y`)  
> sem bætir einni línu við í töfluna hér að neðan.
-->
> 🔖 Taflan hér á eftir er búin til með því að keyra shell skrána `updatevisionhistory.sh` í bash terminal
> 
>  `chmod +x updatevisionhistory.sh`
> 
>  `./updatevisionhistory.sh`
> 
>  Ef þú vilt skoða töfluna fyrst til að sjá hvernig hún kemur út geturðu gert eftirfarandi beint úr skelinni 
> `git log -n 5 --pretty=format:"| %an | %ad | %s | %h |" --date=short -n 10 -- VISIONSCOPE.md`


<!-- GIT_HISTORY_START -->
| Author | Date       | Message | Commit |
|--------|------------|---------|--------|
| Ebba Þóra Hvannberg | 2025-09-08 | fyrsta útgáfa og Revision history gert sjálfvirkt | 5b39409 |

<!-- GIT_HISTORY_END -->

> Skoða allt: `git log -- "VISIONSCOPE.md" `

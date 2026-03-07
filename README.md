# Lifeline or Trap? The Consequences of 'Vibe Coding' and Excessive Reliance on AI
*(Mentőöv vagy csapda? A "vibe coding" és a túlzott AI-hagyatkozás következményei)*

🌐 **A cikk hosztolt weboldala elérhető itt:** [https://olahsara.github.io/kutmod/](https://olahsara.github.io/kutmod/)

Projektünk a generatív mesterséges intelligencia (GenAI) programozás-oktatásra gyakorolt hatásait, különösen a "vibe coding" jelenségét és a kognitív tehermentesítés következményeit vizsgálja.

## 👥 Szerzők

* **Krémer Aliz** – a0tyh8@inf.elte.hu
* **Hősi Rezső Rudolf** – dov7lk@inf.elte.hu
* **Oláh Sára** – a4mrc6@inf.elte.hu

## 📌 A Kutatási Probléma

A kutatásunk középpontjában a **"Debugolási Paradoxon"** áll. Fennáll a veszélye, hogy a kezdő programozók a gyors promptolási sikerek miatt nem sajátítják el a mélyebb algoritmikus logikát, így eszköztelenné válnak a kód validálásakor és a komplex hibakeresés (debugging) során. 

Bár a vibe coding (amikor a fejlesztő a struktúra mély megértése nélkül, természetes nyelvi promptok alapján ír kódot) drasztikusan növeli az induló sebességet, kritikus töréspontot eredményez. Amint az AI elakad, hallucinál vagy egy komplex hibát vét (pl. elavult könyvtárak használata), a programozó egy általa nem értett kódhalmazzal marad magára, ami a frusztráció növekedéséhez és a feladat feladásához vezet.

## 🧪 Vizsgált Hipotézisek

A kísérletünk során az alábbi hipotéziseket (H1-H8) teszteljük, amelyek a tanulási, hibakeresési és kompetencia fázisokat fedik le:

*   **H1 (Felületes tanulás):** A hallgatók az AI eszközök használatával megkerülik a valódi, mély tanulási folyamatot, kiiktatva a készségek kialakulásához elengedhetetlen produktív küszködést.
*   **H2 (A kód meg nem értése):** Amikor a hallgatók az AI által generált kódot használják, gyakran egyáltalán nem értik annak működését, és kritika nélkül másolják be a megoldásokat.
*   **H3 (Láthatatlan hibák):** A felületes tanulás miatt a hallgatók teljesen eszköztelenek lesznek a hibák azonosításakor a felszínesen működőképesnek tűnő "kártyavár-kódokban".
*   **H4 (Túlzott ráhagyatkozás - Over-reliance):** A kezdők gyakran esnek a vak és túlzott ráhagyatkozás csapdájába, teljesen az AI-ra bízva a munkát.
*   **H5 (Architekturális vakság):** Háttértudás nélkül a kezdők összekavarodnak az alkalmazás rétegeiben; képtelenek integrálni az AI által külön-külön generált kódrészleteket, ami egy "foltozott" (patchwork) architektúrát eredményez.
*   **H6 (Prompt-hurok):** Amikor az AI elakad vagy hibázik, a hallgatók aránytalanul sokszor próbálják a problémát újabb promptokkal áthidalni, ahelyett, hogy a kódot manuálisan elolvasnák és értelmeznék.
*   **H7 (Mentális modell hiánya):** A kódírás AI-ra való teljes rábízása (cognitive offloading) meggátolja a kód mentális modelljének kialakulását, ellehetetlenítve a komplex hibák manuális validálását.
*   **H8 (Elmélyülő Szakadék - The Widening Gap):** A jobb alapkészségekkel rendelkező programozók hamarabb váltanak manuális debugolásra, míg a gyengébb képességű hallgatók túlzottan az AI-ra támaszkodnak, és hamarabb feladják a feladatot.

## 📋 Munkamegosztás

A cikk megírását és a kutatás lebonyolítását három fő tematikus felelősségi kör mentén osztottuk fel a logikai koherencia biztosítása érdekében:

**1. Szerző**
*   **Felelősség:** A Bevezetés és a Szakirodalmi áttekintés fejezetek megírása.
*   **Feladatok:** A "vibe coding" és a paradigmaváltás bemutatása, a kutatási probléma megalapozása, valamint a *Cognitive Offloading* (kognitív tehermentesítés) és az *Illusion of Competence* (illuzórikus kompetencia) elméleti hátterének kidolgozása.

**2. Szerző**
*   **Felelősség:** A Módszertan és az Eredmények (Hipotézisek elemzése) fejezetek megírása.
*   **Feladatok:** A kísérleti beállítás (szándékos hiba) dokumentálása, a metrikák (Persistence, Latency to Manual Shift, Frusztrációs skála) definíciója, és a kinyert adatok statisztikai bemutatása a hipotézisek klaszterei mentén.

**Krémer Aliz**
*   **Felelősség:** A Diszkusszió és a Konklúzió fejezetek megírása.
*   **Feladatok:** Az eredmények szakmai interpretálása (pl. statisztikai valószínűség vs. kauzalitás a debugolásban), a pedagógiai javaslatok (pl. AI-free alapozó szakaszok) megfogalmazása, és az "üvegplafon" effektus összegzése.

*Közös feladatok:* Az Absztrakt megírása, a LaTeX formázás, a `refs.bib` fájl karbantartása és a végső lektorálás.

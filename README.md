**📊 O projektu**

Cílem projektu bylo identifikovat klíčové rizikové faktory a na jejich základě navrhnout akční strategii pro stabilizaci klientské základny.

<img width="1681" height="911" alt="Dashboard, manazerske shrnuti" src="https://github.com/user-attachments/assets/ee345e4e-c732-431b-be6d-6942fc3bcd9b" />


**💡 Klíčová zjištění**

**1.) Kritické 3 měsíce:**

- největší riziko ztráty zákazníka hrozí hned v úvodu, protože v prvních 3 měsících odejde 58,06 % nově získaných mladých klientů

**2.) Past manuálních plateb:**

- měsíční tarify placené manuálně (elektronický šek) vykazují extrémní odchodovost 53,73 %

**3.) Nezbytnost technické podpory:**

- zákazníci s optickým internetem bez technické podpory odcházejí v 49,37 % případů (při aktivaci podpory číslo klesá na 22,63 %)

**4.) Ohrožený segment seniorů:**

- senioři odcházejí téměř dvakrát častěji (41,68 %) než mladší segment

### 🔍 Detailní sub-analýza: Vliv věku na chování klientů

<img width="2047" height="1147" alt="dashboard power bi" src="https://github.com/user-attachments/assets/1f50f733-b328-45c5-9929-e22fdf7fd743" />

**🚀 Doporučení pro byznys**

**1.) Automatizace od prvního dne:**

- eliminovat manuální platby a nastavit inkaso jako standardní metodu pro snížení každoměsíčního rozhodování o zrušení

**2.) Bezpečné balíčky:**

- optický internet nenabízet samostatně, ale rovnou v balíčku s technickou podporou a online bezpečnost

**3.) Onboarding:**

- intenzivně se zaměřit na retenční péči během prvních 90 dnů životního cyklu zákazníka

**4.) Zjednodušení pro seniory:**

- stabilizovat vysoký odliv starších ročníků například zjednodušením platebních metod a přidáním lidského přístupu na podpoře

**🛠 Technické zpracování**

- průzkumná analýza dat v Databricks, SQL (čištění, agregace, tvorba segmentů)

- vizualizace a reporting v Power BI (interaktivní dashboard)


### 📈 Fáze 2: Časová analýza, vývoj trendů a věková segmentace

V této fázi jsem se zaměřila na sledování vývoje odchodovosti v čase a na základě zpětné vazby jsem analýzu rozšířila o věkovou kategorii, což umožňuje cíleně sledovat rizikové skupiny.

**Klíčové kroky:**
- **Databricks (SQL):** Vytvořila jsem pokročilou agregovanou tabulku (optimalizace na 108 řádků kombinujících měsíce, úvazky, typ internetu a věkovou kategorii).
- **Power Query:** Provedla jsem transformaci dat, překlad hodnot na srozumitelné kategorie („Senioři“ / „Ostatní“) a ošetření formátů.
- **Power BI:** Sestavila jsem interaktivní spojnicový graf doplněný o věkový průřez a přesné DAX míry (vážená odchodovost a měsíční průměr klientů) pro správné fungování celkových i zafiltrovaných součtů.

**Ukázky interaktivního dashboardu:**

**1.) Celkový nezafiltrovaný pohled (základní přehled za celou klientskou základnu):**

<img width="1815" height="857" alt="Power Bi graf - bez filtrování, main" src="https://github.com/user-attachments/assets/6bc0daf9-586c-4d68-8678-fe26638ba658" />


**2.) Pohled na rizikový segment seniorů (se zaměřením na optický internet):**

<img width="1797" height="866" alt="Power Bi graf - senioři + optika" src="https://github.com/user-attachments/assets/f42d827f-9e10-4b5a-99f0-2d63638a0239" />





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


### 📈 Fáze 2: Časová analýza a vývoj trendů

V této fázi jsem se zaměřila na sledování vývoje odchodovosti v čase, což byznysu umožní vyhodnocovat úspěšnost budoucích retenčních kampaní.

**Klíčové kroky:**

- **Databricks (SQL):** Vytvořila jsem agregovanou tabulku pro optimalizaci výkonu (snížení na 54 klíčových řádků kombinujících měsíce, úvazky a typ internetu).
- **Power Query:** Provedla jsem lokální transformaci dat (oprava desetinných formátů) a kompletní překlad hodnot do češtiny pro čistý vizuál.
- **Power BI:** Sestavila jsem interaktivní spojnicový graf vývoje doplněný o kontextové KPI karty (celkový počet odchodů a objem klientů). Rizikové segmenty jsou vizuálně zvýrazněny korálovou barvou, stabilní úvazky ztlumeny do modré.

**Ukázky interaktivního dashboardu:**

**1.) Pohled na zákazníky s optickým internetem (Kritický segment):**

<img width="1912" height="850" alt="Power Bi graf - optika" src="https://github.com/user-attachments/assets/fcf909ae-c32d-4015-8864-dcd00821f463" />


**2.) Pohled na zákazníky s DSL připojením:**

<img width="1886" height="840" alt="Power Bi graf - DSL" src="https://github.com/user-attachments/assets/3942dcc4-ce81-485b-b8aa-8697580b5238" />


**3.) Pohled na zákazníky bez internetu:**

<img width="1931" height="857" alt="Power Bi graf - bez internetu" src="https://github.com/user-attachments/assets/c82b821e-03a9-4c33-9104-d18c4f973b28" />




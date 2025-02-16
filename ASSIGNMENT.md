# NNPIA – Zadání semestrální práce

Vytvoření webové aplikace, která demonstruje znalosti studenta v oblasti vývoje webových aplikací. Zaměření aplikace si student volí sám.

## Organizační požadavky
- **Povinná konzultace:** nejpozději do **6. týdne** semestru.
- **Termín odevzdání:** minimálně **2 dny před termínem zápočtu**, který si student zvolí.
- **Odevzdání repozitáře:** Přes GitHub classroom.
- **Dokumentace:** Součástí práce musí být stručná **README.md** dokumentace, která popisuje projekt, použitou technologii a návod na spuštění.

---

## Povinné požadavky

Pro uznání semestrální práce a získání zápočtu je nutné splnit následující požadavky:

### Backend (Spring Boot)
1. Použití **Spring Boot** jako backendového frameworku.
2. **Minimálně 3 datové entity** včetně vizualizace datových entit. Schéma může být vygenerováno pomoci IDE na základě již existujícího kódu.
3. **Spring JPA** pro práci s databází.
4. **Spring Security** pro autentizaci a autorizaci pomocí JWT tokenů.
5. **Vícevrstvá architektura** (Model, DAO/Repository, Service, Controller).
6. **Stránkování, řazení a vyhledávání** nad seznamem záznamů.

### Frontend (React.js)
8. Použití **React.js** nebo jiné knihovny pro tvorbu single page aplikace.
9. Aplikace musí obsahovat **minimálně 7 komponent**, a ideálně hooky.
10. Implementace alespoň jedné **znovupoužitelné komponenty** (např. data-grid, tabulka, filtr, modal apod.).

### Dodatečná netriviální funkcionalita
11. Student si zvolí jednu dodatečnou netriviální funkcionalitu dle svého uvážení. Funkcionalita může být vlastní, ale musí být konzultována předem. Možnosti zahrnují:

- Automatická tvorba Open API 3 dokumentace.
- Cashování REST API odpovědí za pomocí Redisu.
- Napojení na OpenAI API nebo jinou službu poskytující jazykové modely.
- Přihlašování pomocí SSO (Google, Microsoft...).
- Backend v jazyce Kotlin.
- Nasazení aplikace na produkční prostředí.
- Použití jiné knihovny než React.js pro tvorbu frontendu (musí být zachována single page aplikace).

### Obecné požadavky
12. Dodržování **principů čistého kódu** (čitelnost, struktura, názvy, formátování).
13. Semestrální práce musí splňovat single page application rendering pattern.
14. Studenti si sami vybírají vhodný typ databáze (relační, grafová, dokumentová). Výběr by měl odpovídat potřebám aplikace.

### Testování
15. **Minimálně 2 unit testy** na netriviální logiku/algoritmus.
16. **Minimálně 2 unit testy** controlleru (např. s využitím **MockMvc**).
17. **Minimálně 1 integrační test**, kde spolupracují alespoň 2 třídy servisní vrstvy (datová vrstva není mockovaná).

## Doporučený postup implementace
1. Promyslete si aplikační logiku.
2. Navrhněte datový model.
3. Maximálně využívejte AI služby, copilota a chatboty:

- Obzvláště pro repetativní úkoly, generování testů a psaní dokumentace.
- Ideálně si pro každý problém vytvořte nový chat, zadejte chytbotovi vhodnou roli a poskytněte mu dostatek kontextu.
- Nezapomínejte ale validovat výstupy a snažte se porozumět dané problematice.

4. Ideálně pracujte průběžně během semestru... Můžete použít kód ze cvičení jako základ.
5. Při řešení problémů aplikujte dekompozici.
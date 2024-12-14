 Propojení s GitHubem výrazně usnadňuje správu projektů a verzování. Níže je jednoduchý návod a doporučení, jak efektivně používat **VS Code** s **GitHubem**:

---

### **1. Přihlášení ke GitHubu z VS Code**
1. Otevřete VS Code.
2. Klikněte na ikonu **Správa zdrojového kódu** (ikona větve) na levé straně.
3. Zvolte **Publikovat na GitHub**.
4. Budete přesměrováni na GitHub, kde povolíte přístup.

Po přihlášení bude GitHub propojen s VS Code, což umožní snadnější klonování a spravování repozitářů.
Můžete si to ověřit přes kliknutí na ikonu **Účty** v levém dolním rohu.

---

### **2. Založení repozitáře**
1. Repositář lze založit přímo na github.com ve vašem účtu - stránka home, levý panel, apod.
2. Repozitář může být veřejný (viditelný komukoliv na internetu) nebo soukromý.

---

### **3. Klonování repozitáře z GitHubu**
1. Na GitHubu si vyberte repozitář, který chcete klonovat.
2. Klikněte na tlačítko **Code** a zkopírujte HTTPS nebo SSH odkaz.
3. Ve VS Code:
   - Otevřete **Zobrazit -> Paleta příkazů...** (Ctrl+Shift+P).
   - Napište a vyberte **Git: Klonovat**.
   - Vložte odkaz na repozitář a zvolte složku, kam se má projekt uložit.
   (Vytvoří se tím nová podsložka s názvem repozitáře.)
4. Ve VS Code také můžete:
   - Zavřít aktuální složku, pokud ji máte otevřenou.
   - Na obrazovce Welcom vyberte **Klonovat úložiště Git...**.
   - Vložte odkaz na repozitář a zvolte složku, kam se má projekt uložit.
   (Vytvoří se tím nová podsložka s názvem repozitáře.)
5. Po klonování se otevře nový projekt v editoru.


---

### **3. Práce s Git přímo ve VS Code**
VS Code má integrované nástroje pro Git:
- **Správa zdrojového kódu:**
  1. Klikněte na ikonu **Správa zdrojového kódu** (ikona větve) na levé straně.
  2. Přidejte změněné soubory  tlačitkem **+** (budou ve připravených - staged).
  3. Napište zprávu pro danou změnu.
  4. Klikněte na **Potvrdit**.
- **Grafu správy zdrojového souboru:**
  - Pro nahrání změn na GitHub klikněte na tlačítko **Nasdílení změn** (ikona šipky "z kolečka nahoru").
  - Pro přijetí změn z GitHubu klikněte na tlačítko **Přijetí změn** (ikona šipky "z kolečka dolů")
- **Pokročilé - vytváření větví:**  
  - Vlevo dole klikněte na název aktuální větve a zvolte **Vytvořit novou větev**.
- **Pokročilé - sloučení větví (Merge):**  
  - Vytvořte pull request na GitHubu, nebo použijte příkaz **Git: Sloučit...**.

---

### **4. Doporučené workflow**
#### **Jednoduchý projekt**
1. **Založení repozitáře na GitHubu**
   - viz sekce 2. výše
2. **Naklonování repozitáře z GitHubu**
   - viz sekce 3. výše
3. **Práce s Git:**
   - Vytvoření README.md, kde se napíše krátký popis projektu
   - Vytvoření prvního commitu (uložení změn) po inicializaci.
   - Pravidelné commitování změn s jasnými zprávami (např. `Přidán HTML základ`).
   - Na GitHub se synchronizuje pomocí **Nasdílení změn (Push)**.
   - Z GitHubu se přijmou změny pomocí **Přijetí změn (Pull)**.

---

### **5. Doporučení pro efektivní práci**
- **Pravidelné commitování:**  
  Je vhodné zapisovat malé, jasně popsané změny. Je snazší opravit chybu, když je změna malá.
- **Popisné zprávy commitů:**
  Např. místo „Upraveno“ raději „Opraveno chybné zobrazení tabulky v HTML“.

---

### **6. Řešení konfliktů**
1. Pokud dojde ke konfliktu (např. dva žáci upraví stejný soubor), Git upozorní na nutnost ručního sloučení.
2. Ve VS Code jsou konfliktní části označeny přímo v editoru, žáci mohou:
   - Vybrat jednu z verzí (naše / jejich).
   - Sloučit změny manuálně.

---

### **7. Volitelná instalace rozšíření**
Pro pokročilou spolupráci VS Code s GitHubem lze nainstalovat následující rozšíření:
1. **GitLens**  
   - Přidává pokročilé funkce pro práci s Gitem, jako je historie změn nebo informace o autorech jednotlivých řádků.
2. **GitHub Pull Requests and Issues**
    - Umožňuje žákům spravovat pull requesty a issue přímo z VS Code.
    - Instalace: Otevřete Extensions (Ctrl+Shift+X) a vyhledejte "GitHub Pull Requests and Issues".
3. **Live Share** 
   - Pokud pracujete ve skupinách, Live Share umožní sdílet kód a spolupracovat v reálném čase.

---

### **8. Odkazy na výukové materiály**
- [Oficiální GitHub dokumentace](https://docs.github.com/)
- [Základy Gitu a GitHubu (YouTube)](https://www.youtube.com/results?search_query=základy+git+cz)
- [GitHub Learning Lab](https://lab.github.com/) – interaktivní tutoriály.

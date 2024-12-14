### **Tahák pro práci s Git**  
Zde je jednoduchý přehled nejčastěji používaných příkazů v Gitu. Tento tahák lze využít jako rychlou referenci při práci na projektu.

---

### **1. Inicializace Git repozitáře**
- **Vytvoření nového repozitáře v aktuální složce:**  
  ```bash
  git init
  ```

---

### **2. Kontrola stavu**
- **Zobrazení stavu repozitáře (co je změněno, přidáno, nebo chybí v commitu):**  
  ```bash
  git status
  ```

---

### **3. Přidání souborů ke sledování (staging area)**
- **Přidání jednoho konkrétního souboru:**  
  ```bash
  git add <název_souboru>
  ```  
- **Přidání všech změněných souborů najednou:**  
  ```bash
  git add .
  ```

---

### **4. Commit změn**
- **Vytvoření nového commitu s popisem:**  
  ```bash
  git commit -m "Popis změn"
  ```

---

### **5. Propojení s GitHubem**  
- **Přidání vzdáleného repozitáře:**  
  ```bash
  git remote add origin <URL_repo>
  ```  
- **Nastavení hlavní větve (pokud je potřeba):**  
  ```bash
  git branch -M main
  ```  
- **První push (odeslání změn na GitHub):**  
  ```bash
  git push -u origin main
  ```

---

### **6. Práce s GitHubem**
- **Odeslání změn na vzdálený repozitář (po commitu):**  
  ```bash
  git push
  ```
- **Stažení nejnovějších změn z GitHubu:**  
  ```bash
  git pull
  ```

---

### **7. Zobrazení historie změn**
- **Zobrazení logu commitů:**  
  ```bash
  git log
  ```
- **Zobrazení zjednodušeného logu:**  
  ```bash
  git log --oneline
  ```

---

### **8. Odstranění ze staging area**
- **Vrácení souboru z „staging area“ zpět k úpravám:**  
  ```bash
  git reset <název_souboru>
  ```
- **Vrácení všech souborů z „staging area“:**  
  ```bash
  git reset
  ```

---

### **9. Smazání posledního commitu (pozor!)**
- **Zachování změn ve složce:**  
  ```bash
  git reset --soft HEAD~1
  ```
- **Zahození změn ve složce:**  
  ```bash
  git reset --hard HEAD~1
  ```

---

### **10. Vytvoření nové větve**
- **Vytvoření nové větve:**  
  ```bash
  git branch <název_větve>
  ```
- **Přepnutí na jinou větev:**  
  ```bash
  git checkout <název_větve>
  ```

---

### **11. Sloučení větví (merge)**
- **Sloučení jiné větve do aktuální větve:**  
  ```bash
  git merge <název_větve>
  ```

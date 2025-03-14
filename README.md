# Czechitas DA: Materiály pro Python kurz datové analýzy

Tento repozitář obsahuje výukové materiály a zdroje pro kurz Datové analýzy od Czechitas. 

## 📚 Obsah kurzu

Kurz je rozdělen do několika klíčových modulů:

1. **Základy Pandas** (`01-pandas/`)
   - Úvod do manipulace s daty pomocí Pandas
   - Základní operace

2. **Pokročilý Pandas** (`02-pandas-2/`)
   - Pokročilé techniky manipulace s daty
   - Transformace dat

3. **Regulární výrazy** (`03-regularni-vyrazy/`)
   - Vyhledávání vzorů v textu
   - Čištění a validace dat

4. **Web Scraping** (`04-web-scraping/`)
   - Získávání dat z webových stránek
   - Práce s webovými zdroji dat

## 📝 Další zdroje

Repozitář obsahuje několik užitečných průvodců a tutoriálů:

- `pandas-vs-sql.md` - Srovnání operací v Pandas a SQL
- `odkazovani-na-soubory.md` - Průvodce odkazováním na soubory
- `ssl-troubles.md` - Řešení problémů s SSL připojením
- `zavorky-python.ipynb` - Průvodce závorkami a syntaxí v Pythonu

## 🛠️ Instalace a nastavení

### Nastavení projektu

1. Instalace potřebných balíčků:

   Budeme instalovat tyto Python balíčky:
   - **pandas**: Hlavní knihovna pro analýzu dat - umožňuje načítat, upravovat a analyzovat data v tabulkové podobě
   - **jupyter**: Interaktivní prostředí pro psaní a spouštění Python kódu, vytváření vizualizací a dokumentace
   - **requests**: Knihovna pro stahování dat z internetu a práci s webovými API
   - **beautifulsoup4**: Nástroj pro parsování HTML a XML souborů, používá se pro web scraping (získávání dat z webových stránek)

   #### Windows
   1. Otevřete příkazový řádek (CMD):
      - Stiskněte `Win + R`
      - Napište `cmd` a stiskněte Enter
      - nebo vyhledejte "Příkazový řádek" v nabídce Start

   2. Spusťte instalační příkaz:
      ```bash
      pip install pandas jupyter requests beautifulsoup4
      ```

   3. Ověření instalace:
      ```bash
      python -c "import pandas; print(f'Pandas verze: {pandas.__version__}')"
      python -c "import jupyter; print('Jupyter je nainstalován')"
      ```

   #### macOS
   1. Otevřete Terminál:
      - Stiskněte `Cmd + Space`
      - Napište "Terminal" a stiskněte Enter

   2. Spusťte instalační příkaz:
      ```bash
      pip3 install pandas jupyter requests beautifulsoup4 
      ```

   3. Ověření instalace:
      ```bash
      python3 -c "import pandas; print(f'Pandas verze: {pandas.__version__}')"
      python3 -c "import jupyter; print('Jupyter je nainstalován')"
      ```

   Pokud se při ověření zobrazí verze knihoven a žádné chybové hlášky, instalace proběhla úspěšně! 🎉


2. Stáhněte tento repozitář:
   - Klikněte na zelené tlačítko "Code" nahoře
   - Vyberte "Download ZIP"
   - Rozbalte stažený soubor do vámi vybrané složky
   
   nebo použijte git (pokud ho máte nainstalovaný):
   ```bash
   git clone https://github.com/AnetaPopelova/czechitas-da-data.git
   ```

### Spuštění Jupyter Notebook

Máte dvě možnosti:

1. **Přes VS Code** (doporučeno pro začátečníky):
   - Otevřete složku projektu ve VS Code
   - Otevřete kterýkoliv `.ipynb` soubor
   - Když VS Code nabídne instalaci Jupyter rozšíření, potvrďte
   - V pravém horním rohu vyberte Python interpreter
   - Úspěšné spuštění poznáte podle:
     - V pravém horním rohu se zobrazí "Select Kernel"
     - Po výběru kernelu se objeví tlačítka pro spouštění buněk
     - První buňka půjde spustit pomocí "Run" tlačítka nebo `Shift + Enter`

2. **Přes prohlížeč**:
   - Otevřete příkazový řádek/terminál (viz výše)
   - Přejděte do složky s projektem pomocí příkazu `cd cesta/k/projektu`
   - Spusťte Jupyter:
     ```bash
     jupyter notebook
     ```
   - Úspěšné spuštění poznáte podle:
     - Automaticky se otevře prohlížeč s adresou začínající `http://localhost:8888`
     - Uvidíte seznam souborů ve vaší složce
     - Můžete kliknout na `.ipynb` soubor pro jeho otevření

## ❗ Časté problémy a řešení

1. **SSL Certifikáty**: Viz `ssl-troubles.md`

2. **Jupyter se nespouští**: 
   - Zkuste reinstalaci:
     ```bash
     # Windows
     pip uninstall jupyter
     pip install jupyter

     # macOS
     pip3 uninstall jupyter
     pip3 install jupyter
     ```
   - Ověřte instalaci:
     ```bash
     jupyter --version
     ```

3. **Python není nalezen**: 
   - Windows: 
     - Otevřete Nastavení systému → Systém → O systému → Upřesňující nastavení systému
     - Klikněte na "Proměnné prostředí"
     - V sekci "Systémové proměnné" najděte "Path"
     - Zkontrolujte, zda obsahuje cestu k Pythonu (např. `C:\Python39`)
   - macOS: 
     - Zkuste použít `pip3` místo `pip`
     - Ověřte instalaci Pythonu: `which python3`

## 🆘 Podpora

- Dotazy ke kurzu směřujte na Discord

## 📄 Licence

Tento materiál je poskytován pro vzdělávací účely jako součást kurzu Digitální akademie: DATA od Czechitas.
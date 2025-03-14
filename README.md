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

1. Stáhněte tento repozitář:
   - Klikněte na zelené tlačítko "Code" nahoře
   - Vyberte "Download ZIP"
   - Rozbalte stažený soubor do vámi vybrané složky
   
   nebo použijte git (pokud ho máte nainstalovaný):
   ```bash
   git clone https://github.com/AnetaPopelova/czechitas-da-data.git
   ```

2. Nainstalujte potřebné balíčky:
   ```bash
   # Windows
   pip install pandas jupyter requests beautifulsoup4 matplotlib

   # macOS
   pip3 install pandas jupyter requests beautifulsoup4 matplotlib
   ```

### Spuštění Jupyter Notebook

Máte dvě možnosti:

1. **Přes VS Code** (doporučeno pro začátečníky):
   - Otevřete složku projektu ve VS Code
   - Otevřete kterýkoliv `.ipynb` soubor
   - Když VS Code nabídne instalaci Jupyter rozšíření, potvrďte
   - V pravém horním rohu vyberte Python interpreter

2. **Přes prohlížeč**:
   ```bash
   jupyter notebook
   ```
   - Automaticky se otevře prohlížeč s Jupyter rozhraním
   - Vyberte notebook, který chcete otevřít


## ❗ Časté problémy a řešení

1. **SSL Certifikáty**: Viz `ssl-troubles.md`
2. **Jupyter se nespouští**: Zkontrolujte instalaci pomocí:
   ```bash
   pip install --upgrade jupyter
   ```
3. **Python není nalezen**: 
   - Windows: Zkontrolujte, zda je Python přidán do PATH
   - macOS: Zkuste použít `pip3` místo `pip`

## 🆘 Podpora

- Dotazy ke kurzu směřujte na Discord

## 📄 Licence

Tento materiál je poskytován pro vzdělávací účely jako součást kurzu Digitální akademie: DATA od Czechitas.
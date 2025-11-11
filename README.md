# 🧩 Manipulace s 2D seznamy – VOŠ AIT2023

Repozitář obsahuje soubory k úkolu **druhé lekce programování** zaměřené na práci s dvourozměrnými strukturami v Pythonu.  
Cílem bylo vytvořit a otestovat funkce ze souboru `list_2D_manipulator.py`.

---

## 📚 Struktura projektu

📂 Manipulace s daty
│
├── list_2D_manipulator.py # hlavní soubor s implementací funkcí
├── osutils.py # pomocné nástroje pro práci se soubory
├── utils.py # pomocné funkce pro práci s daty
├── data_*.py # volitelné datové soubory pro testování
└── test_list2d_Augusta.py # unit testy vytvořené mnou

---

## 🎯 Zadání

Vytvořit **unit testy** pro čtyři funkce z modulu `list_2D_manipulator.py`:

| Student | Funkce |
|----------|--------|
| **Daniel Augusta** | `sort_by_col`, `col_names_from_firts_row`, `deflatten_list_2D`, `replace_values_in_col_by_dict` |

---

## 🧪 Testování

Testy jsou implementovány pomocí standardní knihovny **`unittest`**.  
Každá testovaná funkce má vlastní třídu se dvěma testovacími metodami.

### Spuštění testů
Z adresáře s projektem spusť:
python -m unittest test_list2d_Augusta.py

Očekávaný výstup
........
----------------------------------------------------------------------
Ran 8 tests in 0.001s

OK

🧠 Popis testovaných funkcí
Funkce	Popis
sort_by_col	Třídí dvourozměrný seznam podle hodnot ve zvoleném sloupci (indexem).
col_names_from_firts_row	Oddělí první řádek jako hlavičku, ověří její správnost a vrátí data bez ní.
deflatten_list_2D	Převede jednorozměrný seznam na 2D seznam, kde každý prvek je samostatný list.
replace_values_in_col_by_dict	Nahrazuje hodnoty v zadaném sloupci podle mapovacího slovníku.


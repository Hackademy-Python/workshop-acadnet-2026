# Bun venit la workshop-ul Hackademy de Introducere în Python, ediția 2026! 

Acest workshop este conceput pentru a te introduce în universul programării cu Python, trecând rapid de la conceptele de bază (sintaxă, structuri de control) la instrumente profesionale de analiză și vizualizare a datelor precum **Pandas**, **Numpy** și **Matplotlib**.

---

## Ghid de Setup ( daca nu este deja )

Urmează acești pași pentru a-ți pregăti mediul de lucru înainte de a începe:

1. Instalări de bază

* **Python:** Descarcă și instalează ultima versiune de pe [python.org](https://www.python.org/). **IMPORTANT:** Bifează căsuța `Add Python to PATH` în timpul instalării.
* **Git:** Descarcă și instalează Git de pe [git-scm.com](https://git-scm.com/).
* **VS Code:** Descarcă și instalează [Visual Studio Code](https://code.visualstudio.com/). Din meniul *Extensions*, instalează extensiile oficiale **Python** și **Jupyter**.

2. Preluarea proiectului

Deschide un terminal (sau Command Prompt) și rulează:
```bash
git clone -b elevi [https://github.com/Hackademy-Python/workshop-acadnet-2026.git](https://github.com/Hackademy-Python/workshop-acadnet-2026.git)
cd workshop-acadnet-2026

3. Configurarea mediului virtual (venv)

În folderul proiectului, rulează:

# Crearea mediului
python -m venv venv

# Activarea (Windows)
.\venv\Scripts\activate

# Activarea (macOS/Linux)
source venv/bin/activate

4. Instalarea dependențelor

Cu mediul activat, instalează toate librăriile necesare dintr-o singură comandă:

pip install -r requirements.txt

5. Start!

    Deschide folderul în VS Code: code .

    Deschide fișierul Workshop_introducere.ipynb.

    Selectează kernel-ul (colțul dreapta-sus) și alege mediul tău virtual (venv).

    Asigură-te că fișierul housing.csv este în același folder.

Succes la codat! 

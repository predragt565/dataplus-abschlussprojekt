
# Abschlussprojekt Datenanalyst

Dieses Repository enthält verschiedene Materialien und Ressourcen rund um das **Abschlussprojekt**.
Hier findest du Code-Beispiele, Erklärungen und Dokumentationen zum Abschlussprojekt


## Thema des Projekts:
Dieses zweiteilige Projekt konzentriert sich auf die Analyse von Daten zu Übernachtungstrends in ausgewählten EU-Ländern im Zeitraum von 2012 bis 2025 in Bezug auf die durchschnittliche Temperaturveränderung im selben Zeitraum.  

**Beobachteter Zeitraum:**  2012 – 2025  

**Geografische Abgrenzung:** Mittelmeerländer (Spanien, Portugal, Italien, Kroatien, Griechenland), Deutschland und skandinavische Länder (Dänemark, Norwegen, Schweden, Finnland)  

**Kategorien:** Land/Region, Aufenthaltsland, Unterkunftsart  

**Datenquellen:**  
**Teil 1:** 🌡️ [Durchschnittstemperaturen in Europa – ERA5 Copernicus Daten-Download-Tool](https://cds.climate.copernicus.eu/datasets/reanalysis-era5-single-levels-monthly-means?tab=overview)  
**Teil 2:** 🌍 [Übernachtungen in der EU – Eurostat Datensatz-Download-Tool](https://ec.europa.eu/eurostat/)  

Abschließende Berichte öffentlich verfügbar unter:  
**Teil 1:** 🐍 [Kaggle Jupyter Notebook](https://www.kaggle.com/code/predragtrikic/average-monthly-temperature-change-in-eu-2012-2025)  
**Teil 2:** 📊 [Power BI App](https://app.powerbi.com/Redirect?action=OpenApp&appId=7ade7080-799f-412d-b483-0652313c8615&ctid=3f997f44-998e-40ab-a814-4db66712c837&experience=power-bi)

### Built with
[![Python][Python]][Python-url]
[![Power BI]][Power BI-url]
[![Jupyter]][Jupyter-url]



# Erste Schritte

*Windows*

- Python 3 oder höhere Version installieren
- Repository klonen:
  
  git clone  `git@github.com:predragt565/dataplus-abschlussprojekt.git` <project_name>
  
- Gehe dann in das Projektverzeichnis:
  
  cd <project_name>
  
- Virtuele Entwicklungsumgebung erstellen:
  
  python -m venv .venv
  
- Virtuele Entwicklungsumgebung aktivieren:
  
  .venv\Scripts\activate  
  
- Abhängigkeiten installieren:
  
  pip install -r requirements.txt
  

*MacOS*

- Python 3 oder höhere Version installieren
- Repository klonen:
  
  git clone  `git@github.com:predragt565/dataplus-abschlussprojekt.git` <project_name>
  
- Gehe dann in das Projektverzeichnis:
  
  cd <project_name>
  
- Virtuele Entwicklungsumgebung erstellen:
  
  python3 -m venv .venv
  
- Virtuele Entwicklungsumgebung aktivieren:
  
  source .venv/bin/activate 
  
- Abhängigkeiten installieren:
  
  pip install -r requirements.txt

<p align="right">(<a href="#readme-top">back to top</a>)</p>


# Zweite Schritte - Berichtsablauf

### Teil 1 – Analyse der durchschnittlichen Temperatur

- Laden Sie die folgenden Dateien in denselben Ordner herunter:  
    - average_monthly_temp_change_eu_2011.ipynb  
    - estat_tour_overnight_stays_eu10.ipynb  
    - copernicus_cds_climate_data_avgmotemp_0000h_eu_2011-2025.grib  
    - Drei PNG-Bilder mit dem Namen 'copernicus_map_eu_temp_0000h… .png'  

- Führen Sie das Jupyter Notebook *'average_monthly_temp_change_eu_2011'* in Visual Studio Code aus.  
- Als Ergebnis werden folgende CSV-Dateien erstellt:
    - copernicus_cds_climate_data_avgmotemp_eu_2011-2025.csv (Temperaturdaten)
    - monthly_avg_temp_change_eu_2012_2025.csv (Quelltabelle 1 für Power BI Bericht)

- Die Online-Version des Berichts ist verfügbar unter [Kaggle seite](https://www.kaggle.com/code/predragtrikic/average-monthly-temperature-change-in-eu-2012-2025)

### Teil 2 – Analyse der Übernachtungstrends im EU-Tourismus

- Führen Sie das Jupyter Notebook *'estat_tour_overnight_stays_eu10'* aus.
- Als Ergebnis wird folgende CSV-Datei erstellt:
    - estat_tour_overnight_stays_2012-2025_eu10_de.csv (Quelltabelle 2 für Power BI Bericht)

- Speichern Sie die beiden Quell-CSV-Tabellen im entsprechenden Ordner zusammen mit der Power BI Datei.

- Öffnen Sie die Power BI Berichtsdatei und aktualisieren Sie die Verknüpfungen zu den Quelltabellen.

- Aktualisieren Sie die Daten über Power Query.

- Aktualisieren Sie die Visualisierungen – und viel Spaß beim Erkunden der Diagramme!

- Die Online-Version des Power BI Berichts ist verfügbar unter [Power BI Report](https://app.powerbi.com/Redirect?action=OpenApp&appId=7ade7080-799f-412d-b483-0652313c8615&ctid=3f997f44-998e-40ab-a814-4db66712c837&experience=power-bi)



<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

- Für Teil 1, den Temperaturanalysebericht, führen Sie die Jupyter-Notebook-Datei direkt in Visual Studio Code aus.

- Für Teil 2, Eurostat Übernachtungentrend Bericht, verwenden Sie den URL-Link zum Power BI App Online-Dienst.


<!--Open localhost with the port 5172: http://localhost:5173/<br>
In your case the port could be different.-->


<!-- CONTACT -->

## Contact

[@LinkedIn](https://www.linkedin.com/in/predrag-trikic-6696a429/)

[@Kaggle](https://www.kaggle.com/predragtrikic)

<!-- ACKNOWLEDGMENTS -->

## Useful information

- [React Documentation](https://react.dev/learn/installation)
- [Flask Documentation](https://flask.palletsprojects.com/en/3.0.x/)
- [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS)
- [VITE](https://vitejs.dev/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com
[Flask]: https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white
[Flask-url]: https://flask.palletsprojects.com/en/3.0.x/
[Chakra]: https://img.shields.io/badge/chakra-%234ED1C5.svg?style=for-the-badge&logo=chakraui&logoColor=white
[Chakra-url]: https://v2.chakra-ui.com/
[JavaScript]: https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E
[JavaScript-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript
[Python]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[Python-url]: https://www.python.org/
[Vite]: https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white
[Vite-url]: https://vitejs.dev/
[Render]: https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white
[Render-url]: https://render.com/
[Power BI]: https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=white  
[Power BI-url]: https://powerbi.microsoft.com/
[Jupyter]: https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white  
[Jupyter-url]: https://jupyter.org/

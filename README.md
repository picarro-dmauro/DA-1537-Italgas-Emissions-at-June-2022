# DA1285-Italgas-emissions
Italgas Emissions for 2022 until 31 May
1. Assign customer name, "italgas" or "toscana energia", to `CUSTOMER` in 'config.py'
2. Also assign `FINAL_REPORTS_PATH` and `FINAL_REPORT_COLUMN` in 'config.py'
3. Run 'get-emissions-sources.ipynb'
4. Run 'check-if-lateral-wind-correction-is-needed.ipynb'
5. If lateral wind correction is needed, update peak emissions, otherwise skip ahead:
    1. Run 'correct-lateral-wind-speed.ipynb'
    2. Run 're-calculate-emission-rates.ipynb'
6. Run 'prepare-leaks-with-emission-sources.ipynb'  # Add the Practica Sprint query
7. Run 'determine-emission-factors.ipynb' 

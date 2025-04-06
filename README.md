# DP-203_Lab3
# 💼 Lab 3 - Bestanden transformeren met behulp van een serverloze SQL-pool

Dit project maakt deel uit van de Microsoft DP-203 Data Engineering cursus en richt zich op het transformeren van gegevens in bestanden via een **serverloze SQL-pool** binnen **Azure Synapse Analytics**.

---

## 🔍 Overzicht

In deze lab leer je hoe je:

- Een **Azure Synapse Analytics-werkruimte** opzet met toegang tot een **Data Lake**.
- Gegevens in **CSV-bestanden** analyseert met **SQL-query’s**.
- Transformaties uitvoert en resultaten opslaat in **Parquet-bestanden** via een **CETAS-query** (CREATE EXTERNAL TABLE AS SELECT).
- Een **opgeslagen procedure** maakt om transformaties te automatiseren.
- Alles beheert via **Synapse Studio** in de Azure-portal.

---

## ⚙️ Benodigdheden

- Een actieve **Azure-abonnement** met beheerdersrechten.
- Basiskennis van Azure Portal, PowerShell en SQL.
- Een browser en internetverbinding.

---

## 🧭 Stappen in deze lab

1. **Voorbereiding:**
   - Start de **Azure Cloud Shell** in PowerShell-modus.
   - Clone de oefenrepository.
   - Voer een script uit om automatisch een werkruimte en opslagaccount aan te maken.

2. **Bestanden verkennen in Data Lake:**
   - Open **Synapse Studio**.
   - Bekijk de CSV-bestanden in de map `sales/csv` binnen je gekoppelde opslagaccount.

3. **Gegevens verkennen met SQL:**
   - Gebruik een SQL-script om de eerste regels van de CSV-bestanden op te halen.
   - Analyseer verkoopgegevens zoals product, hoeveelheid en inkomsten.

4. **Transformatie uitvoeren:**
   - Maak een nieuwe database.
   - Definieer een externe gegevensbron en bestandsformaat.
   - Genereer een extern bestand met geaggregeerde verkoopgegevens.

5. **Automatisering met een opgeslagen procedure:**
   - Bouw een **stored procedure** die verkoop per jaar groepeert.
   - Voer de procedure uit en bekijk het gegenereerde resultaat in Data Lake.
   - Let op: verwijder handmatig oude gegevens voordat je de procedure opnieuw uitvoert.

6. **Opruimen:**
   - Verwijder de resourcegroep in de Azure Portal om kosten te voorkomen.

---

## 📁 Structuur van de bestanden

## 📚 Bronnen

- [Microsoft Learn - DP-203 cursus](https://learn.microsoft.com/nl-nl/training/paths/data-engineering/)
- [Azure Synapse Analytics documentatie](https://learn.microsoft.com/nl-nl/azure/synapse-analytics/)
- [Serverless SQL pools in Synapse](https://learn.microsoft.com/nl-nl/azure/synapse-analytics/sql/on-demand-overview)

---

## 👤 Auteur

Deze lab is uitgevoerd als onderdeel van de officiële DP-203 training.  
Gemaakt en gedeeld door: **[Zehra Okay]


![Schermafbeelding 2025-04-06 140340](https://github.com/user-attachments/assets/df629482-9efd-4057-9e78-926806a2f20d)
![Schermafbeelding 2025-04-06 140356](https://github.com/user-attachments/assets/765df58c-9fc3-482f-b5cc-1f3b2aa15838)
![Schermafbeelding 2025-04-06 140432](https://github.com/user-attachments/assets/aa4516af-ae94-4a0d-8947-3ec15d944fc1)
![Schermafbeelding 2025-04-06 140703](https://github.com/user-attachments/assets/c165ddce-946a-4fc3-9f8a-6d90068a3d57)
![Schermafbeelding 2025-04-06 140808](https://github.com/user-attachments/assets/33ab97c0-9058-4287-9561-a30925fa88f6)
![Schermafbeelding 2025-04-06 144857](https://github.com/user-attachments/assets/e4c6dd23-de8f-4c25-b7e3-e314295e9cdd)
![Schermafbeelding 2025-04-06 145533](https://github.com/user-attachments/assets/58f69195-d458-401a-9758-63c64626db0e)
![Schermafbeelding 2025-04-06 150355](https://github.com/user-attachments/assets/d09cb6ab-1256-4d7f-ae04-1697a1725374)
![Schermafbeelding 2025-04-06 150737](https://github.com/user-attachments/assets/351c253e-dec3-4e59-a5ff-7feee0525764)
![Schermafbeelding 2025-04-06 151235](https://github.com/user-attachments/assets/5bf71a01-8d8e-4de3-9128-93c5f7065519)








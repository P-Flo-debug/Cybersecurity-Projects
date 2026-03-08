# Digital Forensics: Enron Email Analysis (Kenneth Lay Corpus)

## Objective
The goal of this investigation was to utilize **Autopsy 4.22.1** to analyze the email communications of Kenneth Lay (former Enron CEO) to identify evidence of insider trading, declining company morale, and executive awareness of financial instability.

## Methodology
1. **Data Acquisition:** Imported the `Kenneth Lay.pst` logical data source into Autopsy.
2. **Analysis:** Configured ingest modules to process metadata and index email content.
3. **Investigation:** Performed targeted keyword searches for terms such as: `trade`, `stock`, `money`, `morale`, and `whistleblower`.
4. **Timeline Reconstruction:** Analyzed email timestamps to compare internal executive messaging against public statements.

## Key Findings
* **Insider Perspectives:** Identified external emails (e.g., KC Hatcher) highlighting the public's perception of Lay's $100M stock sale.
* **Internal Morale:** Discovered direct employee communications (e.g., Stephen Perich) regarding extreme stress and falling company morale.
* **Tool Proficiency:** Successfully navigated Autopsy's keyword hits and metadata views to filter high-volume data into actionable evidence.

## Deliverables
* **[Full Forensic Report](./Enron_Forensics_Analysis_Report.pdf)** (Renamed your PDF)

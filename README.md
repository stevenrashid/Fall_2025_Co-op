# Fall 2025 Co-op Portfolio

A collection of engineering-analysis and data-visualization work assembled around my Fall 2025 University of Cincinnati CEAS co-op portfolio. It brings together project code, presentations, spreadsheets, and analytical outputs.

## Explore by project

| Folder | Focus | Starting point |
| --- | --- | --- |
| [Engineering-Project](Engineering-Project/) | Tidal-turbine analysis for a Savoonga, Alaska engineering project | [Final presentation](Engineering-Project/Team%2010%20Engineering%20Project%20final.pptx) and [Python program](Engineering-Project/main.py) |
| [IBM-Cert](IBM-Cert/) | Data-analysis coursework, chart exports, and dashboard screenshots | [Capstone presentation](IBM-Cert/IBM%20DATA%20ANALYST%20CAPSTONE%20PROJECT.pptx) |
| [Ohio-export-trade-gap](Ohio-export-trade-gap/) | Ohio export performance and proposed trade-data automation | [Export gap presentation](Ohio-export-trade-gap/OHIO%20EXPORT%20GAP%20ANALYZER.pptx) |

## Run the engineering visualization

Use Python 3 with pandas, Matplotlib, and openpyxl. Run from the engineering folder so the program can locate its spreadsheet.

```bash
git clone https://github.com/stevenrashid/Fall_2025_Co-op.git
cd Fall_2025_Co-op/Engineering-Project
python -m pip install pandas matplotlib openpyxl
python main.py
```

The menu offers turbine power/cost comparisons, diesel-replacement scenarios, and a blade-material energy-return comparison. It reads numeric cost and annual-generation values from `Test.xlsx`, sheet `Sheet1`, columns B and E, at zero-based row positions 1–10.

## Viewing the other materials

Download the PowerPoint files to view the presentations, or browse the PNG charts directly on GitHub. The IBM and Ohio export folders contain presentation/output artifacts; they do not include the complete analysis pipelines.

## Interpretation notes

The engineering model uses fixed assumptions and simple cost ratios. Its research notes and code differ on benchmark costs, and one energy-axis label needs unit reconciliation before quantitative reuse.

The Ohio presentation separates completed analysis from a proposed automation architecture. This portfolio includes supporting coursework and team materials as well as co-op-related analysis; individual documents provide their own project context.

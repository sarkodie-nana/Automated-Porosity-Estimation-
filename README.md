# Automated Porosity Estimation for Sandstone-reservoirs
This project utilizes Python (Pandas, Matplotlib, Lasio) to process raw well log data and estimate reservoir properties. The workflow involves data cleaning, lithology identification via Neutron-Density crossplotting, and the calculation of effective porosity using the Density porosity equation
Key Features:

• Data Handling: Automated cleaning of null values.
• Lithology Identification: Created a Neutron-Density crossplot coupled with Gamma Ray z-axis coloring to isolate the sandstone baseline (matrix density = 2.65 g/cc).
• Physics-Based Calculation: Implemented the Density Porosity equation with logic to handle negative porosity and washout anomalies.
Tech Stack:

• Python 
• Pandas (Data manipulation)
• Matplotlib (Technical plotting)

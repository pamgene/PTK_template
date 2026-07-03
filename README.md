# PTK_template

Template for PTK analysis from processed image analysis results to kinase visualization. 

Make decisions at the following points:

1. QC: Set QC filter (`PTKQC_fractionPresent`) factor differently than the default if needed.

2. Assess if Log or VSN is better.

3. Use the Limma app to assess the level of differential phosphorylation.

4. Assess if batch effects are present. If so, correct them with Combat.

5. Use the confidence scoring UKA (csUKA) app to assess differential kinases.

6. To visualize differential kinases, use:

* interactive volcano plot inside the UKA app

* dotplot (dotplot app after UKA)

7. Use the exported kinase list for further analysis.

Find further information in the [Data Analysis guide](https://pamgene.github.io/PamGene_data_analysis_guide/Tercen%20Data%20Analysis%20Guide/III.%20Basic%20processing/).

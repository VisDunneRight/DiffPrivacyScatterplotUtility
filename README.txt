# Supplemental Material

All jupyter notebook files were created and ran in [Google Colaboratory](https://colab.research.google.com/). To simplify any OS issues we recommend downloading the notebooks and data and running them in Google Colab.

## Before Study

The below files were all generated and ran with pilot data as part of the prerigstration. Any diverges from these files will be discussed in the section [After Study](#after-study)

1. Preregisration

   - [PregistrationWithOutputs.ipynb](PreregistrationWithOutputs.ipynb): Jupyter notebook contains the pregistration code. Our analysis decisions and and code to run the analysis are contained here.
   - [PregistrationOutputsCleared.ipynb](PreregistrationOutputsCleared.ipynb): Same as file above without figures generated.
   - [PregistrationWithCellOutputs.pdf](PreregistrationWithCellOutputs.pdf): PDF of jupyter notebook with cell outputs
   - [PreregistrationWithCellOutputsCleared.pdf](PreregistrationWithCellOutputsCleared.pdf): PDF of jupyter notebook with no cell outputs

2. Pregistration/Pilot Data

   - [pilotData](pilotData): Folder contaning the csv files needed to generate the private plots.
   - [pilotPlots](pilotPlots): Folder contaning all the images of the private plots used in the pilot study.
   - [pilotPrivatePlotsStudyWebsite.zip](pilotPrivatePlotsStudyWebsite.zip): Zipped website used to collect the data for the pilot study and run preregistration code. Zip also contains all stimuli used.
   - [pilotResults](./pilotResults): Results collected from three expert reviewers for the 240 charts studied in the pilot. Three seperate jsons are contained for each of the three experts.
   - [pilotPrivatePlotGenerationAndStatsErrors.ipynb](pilotPrivatePlotGenerationAndStatsErrors.ipynb): This generates both the private plots used in the study webiste and the utility metrics used in the preregistratoin file. The jupyter notebook creates a csv of the automated utiltiy metric outputs for each chart.
   - [statisticalUtilityMetrics.csv](statisticalUtilityMetrics.csv): CSV of the utility metrics used in the preregistration.

3. Final Stimuli
   - [originalData](originalData): The data that specified the original shape for the 20 charts. Points were added to data to reach 5,000 points.
   - [scatterplotDensification.ipynb](scatterplotDensification.ipynb): Code used to add or remove points from the 20 original charts so that they would have 5,000 points.
   - [dataFull](dataFull): Folder containing the csvs for the 20 charts used in the final study. This data contains 5,000 points and is used to generate the final images.
   - [images](images): Images showing four charts. The original data (upper left), original data binned (lower left), data with 5,000 points (upper right), data with 5,000 points binned (lower right). This is to help demonstrate that we retained the look of the original data.
   - [scatterplotStimuli.pdf](scatterplotStimuli.pdf): PDF of the images folder containing all the charts in one file
   - [Images](Images): All images examined by the three expert reviewers. These images were used in the study website.
   - [PlotGeneration.ipynb](PlotGeneration.ipynb): Jupyter notebook used to generate the final private plot images used in the study
   - [finalStudyWebsite.zip](finalStudyWebsite.zip): React Website used to display the stimuli and collect data from the three expert reviewers. Website can be found at this [link](https://visdunneright.github.io/UserStudyScatter/)
4. Other
   - [dpcomp_core.zip](dpcomp_core.zip): Open source python library to implement DAWA, AGrid, AHP

## After Study

1. Final Data Analysis
   - [Results](Results): Three jsons for each of the expert reviewrs. This data was used in the analysis.
   - [Analysis.ipynb](Analysis.ipynb): Original pregresitration with additional analysis. Changes have been highlighted in red. Extensions are marked in blue. TODO need to edit
   - [UtilityMetrics.ipynb](UtilityMetrics.ipynb): The jupyter notebook that generates the utility metrics for the final private plots.
   - [UtilityMetrics.csv](UtilityMetrics.csv): CSV of utility metrics compiled for analysis for each chart. 1/epsilon was not used in the results.
   - [Privacy-Plot-Viewer.zip](Privacy-Plot-Viewer.zip): Website created to show all the generated stimuli and results. The data can be explored at this [link](https://visdunneright.github.io/Privacy-Plot-Viewer/)
   - [resultsFigureAndDataExploration.ipynb](resultsFigureAndDataExploration.ipynb): Jupyter notebook used to generate several figures in the results and analyze the data.
   - [figureGeneration.ipynb](figureGeneration.ipynb): Notebook used to generate many of the figures for the paper.

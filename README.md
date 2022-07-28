# Chicago-crime-vis-corpus
The Chicago-crime-vis corpus is a multimodal corpus containing data from the study of interactions of 16 subjects with a visualization expert. The participants explored visualizations on a large screen related to Chicago crime data to determine the deployment of police officers based on crimes in different areas of the city, time of the day, season, etc. For the interaction they used speech and hand gesture and the Visualization Expert was a human generating visualization from a different room. The corpus has 3179 transcribed utterances covering 1,879 word types and a vocabulary of 38,105 word tokens. 


This repository contains three folders -
#### Annotations: 
This folder has annotated data in anvil files for the 16 subjects (subject5 through subject20). Annotation is done for dialogue acts, contextualized actionable requests, gestures and referring expressions. Out of the 3179 utterances 449 were identified as Actionable Requests and annotated with one the 8 possible types of Dialogue Acts. 
The Dialogue Acts are:
1.	CREATE-VISUALIZATION
2.	CLARIFICATION
3.	WINDOW-MANAGEMENT
4.	FACT-BASED
5.	PREFERENCE-BASED
6.	MODIFY-VISUALIZATION
7.	APPEARANCE
8.	HIGH-LEVEL-QUERY

For gesture annotation, out of 536 identified gestures, 380 were annotated as pointing gestures. Out of these pointing gestures 159 pointed to visualizations on the screen and the rest were pointing to entities within the visualizations. 
For referring expression annotation, a total of 294 references were labeled in the corpus (176 text references and 118 gesture references). 
For slot annotation, 680 slot fillers were tagged with slots from our knowledge ontology.
The augmented_data folder contains the Chicago-crime-vis corpus with 160 subjects based on paraphrasing techniques to increase the original corpus size by a factor of 10 i.e., 16 subjects enlarged to 160 subjects leading to an increase to 15K utterances. 

#### Transcripts:
16 videos of approximately 1 hour in length each were transcribed into 16 text files capturing the visualization dialogue with each subject. 

#### Visualizations:
These are the actual visualizations produced by the data analysis expert during the visualization dialogue. The file name corresponds to the actual visualization identifier that the subject was shown on the screen. The annotations in the anvil files also use the same identifiers, e.g., the referring expression annotations identify the referent visualization targets by their identifiers.



## Citation
```bibtex
@inproceedings{kumar2020augmenting,
  title={Augmenting small data to classify contextualized dialogue acts for exploratory visualization},
  author={Kumar, Abhinav and Di Eugenio, Barbara and Aurisano, Jillian and Johnson, Andrew},
  booktitle={Proceedings of the 12th Language Resources and Evaluation Conference},
  pages={590--599},
  year={2020}
}
```
## Acknowledgment

This work was supported, initially, by NSF award IIS 1445751; and currently, by NSF award CNS 1625941, and by a UIC University Scholar award to Barbara Di Eugenio.


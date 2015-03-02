

```
___
layout: post
title: Poster Template
author: Teyden Nguyen
___
```


####1. Introduction 

**MOTIVE**:  No clear view of aging processes. Why?
⋅⋅* Complex subject — hard to investigate experimentally 
⋅⋅* ⋅⋅* large number of interactions
⋅⋅* ⋅⋅* dynamic processes
⋅⋅* ⋅⋅* ⋅⋅* variant between individuals
⋅⋅* ⋅⋅* ⋅⋅* variant throughout individual's lifetime
⋅⋅* ⋅⋅* many more variables
⋅⋅* However, rapid growth in research data — need to resolve limitations in human ability to read, curate, and make meaningful connections out of large data sets. 

In the wet-lab, automation of mundane laboratory tasks have recently allowed scientists to spend more time doing actual analysis on scientific concepts. 

Hence, **PROPOSED SOLUTION**:  
⋅⋅* Automate curation process through AI system to extract knowledge from scientific text and discover patterns
⋅⋅* Assist with hypothesis generation in the life sciences by applying functions to mine data, e.g., producing visualizations to highlight anomalies in research data that may not be seen by the human eye / reader 
Thus, similarly to the wet-lab, if we assign the mundane curation processes to a specially designed AI system tailored to extract knowledge on biological aging, (hopefully) scientists can spend more time doing analysis on the scientific concepts rather than reading 20+ articles of repeat studies to ensure confidence of results. 


(*) *Hypothesis*: INCREASE RATE OF PATTERN DISCOVERY IN DYNAMIC PROCESSES THROUGH FIELD-SPECIFIC NLP SCHEMA FOR TEXT MINING

####2. Background
⋅⋅* Build text mining system tailored towards biological text mining 
⋅⋅* ⋅⋅* All steps to-date (not listing it here)  
⋅⋅* ⋅⋅* Portion haven’t discussed yet but I think is critical to a  complete system:
⋅⋅* ⋅⋅* ⋅⋅* Implement Named Entity Recognition and Classification (NERC) techniques and integrate with information retrieval system (i.e. rule-based approach requires that all biological entities can be quantitatively measured...)
⋅⋅* ⋅⋅* ⋅⋅* Use domain knowledge from biomedical ontologies with machine learning approaches using HMM, or other models appropriate for recognizing biological objects (protein, cell-type, cell-line, etc.)

*In terms of our motive…*
At CREA, they are approaching modelling the concept of aging from a systems biology standpoint, looking at interactions between biological components in the body to give rise to function and behaviour of that system.

Hence, as **BIOLOGICAL AGING is a subject of growth**, which is a **function of time (i.e. X(t) …)**, as well as a **function of several additional parameters**… 
⋅⋅* Set additional parameters to our growth function to be measures of quantifiable biological objects, e.g. cell volume, membrane thickness, telomere length, amount of oxygen radicals, amount of accumulation of somatic mutations, concentration of p450, etc. 

QUERY SEARCH: Use parameters, biological objects, and combinations of biological objects paired with common verbs describing biological events as search queries for PubMed; extract all relations from abstracts containing search query. Sample sets of query searches:

⋅⋅1. parameters = [“cell volume”, “membrane thickness”, “telomere length”, “concentration of X”, “density of Y"]
⋅⋅2. biol_objects = [“p450”, “astrocyte”, “dopamine”, “hypothalamus”, “glucose”, “insulin”, “somatostatin”]
⋅⋅3. objectsNverbs = [[“p450”, “increase”], [“p450”, “decrease”], [“dopamine”, “activate”], [“insulin”, “inhibit”], [“somatostatin”, “excite”]]

>> * Input relations to relational database 
>> * Apply graphing functions to map linkage between relational text (visualization)
>> * Observe relationships between data points
>> * Apply more clustering & analysis functions to further manipulate data


####3. Materials & Methods
1. Construct NLP system to gather information from unstructured text
2. Extract knowledge from retrieved information; abstract relational data
3. Relational database
⋅⋅1. Allows us to publish data
⋅⋅2. Provides opportunity for usage of data 
4. Produce and perform functions on data
⋅⋅⋅ * Visualization —> GUI --> Allow people to see what is being done
⋅⋅⋅ * Web application —> UX --> Allow (some) interaction with what they can see what we’ve done


####4. Discussion
* Tie together everything we’ve done
* Is it consistent with our motive? 
* Does it benefit the research & open-source community? 
* ...?


####5.Conclusion
* Were our goals met? 
* What could we improve with? 
* What are we planning for next?
* ...?

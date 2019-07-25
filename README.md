# Machine Learning Interpretability

This GitHub repository is describing parts of my master-thesis with the title "Analysis of existing methods for the interpretation of the decision process of machine learning methods regarding their suitablity for automotive applications" 

<br/>

> ### Sometimes Human brain is so complex that it just cannot understand its own creation.
> ### Anonym

<br/>

Methods of interpretable machine learning can help you to understand how models behave and make certain predictions.

Methods of interpretable machine learning can be very helpful for:
- Identifying bugs in your model and optimizing
- Getting insights how certain predictions were made
- Getting insights how models behave globally (Feature interaction)
- Detecting bias in traning data
- Verfiying legal requierements for model
- Verfiying confidence of model and prediction
- Creating an interface between Humans and AI


There are several ways to make machine leraning models and their predictions more transparent and interpretable.
First of all, a distinction is made between global or local and model-specific or model-agnostic explanations of models.
Following table gives a brief summary about some methods that I am analyzing in my thesis:

| Method | Use | Scope |
| ------ | --- | ----- |
| LIME*   | model-agnostic | Local
| DeepLIFT | model-specific | Local
| Class Activation Maps | model-specific | Local
| Partial Dependence | model-agnostic | Global
| ELI5!** | model-agnostic | Global
| ICE*** | model-agnostic | Global


 You can find an implementation of LIME and Class Activation Maps in [*this Notebook* ](https://nbviewer.jupyter.org/github/akifcinar/Machine_Learning_Interpretability/blob/master/Interpreting_Image_Classification/Interpreting_Image_Classification.ipynb) other implemetations will follow.


\* LIME: Local interpretable model-agnostic explanations

** ELI5!: Explain Lime I am 5!

*** ICE: Individual Conditional Expecation



<h1>Predictive Justice IMU - Gru&LSTM / Attention layer / visualization attention layer / LIME / N-GRAM</h1>


<h2>Description</h2>
Construction of two Neural network, GRU & LSTM, with a custom attention layer in each.

The data consists of 265 sentences about Italian IMU tax litigations.s. 

Italian GloVE file taken from https://github.com/MartinoMensio/it_vectors_wiki_spacy

Explainability is a major component of the project. An example of an heatmap built with weights of the attention layer is below .

Local Interpretable Model-Agnostic Explanations (LIME) was also explored https://github.com/marcotcr/lime

A N-gram analysis is then performed to gain further insight into the prediction.
<br />


<h2>Languages and Library Used</h2>

- <b>Python</b> 
- <b>Tensorflow&Keras</b>
- <b>Notebook file</b>

<h2>Attention Layer visualization:</h2>

<p align="center">
weights visualization example 1: <br/>
<img src="https://i.imgur.com/fhYlw8B.png" height="50%" width="50%" alt="example 1"/>
<br />
<br />
weights visualization example 2:  <br/>
<img src="https://i.imgur.com/XYjEiwW.png" height="50%" width="50%" alt="example 2"/>
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

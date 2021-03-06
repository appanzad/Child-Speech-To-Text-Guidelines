# What is Child-Speech-To-Text?

<p align="center"><span>a logo or image representing the project</span></p>

<p>Child Speech to Text is a team where we specialize in parent-child verbal interactions. There are several times where we are not able to understand what young children are speaking but due to this project we will be able to transcribe thos interactions using speech datasets that are available to us now. Evntually, we will have a working automated speech-to-text algorithm with a user interface as well.</p>

## Work Done Last Year

<p>Describe the work done last year</p>
The work we did last year was gather all the data we needed, understand what it means, identify the features that need to be pre-processed and extracted and identified the transformations to be used on extracted features. We first tested several speech recognition models using python speech recognition module and made a spreadsheet of the children audio datasets. Then, we created a pre-processing pipeline where we extracted the audio signals from the files and removed the background noise from the signal as well. 
<br />
<br />
We also created applied a pre-emphasis filter where we created a log-mel spectrogram of pre-emphasis signal and generated the Mel-frequency cepstral coefficients as features. We then researched various feature selection techniques and identified models such as the Generative Adversarial Networks and the Probabilistic Inference Models. This year, we hope to implement deep learning architecture, Hidden Markov Models, and to get better inference results, we will combine deep learning with our HMM output from the porbabilistic models. 
<br />
<br />
<details>
<summary>
Models
</summary>

  <p> 1. Probabilistic Inference Model: </p>
  <p>   - Models will be trained on a collection of all the words in each transcription</p>
  <p>   - Model trained specifically for children speech, in the context of children’s books</p>
  <p> 2. Generative Adversarial Network: </p>
  <p>   - Generate synthetic children speaking data enhance model performance </p>
  
</details>



<details>
<summary>
  Screenshots of what we did Last Year
</summary>
  <p> Image 1 </p>
  <p> Image 2 </p>
 
</details>


## Installation

### Overview 

#### Steps

<p>1. Downlaod HTK:        </p>
<p>https://htk.eng.cam.ac.uk/download.shtml</p>
<details>
<summary>
  Installation Example
</summary>
  <p>https://htk.eng.cam.ac.uk/docs/inst-nix.shtml</p>
</details>

<p>2. Download Sox and Python 3 </p>
<p> https://sourceforge.net/projects/sox/ </p>
<p>3. Run the 3 commands to align the scripts</p>
<p> https://github.com/ucbvislab/p2fa-vislab </p>

### Problems faced in Installation

<p> -   </p>

## Research Papers

<p> add papers and info from those papers that is relevant to the project </p>

## Current Work

<p> Currently, we are working on aligning the audio files and researching into Hidden Markov Models and Deep Learning. We are working on documenting our project as well. </p>

## Moel Architecture Overview

### Hidden Markov Models

<p> This model is a type of probabilistic graphical model which allows us to predict a sequence of hidden variables from a specific set of observed variables. For example, based on what peoplr are wearing we can predict the weather. In this case, the they of clothes that someone wears is the observed varibale whereas the weather is te hidden variable.</p>

### Deep Learning Models

<p> </p>


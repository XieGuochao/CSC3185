---
marp: true
---

# Lecture 7 : Image & Recognition (3)

---

- [Lecture 7 : Image & Recognition (3)](#lecture-7--image--recognition-3)
  - [Statistical IR Approach (StatIR)](#statistical-ir-approach-statir)
  - [Syntactic IP Approach (StyntIR)](#syntactic-ip-approach-styntir)
  - [Neural Networks IR Approach](#neural-networks-ir-approach)
  - [ANN (Artificial Neural Networoks)](#ann-artificial-neural-networoks)
    - [Back-Propagation (BP)](#back-propagation-bp)
    - [Deep Learning](#deep-learning)
      - [Machine Learning vs Deep Learning](#machine-learning-vs-deep-learning)
      - [Layer of Deep Learning](#layer-of-deep-learning)
  - [Feature Extraction from Frequency Domain](#feature-extraction-from-frequency-domain)
    - [2-D Fourier Transform](#2-d-fourier-transform)
    - [2D FT: Applications](#2d-ft-applications)
  - [Gabor Filters](#gabor-filters)
    - [Gabor Filters Applications](#gabor-filters-applications)

---

## Statistical IR Approach (StatIR)

- Assume a satistical basis.
- Approach:
  - Representation: vector space
  - Generalization: rules & concepts
  - Evaluation: accurate & trustworthy estimates
- Procedure:
  1. Determine **feature vector** x
  2. Train system
  3. Classify patterns.


---

## Syntactic IP Approach (StyntIR)

- **Structural information**
- Quantify and extract **structural** information and to assess structural similarity of patterns.
- Formulate **hierarchical** descriptions of complex patterns built up from simpler **sub-patterns**.
- **Quantify** Structure:
  1. Formal grammars (Parsing)
  2. Relational descriptions (Relational Graph Matching)


---

## Neural Networks IR Approach

- Architecture
- Training or Learning
- Activation Function

---

## ANN (Artificial Neural Networoks)

ANN Characterized by:

1. Pattern of **connections**
2. Method of determining the **weights**
3. **Activation** Function

### Back-Propagation (BP)

- Gradient descent method to minimize the total squared error.
- Balance between the ability to respond correctly to the **input patterns** that are used for **training** and the ability to give reasonable responses to **input** that is **similar**.
- 3 Stages:
  1. **Feed-forward** of the input training pattern
  2. Calculation & **back-propagation** of the associated **error**
  3. **Adjustment** of the weights

---

### Deep Learning

#### Machine Learning vs Deep Learning

Machine Learning: ability of machines; Feature extraction by human.

Deep learning: a series of algorithms; Feature extraction by neural network.

#### Layer of Deep Learning

1. Convolutional layers: filters. Result of one filter: _feature map_ (FM).
2. Subsampling layers: reduce the **size** of input.

---

## Feature Extraction from Frequency Domain

- Time domain: respect to time

- Frequency domain: respect to frequency.
  - In 2D cases, frequency domain is the space defined by values of the _Fourier transform_ and its frequency variables.
  - How much the signal lies wthin each given frequency band.
  - Decompose a function into frequencies, with more than one sine wave.

---

### 2-D Fourier Transform

<img src="2D&#32;Fourier&#32;Transform.jpg" style="height: 100%; width: auto"/>

---

- Center dot: DC component.
- **Far** away: **Higher** frequency.
- More **contract**, **wider** spectrum.
- The image rotated, the specturm will rotate in the same direction.

---

### 2D FT: Applications

- High-pass filter: Sharpen (high frequency)
- Low-pass filter: Blur (low frequency)

---

## Gabor Filters

- Band-pass filters.
- Optimal **space freqeuncy resolution** (the best joint space-frequency localization)

---

### Gabor Filters Applications

1. Fingerprint identification: image enhancement. (Orientation and freqeuncy for each cell)
2. Fingerprint verification: texture analysis
3. Palmprint identification: texture analysis
4. Iris identification: texture coding
5. Face recognition: Gaborface


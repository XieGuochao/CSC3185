---
marp: true
---

# Lecture 5: Image & Recognition (1)

---

## Introduction to Recognition

- **Pattern**: 
  - The **form** of **representation** of an objectively existed event or object.
  - A set of **measurements** or **observations**, represented in vector or matrix notation.
- Pattern distortion (扭曲)
- IR:
  - Intelligent Systems
  - Mapping from feature space to class space

---

## IR System

Sensor -> Image & Signal Processing -> Pattern Recognition -> Decision Theory

### Definitions

- **Classification**
  - Probabilistic or grammatical models
  - A classifier: decision regions
- **Recognition**
  - The ability to classify
  - One more class: unclassifiable

---

- **Pattern class**
  - A set of patterns
  - Keys:
    - Suitable attributes (features)
    - A good measure of similarity and an associating matching process
- **Preprocessing**
  - To aid **computational feasibility**
  - To aid **feature extraction**
  - Minimize **noise**
- **Description**
  - Resort(凭借) to **linguistic** or **structural** models.

---

### Feature

Patterns -> Features with different numerical values.

1. Feature vector
2. Feature space.

### Feature Selection

1. Computationally **feasible**
2. Lead to **good** PR system success
3. **Reduce** the problem data into a **manageable** amount of information

---

### Simple classifiers

#### Template Matching

1. Get some versions of templates.
2. Compare with templates.
   1. Max correlation.
   2. Min error.

#### Distance Function

A measure of similarity between pattern vectors (proximity).

---

##### Error-free linear separation

Consequence: equivalent to min-distance classifier.

##### Min-distance classifier

- The closest match between the pattern & the respective class prototypes. (**correlation** / **cluster matching**)
- May contain single prototype (1 boundary) or multi-prototypes (**piecewise-linear** boundaries)
- Distance is calculated by **norm** $||x-m_k||$.

---

#### Linear Discriminants

- To find the $m_k$ that minimizes $||x-m_k||$
- To minimize $g(x) = m'x - 0.5||m||^2$

#### Decision Function

For a line $d(X) = w_1x_1 + w_2x_2 + w_3 = 0$ seperating 2 classes: $d(X)>0$ and $d(X) < 0$

Multi-class: more lines.

---

### Image Recognition Steps

- Image Formatting (capture/digitize)
- Conditioning (suppress noise; suppress uninteresting)
- Labeling (determine spatial events)
- Grouping (identifies events; maximum set of pixels in the event)
- Extracting (new spatial entities from groups)
- Matching (match entities to known objects)


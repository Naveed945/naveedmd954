# Artifact 3: Explaining Neural Networks in Plain Language

**Title:** Explaining Neural Networks in Plain Language — A Discussion Post and Knowledge Check

**Objective:** To demonstrate the ability to translate a complex AI/ML concept (how neural networks learn) into an explanation accessible to a non-technical audience, while also validating my grasp of the underlying technical concepts through a formal knowledge assessment.

**Process:** I started by identifying the core mechanics of a neural network — neurons, weights, layers, and the training loop — and then worked backward to find an everyday analogy (guessing a house price) that captured the same logic without jargon. I built the explanation in stages: a relatable scenario first, then the technical mapping, then a real-world application from my own job working with well sensor data. Separately, I completed a 15-question knowledge check covering neural network architecture, training mechanics, and historical foundations, which tested whether my conceptual understanding held up against precise technical definitions. For this portfolio, I revised both pieces, adding a comparison table and structured reflection, and combined them into a single artifact to show both communication skill and technical accuracy side by side.

**Tools:** Markdown for formatting and publishing to GitHub Pages, course discussion boards and the LMS quiz tool for the original coursework, and GitHub for hosting and version control of the portfolio itself.

**Value Proposition:** This artifact shows that I can do more than pass a technical assessment — I can take that same knowledge and make it usable for people who don't have a technical background, like a manager or client who needs to understand what a model is doing without needing to understand the math. That combination of technical grounding and clear communication is something I'd want any employer evaluating my AI/ML skills to see.

---

## Part A: Plain-Language Explanation

*Original context: A discussion post responding to the prompt of explaining neural networks simply, inspired by Einstein's principle that if you can't explain something simply, you don't understand it well enough.*

Einstein's line about simple explanations has always stuck with me. It's easy to hide behind vocabulary — say "backpropagation" and "activation function" and you sound like you know what you're talking about, whether or not you do. So I took this challenge seriously and tried to explain neural networks the way I would explain them to a coworker who doesn't write code.

**The house price analogy**

Imagine you're trying to guess the price of a house. You look at a few clues: square footage, neighborhood, and age. Some clues matter more than others, so you mentally give each one a weight. You add everything up and make a guess. Then someone tells you the real price, and you adjust — maybe neighborhood matters more than you thought. Next house, your guess is a little better.

That is one artificial neuron: take in numbers, weigh them, add them up, produce an output.

**Stacking neurons into layers**

Now stack thousands of those together in layers. The first layer notices simple things. The next layer combines those simple things into slightly bigger ideas. The layer after that combines those into bigger ideas still. In an image, the first layer might catch edges, the next might catch shapes, and a later one might catch "this looks like a face." Nobody programmed those steps — the network worked them out on its own.

**How it learns: three steps, repeated a lot**

1. **Guess.** Data goes in the front, a prediction comes out the back.
2. **Measure the miss.** Compare the prediction to the right answer. The gap is the error.
3. **Adjust.** Push the error backward through the layers and nudge every weight slightly in the direction that would have made the error smaller.

Do that a few million times and the weights settle into something useful. That's training.

**One-sentence summary:** A neural network is a giant pile of adjustable dials that gets tuned by trial and error until its guesses stop being wrong.

**Why this matters in my work**

In my day job, I work with well sensor data — thousands of readings an hour. I could write rules for what a failure looks like, but I would only catch the failures I already know about. A neural network finds the patterns I never thought to write down. That's the real shift: you stop writing the rules and start supplying the examples.

**Instructional design choices I applied:**
- **Chunking** — breaking the explanation into neuron → layers → training loop
- **Progressive disclosure** — leading with the house price example before any technical terms
- **Relevance and context** — tying the concept to my own work with sensor data
- **Spaced repetition** — closing with a one-sentence summary to reinforce the core idea

---

## Part B: Deep Learning Knowledge Check

*Original context: A 15-question quiz assessing foundational deep learning concepts, covering neural network architecture, training mechanics, and historical context.*

Selected topics covered in this assessment:

| Concept | What I Demonstrated |
|---|---|
| GPU acceleration | Understanding why specialized hardware matters for neural network computation |
| RNNs vs. CNNs | Matching architecture type to data type (sequential vs. spatial) |
| Historical foundations | Recognizing the statistical roots of ML (e.g., Legendre's least squares method) |
| Neurons, layers, activation functions | Core building blocks of network architecture |
| Loss functions | How networks quantify and correct error during training |
| Overfitting | A key training challenge and how to recognize it |
| Interpretability | Why deep learning models are often considered "black boxes" |
| Feature extraction | A key differentiator between deep learning and traditional ML |

I scored 30/30 (100%) on this assessment, reflecting a solid grasp of both the technical vocabulary and the conceptual "why" behind how these models function — the same conceptual foundation that made the plain-language explanation above possible.

---

*[← Back to Portfolio Home](../README.md)*

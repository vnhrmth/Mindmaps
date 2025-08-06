## What Is the Simplest Neural Network?

- The simplest neural network is a **Threshold Logic Unit (TLU)**,
- Which is a single artificial neuron that performs binary classification using a weighted sum and a threshold.

## What Is a Threshold Logic Unit?

- A TLU is a basic computational unit that:
  - Takes multiple inputs
  - Multiplies each input by a weight
  - Adds a bias (optional)
  - Compares the result to a threshold
  - Outputs either 0 or 1

## What Are the Components of a TLU?
  - Inputs
  - Weights
  - Threshold
  - Output

## What Is an Input?

- An input is a numerical value representing a feature of the data.

## What Is a Weight?

- A weight scales the importance of each input.

## What Is a Threshold?

- A threshold is a fixed value used to decide the output of the neuron.

## What Is the Output?

- The output is binary (0 or 1), depending on whether the weighted sum exceeds the threshold.

## What Is the Activation Rule?

- The activation rule is:
- ` If (weighted sum ≥ threshold) → output = 1 Else → output = 0 `

## What Can a TLU Do?

- Solve simple binary classification problems
- Implement basic logic gates like AND, OR

## What Can’t a TLU Do?

- Handle non-linear problems (e.g., XOR)
- Learn from data (no learning algorithm)

## How Is It Related to a Perceptron?

- A perceptron is an extension of a TLU that includes:

  - A bias term
  - A learning algorithm (Perceptron Learning Rule)
  - More flexibility in activation functions

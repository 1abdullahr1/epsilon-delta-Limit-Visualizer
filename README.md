
## Interactive $\epsilon$-$\delta$ Limit Visualizer
An interactive tool for exploring the formal definition of a limit ($\epsilon$-$\delta$ definition) for linear functions. This project helps students build an intuition for how the "challenge" of $\epsilon$ (the output range) determines the required $\delta$ (the input range).
## 🚀 Overview
The visualizer demonstrates the limit for the function:
$$f(x) = 3x - 5$$ 
As $x$ approaches 2, the limit $L$ is 1.
## The Math Behind It
To satisfy the formal definition, we need to find a relationship where $\vert{}f(x) - L\vert{} < \epsilon$ whenever $0 < \vert{}x - a\vert{} < \delta$.
For this specific function:

   1. $\vert{}(3x - 5) - 1\vert{} < \epsilon$
   2. $\vert{}3x - 6\vert{} < \epsilon$
   3. $3\vert{}x - 2\vert{} < \epsilon$
   4. $\vert{}x - 2\vert{} < \frac{\epsilon}{3}$

Therefore, the project uses the relationship: $\delta = \frac{\epsilon}{3}$
## ✨ Features

* Interactive Epsilon Slider: Adjust the value of $\epsilon$ to see the horizontal "output band" expand or contract.
* Dynamic Delta Calculation: The $\delta$ "input interval" automatically updates based on the current $\epsilon$ value.
* Visual Mapping: A shaded green region shows the $(x, y)$ area where the function stays within the target bounds.
* Real-time Feedback: Displays precise values for the $\epsilon$ band boundaries and the resulting $\delta$ interval.

## 🛠️ How it Works
The application maps the mathematical relationship to visual components:

* Yellow Shaded Area: Represents the $\epsilon$ band ($L - \epsilon$ to $L + \epsilon$).
* Green Shaded Area: Represents the $\delta$ interval ($a - \delta$ to $a + \delta$).
* Blue Line: The function $f(x) = 3x - 5$.

## 🏁 Getting Started
(Note: Add your specific setup instructions here, for example:)

   1. Clone the repository.
   2. Open index.html in your browser.
   3. Use the slider to explore the limit definition.


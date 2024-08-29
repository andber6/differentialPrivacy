# Differential Privacy Experiment: Dogs on the Internet

## Overview

This project showcases a playful yet insightful experiment aimed at measuring the percentage of users on the internet who are, in fact, dogs. Leveraging the principles of differential privacy, this experiment ensures that our canine friends can remain anonymous while contributing to our understanding of internet demographics.

## How It Works

The core of this experiment lies in the `diffPrivacy.js` script, which simulates a survey asking internet users if they are dogs. To protect the privacy of real dogs, responses are designed to be differentially private. This means that the survey's answers are randomized in a way that prevents individual respondents' identities from being revealed, while still allowing for accurate aggregate data analysis.

### Key Components

- **Differential Privacy:** Implemented through a function that randomly decides whether to return a truthful answer or a random one.
- **Population Simulation:** The script simulates a population of internet users, including both people and dogs, to see how well the differential privacy technique estimates the actual percentage of dogs.
- **Accuracy Analysis:** By adjusting the size of the simulated population, users can explore how the accuracy of the differentially-private estimate changes.

## Running the Experiment

To run this experiment, you will need Node.js installed on your computer. Once set up, navigate to the project directory in your terminal and run:

```
node diffPrivacy.js
```

## Experiment Results

The script outputs two key pieces of information:

- The actual percentage of dogs on the internet, based on the simulated population.
- The differentially-private estimate of the percentage of dogs on the internet.

## Explore Further

- **Adjust the Population Size:** Try modifying the `bigPopulation` flag in the script to simulate larger populations and observe how it affects the accuracy of the estimate.
- **Deep Dive into Differential Privacy:** This experiment serves as a practical introduction to differential privacy. Readers are encouraged to explore further into the mathematical and ethical foundations of differential privacy.

## Contributions

I welcome contributions from the community! Whether you have a suggestion to improve the experiment, want to share your results, or have ideas for additional privacy-preserving techniques, please feel free to open an issue or submit a pull request.

## License

This project is open source and available under the MIT License.

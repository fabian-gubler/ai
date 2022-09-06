# 3: Machine Learning

# Required Readings

## Guest Speaker: AI Ethics - Policy and Regulation
- AI drives inequality
- Firms that can't keep up, fall behind very quickly
- AI as a geopolitical weapon
- Talks (Landscape) -> Putting it down on paper (Whitepapers) -> Legislation

### Business Implementation
- Reputation Damage, Fines, Missed commercial opportunities
- Potential to need to redo the model from scratch
- Trust as a business differentiator

### Operationalize
- Governance (Define AI & policies, Current AI Catalogue, Risk Framework)
- Education (People who use the tool e.g. HR)
- Compliance (Controls, Auditing, Monitor)

## Machine Learning

### What Is Machine Learning?

#### Statistics
- **Standard Deviation**: Average distance from the mean
- **Normal Distribution**: Bell curve (e.g. IQ scores)
- **Distribution Differences**: Left / Right skew and Variance
- **Bayes' Theorem**: Answers given test result how probable that it is a true positive (instead of false positive)
- **Pearson Correlation**: Shows strength of relationship between two variables from 1 to -1 (+0.7 is strong relation)

### The Machine Learning Process
1. **Data Order**: Randomize the order of the data, so that algorithm doesn't detect patterns
2. **Choose a Model**: Selection of algorithm
3. **Train the Model**: Training Dataset, Algorithm calculates weights for each factor
4. **Evaluate the Model**: Using Test Dataset, verify if the algorithm is accurate
5. **Fine-Tune the Model**: Adjust parameters to see if results get better

## Deep Learning 

#### Explanation
- Subfield of machine learning
- In addition to Machine learning, analyzes all the data (pixel by pixel)
- Finds relataionships using neural networks

#### Neural Nets
- Function that includes units having values and weights (indicate relative importance)

### Neural Network Types

#### Fully Connected
All neurons have connections from layer to layer

#### Recurrent Neural Network (RNN)
Reasoning from previous experiencing containing loops and allowing information to be stored

#### Convolution Neural Network (CNN)
Process Images in Stages (Convolution), e.g. when fully connected is impossible

#### Generative adversarial network (GAN)
- Generator: This neural network creates many new creations (photos, sentences etc.)
- Discriminator: Looks at the creations and determines which one is real
- Adjustments: With these two results, new model would change the creations to make them as realistic as possible

#### Hardware
- For deep learning GPUs have been the primary choice
- Custom needs lead to custom hardware (e.g. Google's TPU)

#### Drawbacks and worries
- **black Box**: Explainable AI - Millions of parameters involving many hidden layers
- **Data**: Vast amount of Data needed
- **Causation**: All about finding correlation, not causation

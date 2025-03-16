# Prime Number Prediction using Machine Learning & Deep Learning

## Overview
This project explores **prime number prediction** using Machine Learning (ML) and Deep Learning (DL). We train models to classify whether a number is **prime or composite** using various algorithms, including:

- **Traditional ML Models:** Logistic Regression, SVM, Random Forest, Gradient Boosting
- **Deep Learning:** A large **multi-layered neural network**
- **Comparison with Miller-Rabin Test:** A probabilistic primality test

## Features
- Train models to predict prime numbers
- Compare accuracy with traditional primality tests
- Deploy a Gradio-based interactive UI
- Scalable and optimized deep learning model using TensorFlow
- Supports GPU acceleration (Google Colab)

## Dataset
The dataset consists of **randomly generated integers** labeled as **prime (1) or composite (0)**. The dataset is constructed dynamically and is **not pre-existing**, ensuring a fair training process.

### Feature Engineering:
1. **Number itself** (as input feature)
2. **Divisibility features** (by small primes)
3. **Binary representation** (for pattern recognition)
4. **Statistical properties** (e.g., sum of digits, modular behavior)

## Run it on google collab 
   Make sure to run 
   ```bash
      !pip install gradio
  ```

## Future Improvements
- Train on larger datasets (millions of numbers)
- Optimize deep learning architecture for efficiency
- Implement reinforcement learning for number theory exploration
- Extend to **prime factorization** & **Mersenne prime detection**

## License
This project is **open-source** under the [MIT License](LICENSE).


# Automated-Essay-Scoring



This project was done by Vineet Reddy and me for the course Unstructured Information Processing taught by Prof. Ravi Kothari. In this project, we create a **LSTM-based** neural network for automatically scoring essays.

We used the **Automated Student Assessment Prize (ASAP)** AES dataset, which has become widely popular for holistic scoring due to the large number of essays it contains. The dataset can be found at the following link - https://kaggle.com/c/asap-aes.

We use **Word2Vec** representations of the essay as inputs to our network. We also tried to train our own embedding layer using the dataset but that gave us a poorer performance. This is probably due to the fact that Word2Vec has been trained on a large corpus and hence is able to find better semantic relationships than what we get using the small corpus available to us. We also tried summarizing the essay before creating its Word2Vec representation but that gave us poor results.

On average, we achieved a **Kappa Score of 0.80**. The state of the art networks also produce similar Kappa Scores on the same dataset. 

You can find a detailed report alongside the Jupyter notebook where we expand on our approach and provide details about our outcome.

1. What is Deep Neural Network (DNN)?

👉 A neural network with multiple hidden layers used to learn complex patterns.

🔹 2. When do we use DNN?

👉 When data is tabular or numerical (e.g., Boston housing, OCR dataset)

🔹 3. What is CNN?

👉 A neural network specialized for image data using convolution operations.

🔹 4. Why CNN over DNN for images?

👉 CNN captures spatial features (edges, shapes) while DNN cannot.

🔹 5. What is RNN?

👉 A neural network designed for sequential data (time series, text).

🔹 6. Why RNN is used for time series?

👉 Because it remembers previous data (temporal dependency).

🔥 ACTIVATIONS & OUTPUT
🔹 7. ReLU vs Sigmoid vs Softmax
ReLU → hidden layers
Sigmoid → binary output
Softmax → multi-class output
🔹 8. Why no activation in regression output?

👉 Output is continuous value

🔥 LOSS FUNCTIONS
🔹 9. Loss functions usage
MSE → regression
Binary crossentropy → binary classification
Categorical crossentropy → multi-class
🔹 10. Sparse vs categorical crossentropy

👉 Sparse → integer labels
👉 Categorical → one-hot labels

🔥 CNN SPECIFIC
🔹 11. What does Conv2D do?

👉 Extracts features like edges, textures, patterns

🔹 12. What is MaxPooling?

👉 Reduces image size and keeps important features

🔹 13. What is Flatten?

👉 Converts 2D data → 1D for Dense layer

🔹 14. Why Dropout?

👉 Prevents overfitting

🔥 RNN SPECIFIC
🔹 15. What is sequence?

👉 Ordered data where previous values matter

🔹 16. Problem with basic RNN?

👉 Vanishing gradient problem

🔹 17. Solution to RNN problem?

👉 LSTM / GRU

🔹 18. What is LSTM?

👉 Advanced RNN that remembers long-term dependencies

🔥 GENERAL ML + DL
🔹 19. What is overfitting?

👉 Model performs well on training but poorly on test

🔹 20. How to prevent overfitting?
Dropout
More data
Data augmentation
🔹 21. What is optimizer?

👉 Updates model weights (e.g., Adam)

🔹 22. What is epoch?

👉 One complete pass of dataset

🔹 23. What is batch size?

👉 Number of samples processed at once

🔹 24. What is feature scaling?

👉 Normalizing input values for better training

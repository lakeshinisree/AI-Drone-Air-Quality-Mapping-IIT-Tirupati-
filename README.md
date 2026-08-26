# IIT TIRUPATHI-model

# 🧠 AI Model Training Project – Step-by-Step Implementation

## 📌 Objective

To build, train, and save a machine learning model using Python and TensorFlow, and generate a `.h5` file.

---

## 🛠️ Tools Used

* Python
* TensorFlow
* NumPy

---

## 📊 Dataset Used

The MNIST dataset (handwritten digit images) was used. It contains labeled images from 0–9 for training and testing.

---

# 🚀 Step-by-Step Process

## 🔹 Step 1: Environment Setup

Installed required libraries using:

```bash
pip install tensorflow
```

---

## 🔹 Step 2: Importing Libraries

Imported necessary libraries such as TensorFlow and NumPy to build and train the model.

---

## 🔹 Step 3: Loading the Dataset

Loaded the MNIST dataset using TensorFlow:

* Training data
* Testing data

---

## 🔹 Step 4: Data Preprocessing

* Normalized pixel values from 0–255 to 0–1
* This improves model performance and training speed

---

## 🔹 Step 5: Building the Model

Created a neural network using:

* Flatten layer (input layer)
* Dense layer (hidden layer with ReLU activation)
* Output layer (Softmax for classification)

---

## 🔹 Step 6: Compiling the Model

Configured the model using:

* Optimizer: Adam
* Loss Function: Sparse Categorical Crossentropy
* Metric: Accuracy

---

## 🔹 Step 7: Training the Model

Trained the model using training data:

```bash
model.fit(x_train, y_train, epochs=5)
```

---

## 🔹 Step 8: Evaluating the Model

Tested the model using test data:

```bash
model.evaluate(x_test, y_test)
```

Accuracy of the model was displayed.

---

## 🔹 Step 9: Saving the Model

Saved the trained model in `.h5` format:

```bash
model.save("trained_model.h5")
```

---

## 🔹 Step 10: Running the Program

Executed the program using:

```bash
python model.py
```

---

## 📁 Output

* Trained model file: `trained_model.h5`
* Accuracy score displayed in terminal

---

## 📌 Conclusion

The model was successfully built, trained, evaluated, and saved. This workflow demonstrates how AI models can be developed and can be extended to real-world applications such as image-based feature extraction.

---

## 👩‍💻 Author

Lakshmi Bhuvana Durvasula

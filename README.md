## Project Structure

This project is divided into two closely connected parts that together aim to digitally document and analyse traditional Uttarakhand cuisine using data mining techniques.

---

## Part 1: Data Mining – Image Classification of Uttarakhand Dishes

### Data collection approach
One of the main challenges in this project was the limited availability of authentic images of traditional Uttarakhand dishes. Many of these dishes are prepared in rural households or small local eateries and are not widely documented online.

To maintain cultural authenticity, a majority of the reference images were collected from a local Uttarakhand restaurant, Hotel Bhanu Palace. In cases where image availability was still limited, additional images were sourced from publicly available online platforms to fill the gaps. All images were used strictly for academic and learning purposes.

---

### Dataset preparation and augmentation
Since the original dataset size was relatively small, image augmentation techniques were applied to increase diversity and improve model generalisation. Each image was altered multiple times using transformations such as rotation, zooming, shifting, and flipping.

This process helped create a sufficiently large and varied dataset, allowing the model to learn different visual representations of the same dish and produce more reliable classification results.

---

### What I worked on
- Organised and labelled image data for multiple traditional Uttarakhand dishes
- Applied image augmentation techniques to expand the dataset
- Built and trained a CNN-based image classification model
- Evaluated model performance using training and validation accuracy

---

### Key learning
This part of the project helped me understand the challenges of working with real-world image data where data availability is limited. It also highlighted the importance of data augmentation in improving model robustness and accuracy.

---

## Part 2: Text Mining – Recipe and Ingredient Analysis

### Problem context
Along with visual recognition, understanding the composition of traditional dishes is equally important for cultural documentation. Recipes are usually stored as unstructured text, which makes analysis difficult without proper preprocessing.

This part of the project focuses on converting recipe and ingredient text into structured data that can be analysed using text mining and machine learning techniques.

---

### What I worked on
- Cleaned and preprocessed recipe and ingredient text data
- Analysed ingredient frequency across dishes
- Applied TF-IDF to identify important ingredients
- Built a similarity-based recommendation system using cosine similarity
- Grouped dishes using K-Means clustering
- Visualised insights using bar charts and word clouds

---

### Key insights
- Certain ingredients form the base of Uttarakhand cuisine and appear across multiple dishes
- TF-IDF helped identify unique ingredients that differentiate dishes
- Similarity analysis made it possible to recommend dishes with similar ingredient profiles
- Clustering automatically grouped dishes based on ingredient composition

---

### Key learning
This part of the project demonstrated how unstructured text data can be transformed into meaningful insights. It also showed how techniques like vectorisation, similarity measurement, and clustering can be applied to real-world textual datasets.

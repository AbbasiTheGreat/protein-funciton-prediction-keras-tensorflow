# protein-funciton-prediction-keras-tensorflow
In this repo , I worked on protein function prediction using keras and tensorflow.
As I advance in my "Practical Deep Learning using Keras and Tensorflow" course, here's what advancements I have made.

Here’s a detailed breakdown of the work:



𝐃𝐚𝐭𝐚 𝐏𝐫𝐞𝐩𝐫𝐨𝐜𝐞𝐬𝐬𝐢𝐧𝐠

Extracted and converted protein sequences from .fasta files, handling over 10,000 protein sequences.This included removing empty spaces , extracting protein id and fucntions performed by the protein using regular expression and storing in a text file using json.



𝐋𝐨𝐚𝐝𝐢𝐧𝐠 𝐃𝐚𝐭𝐚 𝐚𝐧𝐝 𝐏𝐫𝐞𝐩𝐚𝐫𝐢𝐧𝐠 𝐟𝐨𝐫 𝐓𝐫𝐚𝐢𝐧𝐢𝐧𝐠

Implemented helper function to read and process the data efficiently.Split the dataset into training and testing sets to evaluate the model performance accurately.Ensured the data shapes were correctly handled for model training.



𝐌𝐨𝐝𝐞𝐥 𝐒𝐞𝐭𝐮𝐩 𝐚𝐧𝐝 𝐓𝐫𝐚𝐢𝐧𝐢𝐧𝐠

Transitioned from a sequential model to a functional API for more flexibility and applied embedding layers to convert protein sequences into numerical form, constructed dense layers with activation functions to capture complex patterns.Compiled the model using binary cross-entropy loss and the Adam optimizer.Trained the model on the dataset, ensuring both training and validation accuracy were tracked.



𝐖𝐡𝐲 𝐮𝐬𝐞 𝐅𝐮𝐧𝐜𝐭𝐢𝐨𝐧𝐚𝐥 𝐀𝐏𝐈?

The Functional API in deep learning frameworks like Keras offers several advantages, particularly for building complex models. Here are some key benefits:

1. Flexibility in Model Architecture:

2. Shared Layers

3. Reusable Layers

4. Graph-like Model Visualization:

5. Multiple Inputs and Outputs:



𝐑𝐞𝐬𝐮𝐥𝐭𝐬 𝐕𝐢𝐬𝐮𝐚𝐥𝐢𝐳𝐚𝐭𝐢𝐨𝐧

Accuracy and Loss Plots: Visualized training and validation accuracy and loss over epochs to monitor model performance.



𝐊𝐞𝐲 𝐓𝐚𝐤𝐞𝐚𝐰𝐚𝐲𝐬:

This development highlights the power of deep learning in bioinformatics, particularly in predicting protein functions, which can have significant implications in research and medicine.

Effective data preprocessing and a well-structured model are crucial for accurate predictions.



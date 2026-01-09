About the Project

This project was built during the Intel Unnati Industrial Training Program as a team project.
The goal was to create an image recommendation system that can find visually similar images using deep learning instead of manual tags or metadata.

Given an input image, the system compares it with a dataset of images and recommends the most similar ones based on learned feature representations.

What the Project Does

Takes an image as input

Extracts feature embeddings using a deep learning model

Compares embeddings with stored image vectors

Returns the most visually similar images

How It Works (Brief)

Images are preprocessed and resized

A deep learning model generates embeddings

Embeddings are stored for comparison

Similarity is calculated using distance metrics

Top matching images are recommended

Tools & Technologies Used

Python

Jupyter Notebook

TensorFlow / PyTorch

NumPy, Pandas

OpenCV

Scikit-learn

Execution Note

The model training and embedding generation were done in a GPU-enabled environment provided during the Intel Unnati program.

Because of the heavy compute requirements, the notebook contains pre-generated outputs. Re-running the full training pipeline on a local CPU machine may take a long time or may not be feasible.

The notebook is shared mainly to show the code structure, logic, and results.

Team Project Details

This was a team project completed by three members as part of the internship.

My Contribution

Worked on image similarity logic using embeddings

Helped in building the recommendation pipeline

Assisted with model selection and evaluation

Contributed to debugging and result analysis

Results

Successfully generated meaningful image embeddings

The system was able to retrieve visually similar images

Helped understand how recommendation systems work in computer vision

What I Learned

Image feature extraction using deep learning

Similarity search using embeddings

Working with GPU-trained models

Collaborative development in ML projects

Acknowledgements

Thanks to Intel Unnati Program mentors and my teammates for their guidance and support during this project.

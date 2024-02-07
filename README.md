## Person Detection And Cropping

## Description

This project is a Python-based tool for face recognition and cropping within group photos. It allows users to take a photo with multiple people, draws bounding boxes around each person and their face, and returns the person's name if the code already has the face embeddings for it. If the face embeddings are not available, the tool prompts the user to create the face embedding and adds it to the directory. Finally, the tool returns the cropped images of each person along with their names.

## Features

1. Face recognition within group photos.
2. Bounding box drawing around each person and their face.
3. Identification of known faces based on pre-existing face embeddings.
4. On-the-fly creation and addition of face embeddings for unknown faces.
5. Cropped images of each person returned for further manipulation.

## Installation

**Clone the repository**

git clone [repository](https://github.com/shwetabh-23/person-detection.git)

**run the command setup_env.sh**
bash ./setup_env.sh

**run the command run_app.sh**
bash ./run_app.sh


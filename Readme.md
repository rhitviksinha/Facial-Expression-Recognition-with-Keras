## Usage

Download/Clone the repository, navigate to the folder and:  
Run the Python notebook, to generate the `model.json` file, and the `model_weights.h5` file.  
Then run command:  
```
python main.py
```

Serves on `https://localhost:5000`.

### Change the video stream/file
Change video/image stream for face recognition from the file camera.py. Navigate to the line:  
```
self.video = cv2.VideoCapture("presidential_debate.mp4")
```

Replace `presidential_debate.mp4` with a file of your choice, or enter `0` for webcam input.

### Get the dataset here:
You can get it off Kaggle, [here](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data).  
I used the distribution available on [Coursera](https://www.coursera.org/projects/facial-expression-recognition-keras), where they already divide the dataset according to its class into its specific folder.

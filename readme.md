# European Green Crab Detection

Train and evaluate a YOLO object-detection model for European green crabs using Google Colab.

## Run the Model in Google Colab

Open the ready-to-run notebook:

[Open European Green Crab Colab Notebook](https://colab.research.google.com/drive/1gqpoXX-ME9NWUBut0pF5ZHaOSvYF21va?usp=sharing)

### Steps

1. Open the notebook using the link above.
2. In Colab, select **Runtime > Change runtime type** and choose **T4 GPU** when available.
3. Run the notebook cells from top to bottom using **Runtime > Run all**.
4. Approve any package, Google Drive, or file-access prompts shown by Colab.
5. Wait for training to finish. The trained model is saved in the training output folder.
6. Run the prediction and evaluation cells to view detections and accuracy metrics.

## What the Notebook Does

- Installs the required Python packages.
- Downloads or prepares the dataset used by the Colab workflow.
- Loads a pretrained YOLO model.
- Trains the model on the green crab dataset.
- Runs detection on an example image.
- Evaluates the model using validation metrics such as precision and recall.

## Requirements

- A Google account
- Internet access
- A Google Colab session
- GPU runtime recommended for faster training

The notebook is designed so that users can run the complete workflow without configuring a local Python environment.

## Notes

- Training time depends on the selected Colab hardware and the number of epochs.
- The first run may take longer because it installs packages and downloads model weights or dataset files.
- Keep the Colab tab open while training is running.

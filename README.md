# Custom Video Classification with VideoMAE

This project implements a video classification pipeline using the state-of-the-art VideoMAE model. It allows you to:

* Train VideoMAE on custom video datasets.
* Test and evaluate the trained model's performance.
* Perform inference to classify new unseen videos.

This project empowers you to leverage the power of VideoMAE for your specific video classification tasks on custom data.

Dataset Structure:

The project expects your video dataset to be organized in the following structure:

Root directory
├── train/   # Folder containing training videos
│   └── video1  # Individual video files
│   └── video2  # Individual video files
├── val/     # Folder containing validation videos
│   └── video1  # Individual video files
│   └── video2  # Individual video files
└── test/    # Folder containing videos for inference
     └── video1  # Individual video files
     └── video2  # Individual video files


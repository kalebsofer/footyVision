# footyVision

FootyVision is a football analysis system that leverages machine learning, computer vision, and deep learning techniques to provide comprehensive insights into football matches. This project combines object detection, tracking, and custom model training to accurately detect and track players, referees, and footballs.

## Features

- Object Detection: FootyVision utilizes YOLO, an object detector, to detect players, referees, and footballs in real-time.
- Object Tracking: The system employs advanced tracking algorithms to track the detected objects across frames, ensuring accurate analysis.
- Custom Model Training: In addition to using pre-trained models, FootyVision trains its own object detector to enhance the output of the state-of-the-art models.
- Team Assignment: FootyVision assigns players to teams based on the colors of their t-shirts using K-means for pixel segmentation and clustering.
- Camera Movement Measurement: Optical flow is used to measure camera movement between frames, enabling precise measurement of player movement.
- Perspective Transformation: FootyVision implements perspective transformation to represent the scene's depth and perspective, allowing measurement of player movement in meters rather than pixels.
- Speed and Distance Calculation: The system calculates a player's speed and the distance covered, providing valuable performance metrics.

## Getting Started

To get started with FootyVision, follow these steps:

1. Clone the repository: `$ git clone https://github.com/your-username/footyvision.git`
2. Install the required dependencies: `$ pip install -r requirements.txt`
3. Run the system: `$ python main.py`

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

We would like to thank the creators of YOLO and the various open-source libraries and frameworks used in this project for their contributions.

## Contact

For any inquiries or questions, please contact us at [email protected]

Enjoy analyzing football matches with FootyVision!
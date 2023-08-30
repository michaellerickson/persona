Frame Extractor

This script extracts frames from a video file and optionally preprocesses them (resize, convert to grayscale) and saves them as image files.

Requirements
- Python 3.6 or higher
- pip 19.0 or higher
- OpenCV (cv2)

Installation
Make sure you have Python and pip installed on your machine.

Install OpenCV by running the following command:


pip install opencv-python


Usage
Edit the `extract_frames.pyw` script to specify the video file you want to extract frames from, the output directory where the frames will be saved, and the frame rate at which you want to extract the frames.


For example:

video_path = r'/path/to/directory/for/video.mp4'
output_path = r'/path/to/store/frames'
frame_rate = 10
extract_frames(video_path, output_path, frame_rate)


(Optional) If you want to preprocess the frames (resize, convert to grayscale), edit the `preprocess_frames` function call at the bottom of the `extract_frames.pyw` script.


frame_path = r'/path/to/store/frames/frame_0.png'
output_path = r'/path/to/store/preprocessed/frame_0.png'
resize_dims = (224, 224)
grayscale = True
preprocess_frames(frame_path, output_path, resize_dims, grayscale)


Make sure to adjust the paths and frame rate in the `extract_frames.pyw` script before running it. You can also adjust the `resize_dims` and `grayscale` parameters in the `preprocess_frames` function call to preprocess the frames as desired.

Support This Project
If you find this project useful and would like to support its development, you can make a donation via

Bitcoin:
3Ba6FM8mVsiAkJwvoSR6KFPdfmd7JEHRMy

Solana:
3caiUBs8vtenHRP75D4xKzPWf6NWpzXe88m6jJFf9MDM

Ethereum on Optimism:
0x15A12D8432d4d0540D9f003Dfe0E0535f549eD77

Contact: viddorah@gmail.com

Your support is greatly appreciated and will help to maintain and improve the project.

License
This project is licensed under the MIT License - see the LICENSE file for details.
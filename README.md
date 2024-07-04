# Sign Language Detection System

This Sign Language Detection System is built using OpenCV and Python. It leverages the Tensorflow, LabelImg libraries are used to detect specific sign language symbols.

## Commands

1. Clone the repository

   ```bash
   git clone https://github.com/charankulal/Sign-Language-Detection-using-opencv
   ```

2. Clone the Required packages from following repository

   ```bash
   git clone https://github.com/tzutalin/labelImg
   ```

   ```bash
   git clone https://github.com/nicknochnack/RealTimeObjectDetection
   ```

   ```text
   move the contents of the RealTimeObjectDetection into the parent folder
   Finally contents should look like
   Sign-Language-Detection-using-opencv
   |-labelImg
   |-Tensorflow
   
   ```

3. Create virtual environment

   ```bash
   python -m venv .venv
   ```

4. Activate virtual environment

   ```bash
   .venv/Scripts/activate
   ```

   for Mac or Linux

   ```bash
   source .venv/bin/activate
   ```

5. Install the required packages

   ```bash
   pip install -r requirements.txt
   ```

6. Run the program

   ```bash
   python3 main.py
   ```

### video parser

Python script for extracting images from video files

Basic usage: 
  ```python3 video_parser.py -i INPUT_DIR -o OUTPUT_DIR```
  
  INPUT_DIR is the directory containing video files 
  INPUT_DIR can also be a zip file 
  OUTPUT_DIR is where RGBD frames and json files are saved 
Examples: 
* To process first 100 frames only:  
    ```python3 video_parser.py -i INPUT_DIR -o OUTPUT_DIR -n 100``` 
* To flip image: 
    ```python3 video_parser.py -i INPUT_DIR -o OUTPUT_DIR --flip``` 
* To extract every 5th-frame: 
    ```python3 video_parser.py -i INPUT_DIR -o OUTPUT_DIR --skip_frames 5``` 
* To delete original data after processing: 
    ```python3 video_parser.py -i INPUT_DIR -o OUTPUT_DIR --delete_original``` 
    
To view all options:  
  ```python3 video_parser.py -h ```

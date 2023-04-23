# s-t-cut-segmentation

Repository for the course project done as part of CS-736 (Medical Image Computing) course at IIT Bombay in Spring 2022.  
Webpage: https://sarthakmittal92.github.io/projects/spr22/s-t-cut-seg  
Original Repository: https://github.com/sarthakmittal92/past-repos/blob/main/CS736.tar.gz

```
@misc{
naik_shameem_2019, 
title={Fast Interactive SuperpixelBased Image Region Generation}, 
url={https://www.ijitee.org/wp-content/uploads/papers/v8i8/H7423068819.pdf}, 
journal={IJITEE}, 
publisher={International Journal of Innovative Technology and Exploring Engineering}, 
author={Naik, Dinesh and Shameem, Muhammed}, 
year={2019}, 
month={Jun}
} 
```

## Dependencies:
python 3.5+
libopencv-dev
python3-tk

Other packages in requirements.txt
Install using: pip install -r requirements

virtualenv can be used.

## Usage:
run using: python3 ./code/Segmentation.py -i <path-to-input>
eg. 'python3 ./code/Segmentation.py -i ./data/deer.png'

## Details:
GUI shows up to mark foreground and background
Toggle using 'b' for background and 'o' for foreground
Press ESC after making the scribbles (sample scribbled images added in data folder)
Output will be stored in results directory (as out.png)

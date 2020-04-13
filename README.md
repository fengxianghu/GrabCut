
# GrabCut

My implementation of *[Grabcut: Interactive foreground extraction using iterated graph cuts]
## Dependencies

* Python 3.7
* OpenCV
* NumPy


## File desctiptions

* `grabcut_opencv.py` - Core implementation of the algorithm.
* `beispiel_aus_datensatz.jpg` - the given picture
* `grabcut_output.png` - the result of grabcut_opencv [https://github.com/fengxianghu/GrabCut/blob/master/grabcut_output.png]

## Usage

```
python grabcut_opencv.py <filename>
```

If `filename` is not specified, the program will pick `beispiel_aus_datensatz.jpg` to segment. For more details, 
please refer to instructions printed to the console after run the program.

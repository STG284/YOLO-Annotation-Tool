# YOLO-Annotation-Tool
## This is for creating the training set of images for YOLO

###### Commands on terminal:
```
https://github.com/STG284/YOLO-Annotation-Tool.git

cd YOLO-Annotation-Tool

pip install -r requirements.txt
```
### Create 001 folder in Images folder and put your class one images

### Convert to .JPEG from any type of images. Use this command(Ubuntu)

```mogrify -format jpg *.JPEG```
or
```mogrify -format jpg *.jpeg```
or
```mogrify -format jpg *.png```

### Run Main python script 

 ``` python main.py ```

### Run convert python file for create final text file for yolo images 

```python convert.py```



original repo: https://github.com/ManivannanMurugavel/YOLO-Annotation-Tool.git

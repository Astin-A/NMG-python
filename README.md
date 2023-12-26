# NMG python
 Normal Map Generator is a tool written in Python


## Usage

```
./NMGenerator.py input_file output_file --smooth SMOOTH_VALUE -- intensity INTENSITY_VALUE
```

### Required arguments:

#### input_file            
input image path

#### output_file          
output image path


### Optional arguments:

#### -h, --help            
Show help message

#### -s SMOOTH_VALUE, --smooth SMOOTH_VALUE
Smooth gaussian blur applied on the image

#### -it INTENSITY_VALUE, --intensity INTENSITY_VALUE
Intensity of the normal map

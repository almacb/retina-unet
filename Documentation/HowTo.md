## Pip install all packages from a requirements.txt in windows10 without stoping if one pakage fail

```
$ FOR /F %p IN (requirements.txt) DO pip install %p
$ pip list
```

## Check one package is installed
```
$ pip show [package_name]
```

## To find out what is included in $PYTHONPATH
[ref](https://askubuntu.com/questions/470982/how-to-add-a-python-module-to-syspath/471168#471168?newreg=daf6bd43fcbf44ac874d1f98d1797336)

```
import sys
print(sys.path)
```





## Convert tif images to png

- Install imageMagik
- In Windows powerShell go to \DRIVE\training\images
```
 $ magick mogrify -format png -path ../imagesPNG *.tif
 ```

[ref](http://www.imagemagick.org/Usage/basics/#mogrify)
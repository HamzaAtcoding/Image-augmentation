# Image-augmentation
Image augmenter for creating various augmented images of a single image. Basic usage can be pointed down to **create a dataset** which suffers from image limitation
## Required Dependencies
Keras  
Scikit-learn  
Opencv  
etc
## Tool used
* Emacs
## Getting Started
Place the initially committed file **Image-augmenter.py** at your folder of your desire, then `python` in shell or run in an `IDE` environment
## Customization
Look for `Image-augmenter.py` file, alter the loop according to your needs
```python
for batch in datagen.flow(x, batch_size=1,
                          save_to_dir='5000', save_prefix='5000-f-real', save_format='jpeg'):
    i += 1
    if i > 100:
        break  # otherwise the generator would loop indefinitely
 ```
## License
Look at the `license file` in this repo

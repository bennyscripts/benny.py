# benny.py
A Python wrapper for Benny's API.

### Install
> ```bash
> $ pip install benny.py
> ```

### Example
> ```python
> import benny
> 
> client = benny.Client()
> 
> cat_image = client.cat()
> dog_image = client.dog()
> 
> print(cat_image, dog_image)
> ```
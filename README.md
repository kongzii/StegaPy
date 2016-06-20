# StegaPy
StegaPy is Steganography made very simple. Just encode/decode your ASCII text into any image.

## Usage

### In Python

```
from stegapy import encode, decode

# Encode message into test_stegaed.png using test.jpg image
# Only ASCII characters are allowed, and PNG output is recommended.
encode("Hello, this will be encoded.", "test.jpg", "test_stegaed.png")

decode("test_stegaed.png")

```

### From terminal

```
python3 stegapy.py --encode --message="Greetings from jung.ninja." --image-in="test.jpg"

python3 stegapy.py --decode --image-in="_stegaed.png"
```

## Notes

For more info check my blog http://blog.jung.ninja
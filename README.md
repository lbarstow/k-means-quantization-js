This is an application to turn an image into a cross stitch pattern. It was adapted
from "https://github.com/dstein64/k-means-quantization-js"

TODO:
-add ability to add maximum height or width ( app will choose the smaller of the two
  and calculate squares based off of this)
-convert color to closest DMC floss


k-means Image Color Quantization
================================

*k-means Image Color Quantization* is a web page that can apply color
quantization to images using k-means clustering.

The code runs fully in the browser. That is, there are no server-side calls
to process the image and/or run the clustering and quantization. The
implementation is in JavaScript.

How To Use
----------

To quantize an image, navigate to index.html, load an image, select a value for
*k*, and click *Quantize*. The time to process increases with the size of the
image.

The page is available at
<https://dstein64.github.io/k-means-quantization-js/>.

Screenshots
-----------

### Selection/Instructions

![Select](screenshots/select.png)

### Quantized Image

![Quantized](screenshots/quantized.png)

License
-------

The source code has an [MIT License](https://en.wikipedia.org/wiki/MIT_License).

See [LICENSE](LICENSE).

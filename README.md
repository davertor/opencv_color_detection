
![Made-love][made-love-shield]
[![LinkedIn][linkedin-shield]][linkedin-url]


# Webcam color detector
Webcam color detector is a python script that opens your webcam video in order to detect objects with the color defined by the user in real-time.

Webcam color detector draw a yellow circle in the center of the object detected. Color is defined in HSV space instead of RGB, because in HSV color is defined mainly by its hue, which makes easier to find the desired color. The detector can only find one object per frame, so it will draw a circle around the object with the higher contour.

Besides, the detector draw a red path over the image, which is the trajectory described by the object with the selected color. 

![Product screenshot][product-screenshot]

## Dependencies
Before you begin, ensure you have met the following requirements:
* open-cv
* numpy

## Authors
* [@davertor](https://github.com/davertor) 📖

## License
This project uses the following license: GNU v3.0


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[product-screenshot]: images/screenshot.png
[linkedin-url]: https://linkedin.com/daniel-verdu-torres

[made-love-shield]: https://img.shields.io/badge/-Made%20with%20love%20❤️-orange.svg?style=for-the-badge
[license-shield]: https://img.shields.io/badge/License-GNU-brightgreen.svg?style=for-the-badge
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-darkblue.svg?style=for-the-badge&logo=linkedin
[twitter-shield]: https://img.shields.io/badge/-Twitter-blue.svg?style=for-the-badge&logo=twitter


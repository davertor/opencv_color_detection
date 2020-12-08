
[![GNU V3.0 License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Twitter][twitter-shield]][twitter-url]

# Webcam color detector
Webcam color detector is a python script that opens your webcam video in order to detect objects with the color defined by the user in real-time.

Webcam color detector draw a yellow circle in the center of the object detected. Color is defined in HSV space instead of RGB, because in HSV color is defined mainly by its hue, which makes easier to find the desired color. The detector can only find one object per frame, so it will draw a circle around the object with the higher contour.

Besides, the detector draw a red path over the image, which is the trajectory described by the object with the selected color. 

[![Product screenshot][product-screenshot]]

## Dependencies
Before you begin, ensure you have met the following requirements:
* open-cv
* numpy

## Contributing to Webcam color detector
To contribute to Webcam color detector, follow these steps:
1. Fork this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.

Alternatively see the GitHub documentation on [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

## Authors
* [@davertor](https://github.com/davertor) 📖

## Contact
If you want to contact me you can reach me at davertor@gmail.com.

## License
This project uses the following license: GNU v3.0


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[license-shield]: https://img.shields.io/badge/License-GNU-brightgreen.svg?style=for-the-badge
[license-url]: https://github.com/davertor/webcam_color_detector/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/daniel-verdu-torres
[twitter-shield]: https://img.shields.io/badge/-Twitter-black.svg?style=for-the-badge&logo=twitter&colorB=555
[twitter-url]: https://twitter.com/davertor
[product-screenshot]: images/screenshot.png


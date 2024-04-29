<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/janskn/land-cover-detection"> 
    <img width="250" alt="image" src="https://github.com/JanSkn/land-cover-detection/assets/68644413/eb5e6e88-b0f6-46dd-84c5-a12464f9b147">
  </a>

  <h3 align="center">Land Cover Detection</h3>

  <p align="center">
    Automatic classification of satellite images with machine learning.
    <br />
    <a href="https://github.com/janskn/land-cover-detection"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/janskn/land-cover-detection/issues">Report Bug</a>
    ·
    <a href="https://github.com/janskn/land-cover-detection/issues">Request Feature</a>
  </p>
</div>



<!-- ABOUT THE PROJECT -->
## About The Project

Land cover detection is the process of analysing aerial imagery to identify and map the different types of ground structures in a given area, for example forests, buildings or rivers. 

It is critical for a variety of applications, including environmental monitoring, urban planning, agriculture or natural resource management.

<br />

The image dataset includes 21 classes (in order):

- agricultural, airplane, baseball diamond, beach, buildings, chaparral,
dense residential, forest, freeway, golf course, harbour, intersection, medium residential, mobile home park,
overpass, parking lot, river, runway, sparse residential, storage tanks, tennis court

Examples of the images and their predictions:

<img width="1048" alt="image" src="https://github.com/JanSkn/land-cover-detection/assets/68644413/5d2999ce-742a-4c8d-a85e-bdd6f2b25e29">

<br /><br />

This project implements two different approaches: a **Convolutional Neural Network (CNN)** and a **Support Vector Machine (SVM)**.

<br />

You can read more about the project and why there are two different models in the `Report.pdf`.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



## Installation

_Follow these steps to run the project._

1. Clone the repo
   ```sh
   git clone https://github.com/janskn/land-cover-detection.git
   ```
2. Run the Jupyter Notebook in `src`

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

This project was built with Python.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Run `src/land_cover_detection.ipynb`.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


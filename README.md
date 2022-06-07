<div id="top"></div>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/JavierMendez-Coder/react-auth">
    <img src="public/images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">React Auth</h3>

  <p align="center">
    React application with Firebase authentication
    <br />
    <a href="https://github.com/JavierMendez-Coder/react-auth"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/JavierMendez-Coder/react-auth/issues">Report Bug</a>
    ·
    <a href="https://github.com/JavierMendez-Coder/react-auth/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://github.com/JavierMendez-Coder/react-auth)

This project is aimed to create a React app which requires users to authenticate through a sign up and login page in order to access to the app's content, additionally with a logout button to leave whenever they want. 

Furthermore, authentication persistence will be implemented to allow the users to stay logged in even if they leave the page, and automatically loggin users out after some time.


Designed by [Maximilian Schwarzmüller][mschwarzmueller] from [Academind][academind] in his [React - The Complete Guide][course-url] course.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [React.js](https://reactjs.org/)
* [Firebase](https://firebase.google.com/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation
 
1. Clone the repo
   ```sh
   git clone https://github.com/JavierMendez-Coder/react-auth.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Enter your API in `.env`
   ```env
   REACT_APP_API_KEY="ENTER YOUR API"
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

In this project you can sign up or login to access to the app, then there you are also free to change your password or logout yourself, otherwise you will be logged out after some time, this time doesn't refresh with activity in the page.

### Run App
  * Server
    ```sh
    npm start
    ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Javier Méndez - javiermendez0299@gmail.com

Project Link: [https://github.com/JavierMendez-Coder/react-auth](https://github.com/JavierMendez-Coder/react-auth)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Maximilian Schwarzmüller][mschwarzmueller]
* [Academind][academind]

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/JavierMendez-Coder/react-auth.svg?style=for-the-badge
[contributors-url]: https://github.com/JavierMendez-Coder/react-auth/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/JavierMendez-Coder/react-auth.svg?style=for-the-badge
[forks-url]: https://github.com/JavierMendez-Coder/react-auth/network/members
[stars-shield]: https://img.shields.io/github/stars/JavierMendez-Coder/react-auth.svg?style=for-the-badge
[stars-url]: https://github.com/JavierMendez-Coder/react-auth/stargazers
[issues-shield]: https://img.shields.io/github/issues/JavierMendez-Coder/react-auth.svg?style=for-the-badge
[issues-url]: https://github.com/JavierMendez-Coder/react-auth/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/javiermendez-coder
[product-screenshot]: public/images/screenshot.png
[mschwarzmueller]: https://github.com/mschwarzmueller
[academind]: https://github.com/academind
[course-url]: https://www.udemy.com/course/react-the-complete-guide-incl-redux/

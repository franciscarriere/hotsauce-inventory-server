<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/franciscarriere/hotsauce-inventory">
    <img src="images/logo-white.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Hot Sauce Inventory</h3>

  <p align="center">
    Hot Sauce Inventory Management
    <br />
    <a href="https://github.com/franciscarriere/hotsauce-inventory/issues">Report Bug</a>
    ·
    <a href="https://github.com/franciscarriere/hotsauce-inventory/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#dependencies">Dependencies</a></li>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Dependencies
- [MongoDB](https://www.mongodb.com/)
- [NodeJS](https://nodejs.org/en/)
- [NoDemon](https://nodemon.io/)

### Prerequisites

1. Clone the repo
   ```sh
   git clone https://github.com/franciscarriere/hotsauce-inventory.git
   ```

2. Run NPM install for the server component

* npm
  ```sh
  cd app/
  npm install
  ```

2. Run NPM install for the client component

* npm
  ```sh
  cd app/src/client
  npm install
  ```

## Local Development
During development, ensure your computer's host file has been edited to point `volamtarpeppers.wrclan.ca` to 127.0.0.1

To start the server for a dev environment, use the provided startup shell script.

* shell
  ```sh
  cd app/
  sh startup-dev.sh
  ```


<!-- USAGE EXAMPLES -->
## Usage

To start the server, use the provided startup shell script.

* shell
  ```sh
  cd app/
  sh startup.sh
  ```

<!-- CONTACT -->
## Contact

Francis Carriere - [@FCArchon](https://twitter.com/FCArchon) - senatorsfc@gmail.com

[https://github.com/franciscarriere/hotsauce-inventory](https://github.com/franciscarriere/hotsauce-inventory)


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/franciscarriere/repo.svg?style=for-the-badge
[contributors-url]: https://github.com/franciscarriere/hotsauce-inventory/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/franciscarriere/repo.svg?style=for-the-badge
[forks-url]: https://github.com/franciscarriere/hotsauce-inventory/network/members
[stars-shield]: https://img.shields.io/github/stars/franciscarriere/repo.svg?style=for-the-badge
[stars-url]: https://github.com/franciscarriere/hotsauce-inventory/stargazers
[issues-shield]: https://img.shields.io/github/issues/franciscarriere/repo.svg?style=for-the-badge
[issues-url]: https://github.com/franciscarriere/hotsauce-inventory/issues
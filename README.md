<!-- PROJECT LOGO -->
```
                        _______________________________     _________         .    .
                       /                               \   (..       \_    ,  |\  /|
                       |  Fish are friends, not food.   \   \       O  \  /|  \ \/ /
                       \_______________________________  \   \______    \/ |   \  /
                                                       \__\     vvvv\    \ |   /  |
                                                                \^^^^  ==   \_/   |
                                                                 `\_   ===    \.  |
                                                                 / /\_   \ /      |
                                                                 |/   \_  \|      /
                                                                        \________/
```
<p align="center">
  <h1 align="center">bruce</h1>
  <p align="center">
    Accelerating the parsing PCAPS into JSON format as well as ability to extract files from those PCAPS
    <br><br>
    <a href="https://mit-license.org">
    <img src="https://img.shields.io/badge/license-MIT-black.svg" alt="License: MIT">
    </a>
    <a href="https://github.com/bruce/issues">
    <img src="https://img.shields.io/github/issues/markdown-templates/markdown-snippets.svg" alt="Issues">
    </a>
    <a href="https://github.com/bruce/forks">
    <img src="https://img.shields.io/github/forks/markdown-templates/markdown-snippets.svg" alt="Forks">
    <a href="https://github.com/cyber1of3/bruce/stargazers">
    <img src="https://img.shields.io/github/stars/markdown-templates/markdown-snippets.svg" alt="Stars">
    </a>
    <a href="https://www.python.org">
    <img src="https://img.shields.io/badge/language-python-yellow" alt="Python">
    </a>
    <img src="https://img.shields.io/badge/subject-DFIR-red" alt="Subject">
    <img src="https://img.shields.io/github/last-commit/cyber1of3/bruce" alt="Last Commit">
    </a>
    <br><br>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Prerequisites](#prerequisites)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)


<br><br>
<!-- ABOUT THE PROJECT -->
## About The Project

bruce has been created to help fellow digitial forensicators with reading and interpreting PCAP files without the need to trawl though Wireshark. bruce utilises tshark to convert the PCAPS and outputs them into JSON to then be indexed into log management or SIEM platforms alongside other data sources.
<br>

## Prerequisites

* [tshark](https://tshark.dev)
<br><br>


<!-- USAGE EXAMPLES -->
## Usage
`python3 bruce.py [-h] [-e] <directory_of_PCAPS>`
### Example
`python3 bruce.py -e /pcaps/`
### Support
See the [support](https://github.com/cyber1of3/bruce/issues) for a list of commands and additional third-party tools to help with preparing images or data for bruce.
<br><br>


<!-- ROADMAP -->
## Roadmap

* String searching

See the [open issues](https://github.com/cyber1of3/bruce/issues) for a list of proposed features (and known issues).
<br>

See the [changes](https://github.com/cyber1of3/bruce/issues) for a list of previous changes to bruce.
<br><br>


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
<br><br>


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.
<br><br>


<!-- CONTACT -->
## Contact

cyber1of3 - cyber1of3thon@gmail.com

Project Link: [https://github.com/cyber1of3/bruce](https://github.com/cyber1of3/bruce)
<br><br>


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Wireshark (tshark)](https://tshark.dev)
* [Best-README-Template](https://github.com/othneildrew/Best-README-Template)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/cyber1of3/bruce.svg?style=flat-square
[contributors-url]: https://github.com/cyber1of3/bruce/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/cyber1of3/bruce.svg?style=flat-square
[forks-url]: https://github.com/cyber1of3/bruce/network/members
[stars-shield]: https://img.shields.io/github/stars/cyber1of3/bruce.svg?style=flat-square
[stars-url]: https://github.com/cyber1of3/bruce/stargazers
[issues-shield]: https://img.shields.io/github/issues/cyber1of3/bruce.svg?style=flat-square
[issues-url]: https://github.com/cyber1of3/bruce/issues
[license-shield]: https://img.shields.io/github/license/cyber1of3/bruce.svg?style=flat-square
[license-url]: https://github.com/cyber1of3/bruce/master/LICENSE.txt

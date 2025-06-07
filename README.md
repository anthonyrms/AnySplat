# AnySplat: Feed-forward 3D Gaussian Splatting from Unconstrained Views

### [Project Page](https://city-super.github.io/anysplat/) | [Paper](https://arxiv.org/pdf/2505.23716)

![AnySplat](https://img.shields.io/badge/Download-AnySplat-blue?style=flat-square&logo=github)

**Authors:**  
[Lihan Jiang*](https://jianglh-whu.github.io/), [Yucheng Mao*](https://myc634.github.io/yuchengmao/), [Linning Xu](https://eveneveno.github.io/lnxu), [Tao Lu](https://inspirelt.github.io/), [Kerui Ren](https://github.com/tongji-rkr), [Yichen Jin](), [Xudong Xu](https://scholar.google.com.hk/citations?user=D8VMkA8AAAAJ&hl=en), [Mulin Yu](https://scholar.google.com/citations?user=w0Od3hQAAAAJ), [Jiangmiao Pang](https://oceanpang.github.io/), [Feng Zhao](https://scholar.google.co.uk/citations?user=r6CvuOUAAAAJ&hl=en), [Dahua Lin](http://dahua.site/), [Bo Dai<sup>†</sup>](https://daibo.info/) 

## Overview

<p align="center">
<img src="assets/pipeline.jpg" width=100% height=100% class="center">
</p>

AnySplat introduces a novel approach to 3D Gaussian splatting from uncalibrated images. The method employs a transformer-based geometry encoder, which processes the input images and generates a structured representation of the scene. Following this, three decoder heads work in tandem to reconstruct the 3D scene.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Contributing](#contributing)
5. [License](#license)
6. [Contact](#contact)
7. [Acknowledgments](#acknowledgments)

## Features

- **Transformative Geometry Encoding:** Utilizes state-of-the-art transformer models to understand complex geometries from uncalibrated images.
- **Multi-Decoder Architecture:** Employs three decoder heads to ensure comprehensive scene reconstruction.
- **High-Quality Outputs:** Generates high-fidelity 3D representations, making it suitable for various applications in graphics and computer vision.
- **User-Friendly Interface:** Simplified commands for easy interaction with the system.
- **Extensive Documentation:** Detailed guides and examples to help users get started quickly.

## Installation

To get started with AnySplat, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/anthonyrms/AnySplat.git
   cd AnySplat
   ```

2. **Install Dependencies:**
   Ensure you have Python 3.8 or higher installed. Use pip to install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the Latest Release:**
   Visit the [Releases](https://github.com/anthonyrms/AnySplat/releases) section to download the latest version. If you find a file, download it and execute as instructed.

## Usage

To use AnySplat, follow these simple steps:

1. **Prepare Your Images:**
   Gather your uncalibrated images and place them in a designated folder.

2. **Run the Model:**
   Execute the following command in your terminal:
   ```bash
   python main.py --input_path /path/to/your/images --output_path /path/to/output
   ```

3. **View Results:**
   Once the process completes, navigate to the output directory to view the generated 3D representations.

## Contributing

We welcome contributions from the community. If you would like to contribute to AnySplat, please follow these guidelines:

1. **Fork the Repository:** Click the "Fork" button at the top right of this page.
2. **Create a Branch:** Use the following command to create a new branch:
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Make Changes:** Implement your changes and test thoroughly.
4. **Submit a Pull Request:** Push your changes and submit a pull request for review.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, please reach out to the authors:

- [Lihan Jiang](https://jianglh-whu.github.io/)
- [Yucheng Mao](https://myc634.github.io/yuchengmao/)
- [Linning Xu](https://eveneveno.github.io/lnxu)
- [Tao Lu](https://inspirelt.github.io/)
- [Kerui Ren](https://github.com/tongji-rkr)

## Acknowledgments

We would like to thank the contributors and researchers in the field of computer vision and graphics. Their work has inspired and enabled the development of AnySplat.

## Additional Resources

- [Project Page](https://city-super.github.io/anysplat/)
- [Paper](https://arxiv.org/pdf/2505.23716)

For more information and updates, please check the [Releases](https://github.com/anthonyrms/AnySplat/releases) section.
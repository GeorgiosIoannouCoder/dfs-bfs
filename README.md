<a name="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![GitHub][github-shield]][github-url]

# [dfs-bfs] | Depth First Search - Breadth First Search On A 2D-Grid

<br />
<div align="center">
    <img src="dfs-bfs.png" alt="Logo" width="400" height="200">


<h3 align="center">Depth First Search - Breadth First Search</h3>

  <p align="center">
    Depth First Search - Breadth First Search On A 2D-Grid allows people to traverse and search for a particular cell/node/number in a 2D-Grid.
    <br />
    <a href="https://github.com/GeorgiosIoannouCoder/dfs-bfs"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/GeorgiosIoannouCoder/dfs-bfs/issues">Report Bug</a>
    <a href="https://github.com/GeorgiosIoannouCoder/dfs-bfs/issues">Request Feature</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#key-features">Key Features</a></li>
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
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About The Project

![Project Name Screen Shot][project-screenshot]

- **Depth First Search - Breadth First Search On A 2D-Grid allows people to traverse and search a particular number in a 2D-Grid.**
- **Depth-First Search (DFS) and Breadth-First Search (BFS) are two techniques of traversing graphs and trees. DFS explores a graph or tree by diving as deeply as possible along a branch before backtracking, making it well-suited for tasks like finding paths and topological sorting. It is implemented using the stack data structure and recursion. Arrays/Lists can be used to implement the stack data structure.**
- **BFS systematically explores all neighbors of a node before moving to their neighbors, making it ideal for finding the shortest path in unweighted graphs and efficiently visiting nodes level by level. BFS employs a queue to maintain a first-in-first-out order, allowing them to serve different graph exploration needs.**

## Problem Statement

1. Given the 2D-Grid in the below Figure, start at the black 1 position and reach the goal at the red 15 position. Find the path to the goal using:
   1. Depth First Search (DFS)
   2. Breadth First Search (BFS)

<img src="2d_grid.png" alt="Grid" width="" height="">

### Key Features

1. **Usually we see Depth-First Search (DFS) and Breadth-First Search (BFS) on a Tree. However, they can also be used in a graph or grid which is what we do here.**

<p align="right"><a href="#readme-top">Back to top</a></p>

### Built With

[![Python][Python]][Python-url]
[![JupyterNotebook][JupyterNotebook]][JupyterNotebook-url]


<p align="right"><a href="#readme-top">Back to top</a></p>

## Getting Started

**To get a local copy of the Depth First Search - Breadth First Search On A 2D-Grid up and running locally follow these simple example steps:**

### Prerequisites

**NOTE:** How to check if Python is installed and what is its version

```sh
  python --version
```

**NOTE:** How to check if Git is installed and what is its version

```sh
  git -v
```

1. Please make sure you have pyenv installed and use any Python3 version:

   - You can use pyenv to switch between different Python versions:
     - Windows: [https://www.youtube.com/watch?v=HTx18uyyHw8](https://github.com/pyenv-win/pyenv-win)
     - Mac: [https://www.youtube.com/watch?v=31WU0Dhw4sk](https://github.com/pyenv/pyenv)
     - Linux: [https://www.youtube.com/watch?v=1Zgo8M9yUtM](https://github.com/pyenv/pyenv)

2. Please make sure you have git installed

   - Windows: [https://git-scm.com/download/win](https://git-scm.com/download/win)
   - Mac: [https://git-scm.com/download/mac](https://git-scm.com/download/mac)
   - Linux: [https://git-scm.com/download/linux](https://git-scm.com/download/linux)

#### SetUp

1. Navigate to the directory where you want to clone/run/save the application

   ```sh
   cd your_selected_directory
   ```

2. Clone this repository

   ```sh
   git clone https://github.com/GeorgiosIoannouCoder/dfs-bfs.git
   ```

3. Navigate to the dfs-bfs git repository

   ```sh
   cd dfs-bfs
   ```

4. Use any Python3 version in the cloned repository folder:

   ```sh
   pyenv local 3.xx.xx
   ```

5. Create virtual environment in the cloned repository folder

   ```sh
   python -m venv .dfs-bfs-venv
   ```

6. Activate the virtual environment (Windows OR Mac/Linux):
   1. Windows

   ```sh
   .\.dfs-bfs-venv\Scripts\activate
   ```

   2. Mac/Linux

   ```sh
   source .dfs-bfs/bin/activate
   ```

7. Install ipykernel:

   ```sh
   pip install ipykernel
   ```

8. Install Jupyter Notebook:

   ```sh
   pip install jupyter notebook
   ```

9.  Add the kernel of the virtual environment in the Jupyter Notebook:

   ```sh
   ipython kernel install --user --name=.dfs-bfs-venv
   ```

10. Run the Jupyter Notebook:

   ```sh
   jupyter notebook
   ```

11. Select the .dfs-bfs-venv kernel to run the Jupyter Notebook.

<p align="right"><a href="#readme-top">Back to top</a></p>

## Usage

1. Define/Input a grid, starting cell, goal cell, and traversal directions, use Depth First Search (DFS) or Breadth First Search (BFS) to find the goal cell in the 2D-Grid.
2. You can use the two notebooks above for both [Depth First Search (DFS)](https://github.com/GeorgiosIoannouCoder/dfs-bfs/blob/main/Ioannou_Georgios_dfs.ipynb) and [Breadth First Search (BFS)](https://github.com/GeorgiosIoannouCoder/dfs-bfs/blob/main/Ioannou_Georgios_bfs.ipynb)
3. The two notebooks above were coded having in mind the problem statement mentioned in the introduction.

## Report

1. You can find the report for this project [here](https://github.com/GeorgiosIoannouCoder/dfs-bfs/blob/main/Ioannou_Georgios_Report_HW_2-1.pdf) where it shows step by step how Depth First Search (DFS) and Breadth First Search (BFS) work to find the goal cell.

<p align="right"><a href="#readme-top">Back to top</a></p>

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right"><a href="#readme-top">Back to top</a></p>

## License

Distributed under the MIT License. See [LICENSE](https://github.com/GeorgiosIoannouCoder/dfs-bfs/blob/main/LICENSE) for more information.

MIT License

Copyright (c) 2023 Georgios Ioannou

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

<p align="right"><a href="#readme-top">Back to top</a></p>

## Contact

Georgios Ioannou - [@LinkedIn](https://linkedin.com/in/georgiosioannoucoder)

Georgios Ioannou - [@georgiosioannoucoder](https://georgiosioannoucoder.github.io/) - Please contact me via the form in my portfolio.

Project Link: [https://github.com/GeorgiosIoannouCoder/dfs-bfs](https://github.com/GeorgiosIoannouCoder/dfs-bfs)

<p align="right"><a href="#readme-top">Back to top</a></p>

[contributors-shield]: https://img.shields.io/github/contributors/GeorgiosIoannouCoder/dfs-bfs.svg?style=for-the-badge
[contributors-url]: https://github.com/GeorgiosIoannouCoder/dfs-bfs/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/GeorgiosIoannouCoder/dfs-bfs.svg?style=for-the-badge
[forks-url]: https://github.com/GeorgiosIoannouCoder/dfs-bfs/network/members
[stars-shield]: https://img.shields.io/github/stars/GeorgiosIoannouCoder/dfs-bfs.svg?style=for-the-badge
[stars-url]: https://github.com/GeorgiosIoannouCoder/dfs-bfs/stargazers
[issues-shield]: https://img.shields.io/github/issues/GeorgiosIoannouCoder/dfs-bfs.svg?style=for-the-badge
[issues-url]: https://github.com/GeorgiosIoannouCoder/dfs-bfs/issues
[license-shield]: https://img.shields.io/github/license/GeorgiosIoannouCoder/dfs-bfs.svg?style=for-the-badge
[license-url]: https://github.com/GeorgiosIoannouCoder/dfs-bfs/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=0077B5
[linkedin-url]: https://linkedin.com/in/georgiosioannoucoder
[github-shield]: https://img.shields.io/badge/-GitHub-black.svg?style=for-the-badge&logo=github&colorB=000
[github-url]: https://github.com/GeorgiosIoannouCoder/
[project-screenshot]: dfs-bfs.png
[Python]: https://img.shields.io/badge/python-FFDE57?style=for-the-badge&logo=python&logoColor=4584B6
[Python-url]: https://www.python.org/
[JupyterNotebook]: https://img.shields.io/badge/jupyter-808080?style=for-the-badge&logo=jupyter&logoColor=FFA500
[JupyterNotebook-url]: https://jupyter.org/
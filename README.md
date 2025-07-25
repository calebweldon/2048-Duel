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
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<div align="center">
  <img src="https://github.com/calebweldon/2048-Duel/assets/132513904/b6acd17a-cbf9-4b47-ba6d-018ff5dc9b82" alt="Logo" width="800" height="800">
  <p>2048 Duel is a multiplayer adaptation of the popular game 2048 made using C++. Grab a friend and a computer and start playing!</p>
</div>



<!-- BUILT WITH -->
### Built With
[![C++][C++-badge]][C++-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Follow the steps below to set up and run the project locally on your machine.

### Prerequisites

* CMake  
  > ⚠️ **Note:** Requires CMake version 3.10 or higher.  
  > Install via pip:  
  > ```sh
  > pip install cmake
  > ```

* C++ Compiler  
  > ⚠️ **Note:** Requires a compiler that supports **C++17**.  
  > Check your version with:  
  > ```sh
  > g++ --version   # or clang++ --version
  > ```  
  > If needed, install one with:  
  > - **macOS**: `brew install gcc`  
  > - **Ubuntu/Linux**: `sudo apt update && sudo apt install g++`

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/calebweldon/2048-Duel
   cd 2048-Duel
   ```

2. Set up the build directory:

   ```sh
   cmake -S . -B build
   ```

3. Build the project:

   ```sh
   cmake --build build
   ```

4. Run the game:

   ```sh
   ./build/game
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Caleb Weldon | [Website](https://calebweldon.com/) | calebweldon2026@u.northwestern.edu

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
[C++-badge]: https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white
[C++-url]: https://cplusplus.com/

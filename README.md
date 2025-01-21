# Simple OpenGL Example with GLEW and GLFW3

This repository contains a basic example of using OpenGL with GLEW (OpenGL Extension Wrangler) and GLFW3 (Graphics Library Framework) in Visual Studio. The project demonstrates setting up a window.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before you begin, ensure you have the following software installed:

- [Visual Studio](https://visualstudio.microsoft.com/)

## Installation

1. Clone the repository with another name:

    ```bash
    git clone https://github.com/arturo-intel/baseGLEW.git new-name
    cd new-name
    ```
2. Rename the following files 
   
    ![WhatsApp Image 2025-01-21 at 10 37 55_05428bed](https://github.com/user-attachments/assets/6057b789-dee9-4507-9605-be4fd5742e6b)

   to the new name (i.e. letest)

    ![WhatsApp Image 2025-01-21 at 10 38 55_b3166465](https://github.com/user-attachments/assets/8b484c9f-2d83-46ec-a0d5-b21cff582e22)

4. Open the project in Visual Studio.

    ![WhatsApp Image 2025-01-21 at 10 39 18_870d7ab0](https://github.com/user-attachments/assets/db78606f-340e-417f-abe8-718a612dfa20)

    A warning message will pop up, click on OK  

5. The solution will still pointing to the "0_base" project.

    ![WhatsApp Image 2025-01-21 at 10 40 05_65d4620a](https://github.com/user-attachments/assets/8dc6eb72-f5e2-47e2-8256-2777127334d8)

   To fix this, remove "0_base" project. Right click over and select delete
   
    ![WhatsApp Image 2025-01-21 at 10 40 40_4ec4dd4b](https://github.com/user-attachments/assets/d5cb0b0b-cf0a-4ba5-bce0-0c8a58fc65b0)

   Click OK

    ![WhatsApp Image 2025-01-21 at 10 41 05_a8fabd4e](https://github.com/user-attachments/assets/ee60488f-a760-484e-993d-066ca9782b73)


   Then add the exisisting "letest" project by right clicking over the solution and select add existing project

    ![WhatsApp Image 2025-01-21 at 10 41 50_89b49d29](https://github.com/user-attachments/assets/75de3613-7209-4110-85fe-6449eb9d61d2)

   Navigate to where the .vcxproj file is and select it.

    ![WhatsApp Image 2025-01-21 at 10 42 19_1adce079](https://github.com/user-attachments/assets/c5f6c30e-3c5e-4258-b949-7b450252db10)

6. Done!. Visual Studio project is configured to use all the attached dependencies (GLEW and GLFW3).

   ![WhatsApp Image 2025-01-21 at 10 42 48_c3d69100](https://github.com/user-attachments/assets/50d2ad02-7399-4193-ad15-557556bfc670)

## Usage

1. Build the project in Visual Studio.
2. Run the executable to see the OpenGL window .

## Contributing

Contributions are always welcome! Please follow these steps if you'd like to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch-name`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch-name`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

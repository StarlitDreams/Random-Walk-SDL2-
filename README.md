# Random Walk Simulation with SDL2

This project is a simple random walk simulation using SDL2. The program creates a graphical window and simulates a random walk where each step is colored differently based on the direction taken.

## Features

- **Random Walk Simulation:** The program randomly chooses a direction (up-left, up-right, down-left, down-right) for each step of the walk.
- **Color-Coded Steps:** Each direction has a unique color associated with it:
  - Up-left: Pink (245, 169, 184)
  - Up-right: Light Blue (91, 206, 250)
  - Down-left: White (255, 255, 255)
  - Down-right: Black (0, 0, 0)
- **Boundary Reset:** The walk resets to the center if it goes beyond the defined boundary.

## Example
![project_gif](https://github.com/StarlitDreams/Random-Walk-SDL2-/assets/40852436/3fc8f25e-7ea1-46d8-af3a-492f3bcaca0b)

## Prerequisites

- SDL2 library
- Mingw-w64 or any compatible compiler
- C++17 or later

## Building and Running the Program

### Windows

1. Ensure you have the SDL2 library installed. You can download it from [SDL2 Downloads](https://www.libsdl.org/download-2.0.php) or using MSYS
   ```sh
   pacman -S mingw-w64-x86_64-SDL2
3. Clone this repository or download the source code.
    ```bash
   git clone https://github.com/starlitdreams/random-walk-sdl2.git
   cd random-walk-sdl2
5. Open a terminal or command prompt and navigate to the directory containing the source code.
6. Compile the code using the following command:
   ```sh
   chcp 65001 > $null; & "C:\msys64\mingw64\bin\g++.exe" -fdiagnostics-color=always -g "path_to_your_source_code\random_walk.cpp" -o "path_to_your_output_directory\random_walk.exe" -lmingw32 -lSDL2main -lSDL2 -mwindows -LC:\msys64\mingw64\lib -IC:\msys64\mingw64\include\SDL2 -Dmain=SDL_main
7. After building the project, you can run the executable:
   ```sh
   random_walk.exe
   
## License

This project is licensed under the MIT License. See the LICENSE file for details.


# LayoutCanvas

## 🔧 Building and Installation
This project is built using CMake and requires the Qt Framework for the GUI.

### Prerequisites
* **C++ Compiler:** GCC, Clang, or MSVC (supporting C++17 or newer).
* **CMake:** Version 3.10 or higher.
* **Qt Framework:** Version 6.x (with support for Qt Widgets and Qt OpenGL).
* **Python 3:** Required for P-Cell scripting (must be accessible for embedding).

### Building from Source

```bash
# Clone the repository
git clone [https://github.com/esai-vel-murugan/LayoutCanvas.git](https://github.com/esai-vel-murugan/LayoutCanvas.git)
cd LayoutCanvas

# Create a build directory
mkdir build
cd build

# Configure CMake
# (Note: Adjust -DCMAKE_PREFIX_PATH if Qt is not found automatically)
cmake ..

# Build the project (adjust -jN for your number of CPU cores)
make -j8

# Run the application
./src/LayoutCanvas # (or similar path depending on your build system)

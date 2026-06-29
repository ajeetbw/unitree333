# Unitree Robot SDK Version 2
Unitree Robot SDK Version 2 is a comprehensive software development kit designed to provide a robust and efficient interface for interacting with Unitree robots. This SDK is built on top of a robust tech stack, leveraging the power of C++, Eigen, and Boost to deliver high-performance and reliable functionality.

## Project Description
The Unitree Robot SDK Version 2 is designed to provide a unified interface for controlling and interacting with Unitree robots. This SDK provides a wide range of features, including motion control, sensor integration, and advanced algorithms for robotics applications. With this SDK, developers can create custom applications, integrate Unitree robots with other systems, and leverage the advanced capabilities of these robots.

## Tech Stack
The Unitree Robot SDK Version 2 is built using a combination of the following technologies:
* **Programming Languages:** C++, Python
* **Frameworks:** CMake, Eigen, Boost
* **Libraries:** YAML-CPP, SPDLog, Fmt
* **Operating Systems:** Ubuntu 20.04 LTS (supported on both aarch64 and x86_64 architectures)

## Installation and Startup
To install and start using the Unitree Robot SDK Version 2, follow these steps:
### Prerequisites
* Install the required dependencies: `apt-get update` and `apt-get install -y cmake g++ build-essential libyaml-cpp-dev libeigen3-dev libboost-all-dev libspdlog-dev libfmt-dev`
* Ensure you have the necessary compiler (GCC version 9.4.0) and CMake (version 3.10 or higher) installed

### Building the SDK
1. Create a build directory: `mkdir build`
2. Navigate to the build directory: `cd build`
3. Run CMake: `cmake ..`
4. Build the SDK: `make`

### Installing the SDK
To install the SDK system-wide, run: `sudo make install`
Alternatively, you can install the SDK to a custom directory by specifying the `CMAKE_INSTALL_PREFIX` flag: `cmake .. -DCMAKE_INSTALL_PREFIX=/opt/unitree_robotics` followed by `sudo make install`

## Basic Usage
The Unitree Robot SDK Version 2 provides a range of APIs and examples to help you get started with developing your own applications. For example, you can use the `state_machine` example to control the robot's state machine, or the `h1` example to interact with the H1_2 parallel mechanism control interface.

### State Machine Example
The `state_machine` example demonstrates how to use the SDK to control the robot's state machine. You can modify the `params.json` file to adjust the parameters, such as the time step (`dt`), proportional gain (`kp`), and derivative gain (`kd`).

### H1_2 Parallel Mechanism Control Example
The `h1` example provides an interface for controlling the H1_2 parallel mechanism. You can use this example to test the performance of the H1_2 ankle in `PR Mode`, which enables direct control over the pitch and roll joints.

## Contributing
Contributions to the Unitree Robot SDK Version 2 are welcome. To contribute, please fork the repository, make your changes, and submit a pull request. Ensure that your code adheres to the existing coding standards and conventions.

## Licensing
The Unitree Robot SDK Version 2 is licensed under [insert license]. By using this SDK, you agree to the terms and conditions of the license.

## Additional Resources
For more information about the Unitree Robot SDK Version 2, please visit the [Unitree Document Center](https://support.unitree.com/home/zh/developer).
## 8379 Parity Bits Summer Improvements
The goal of this repo is to revamp the 8379 codebase to provide a good foundation for future seasons. 

## Goals
- Advanced autonomous movement
	- Support for multiple chassis types
 	- Robust localization, physics-informed control and motion planning
- Modular framework for easily controlling new assemblies and swapping out hardware
- Clean and well documented code to help new coders
- Multithreading

## Implementation
- ROS-like framework of topics and services
	- Services implemented as simple method calls, thread-safe topic class contains data to be passed around
- Use of abstraction to enable seamless swapping of algorithms

cmake_minimum_required(VERSION 3.27)
project(Operating_System_Task_Manager_Emulator)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Operating_System_Task_Manager_Emulator
        DataStructure.h
        DeviceManager.cpp
        DeviceManager.h
        MemoryManager.cpp
        MemoryManager.h
        ProcessManager.cpp
        ProcessManager.h
        TaskManager.cpp)

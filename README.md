# MEMORY MANAGEMENT SIMULATION 💾

<img width="1440" alt="image" src="https://github.com/GWC523/Memory-Management-Simulation/assets/56357171/b889806a-781f-4385-8975-aa42c2989160">

The app can simulate three different memory management algorithms: first-fit, worst-fit, and best-fit simulation. 

View Simulation: https://gwc523.github.io/cmsc-125-mp3/

# ABOUT MEMORY MANAGEMENT

Operating systems employ memory management algorithms as a method of allocating and controlling memory resources for processes. Here is a summary of the first-fit, best-fit, and worst-fit memory management algorithms.

First-Fit:
The first memory block that is big enough to fit a process is allocated via the first-fit method. The first block that fulfills the memory requirements is where the search ends after starting at the beginning of the memory space. Given that it doesn't have to scan the full memory space, this approach is quick and easy to implement. Fragmentation, in which smaller unused memory gaps are left between allocated blocks, might result, though.

Best-Fit:
The memory block that fits the process's needs the best is chosen via the best-fit algorithm. It looks through all of the RAM and selects the smallest block that is still big enough to house the process. This method makes better use of the memory blocks in order to reduce fragmentation. However, because the full memory space must be searched, it could be slower than the first-fit approach.

Worst-Fit:
The worst-fit approach gives the process access to the biggest memory block that is available. It looks through the whole memory and chooses the biggest block that can satisfy the process's memory needs. When huge processes must occasionally be assigned, this approach is helpful. However, as it leaves behind tiny, useless memory gaps, it can cause considerable fragmentation.

Every memory management technique has pros and cons, and how well it performs will depend on the workload and memory consumption patterns of the system. The system's unique needs for memory usage and fragmentation determine the best algorithm to use based on criteria including efficiency, speed, and fragmentation. To improve memory management, operating systems frequently combine these techniques or other iterations of them.


## How to Use ⚒️

From your command line, first clone Memory-Management-Simulation:

```bash
# Clone the repository
$ git clone https://github.com/GWC523/Memory-Management-Simulation.git

# Move into the repository
$ cd portfolio-v1

# Remove the current origin repository
$ git remote remove origin
```

Then install the dependencies using NPM

```bash
# 2022 Update - Fix Dependencies
$ npm audit fix

# Install dependencies
$ npm install

# Start the development server
$ npm start
```

## Technologies Used

- [Bootstrap 4](https://getbootstrap.com/docs/4.3/getting-started/introduction/)


## Author

Gwyneth Chiu - https://github.com/GWC523

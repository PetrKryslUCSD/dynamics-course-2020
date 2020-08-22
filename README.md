# dynamics-course-2020

## Finite element/boundary element software

[FinEtools.jl](https://github.com/PetrKryslUCSD/FinEtools.jl) is a Julia package for the basic operations of the finite element method. It is applied in separate packages in individual application domains, for instance to heat conduction, stress analysis and so forth.

The core ideas of [FinEtools.jl](https://github.com/PetrKryslUCSD/FinEtools.jl) are described in the [Conceptual Guide](https://petrkryslucsd.github.io/FinEtools.jl/latest/guide/guide.html#Guide).

Of particular interest to this course are applications to  [linear solid mechanics](https://github.com/PetrKryslUCSD/FinEtoolsDeforLinearTutorials.jl), [acoustics](https://github.com/PetrKryslUCSD/FinEtoolsAcoustics.jl), [vibration in fluids](https://github.com/PetrKryslUCSD/FinEtoolsVibInFluids.jl), and [dynamics of flexible beams](https://github.com/PetrKryslUCSD/FinEtoolsFlexBeams.jl).

## Theory

The theory implemented in [FinEtools.jl](https://github.com/PetrKryslUCSD/FinEtools.jl) and friends is described in the textbook [Finite Element Modeling with Abaqus and Python for Thermal and Stress Analysis](http://hogwarts.ucsd.edu/~pkrysl/femwabaquspython-book/).


## Tutorials

The applications can be explored with tutorials. Check out the documentation of:

- [FinEtoolsDeforLinearTutorials.jl](https://github.com/PetrKryslUCSD/FinEtoolsDeforLinearTutorials.jl): Linear structural dynamics.
- [FinEtoolsAcousticsTutorials.jl](https://github.com/PetrKryslUCSD/FinEtoolsAcousticsTutorials.jl): Acoustics.
- [FinEtoolsVibInFluidsTutorials](https://github.com/PetrKryslUCSD/FinEtoolsVibInFluidsTutorials.jl): Vibration of structures in fluids.
- [FinEtoolsFlexBeamsTutorials.jl](https://github.com/PetrKryslUCSD/FinEtoolsFlexBeamsTutorials.jl): Dynamics of flexible beams.

## Software environment for trying it out

1. Make sure you have [Git for Windows](https://gitforwindows.org/). 
2. Download the portable Julia environment for this course[???]()

### Instructions

The portable version of Julia in this folder is only for the Windows platform.

Clone the tutorial repositories you would like to explore:
```
git clone https://github.com/PetrKryslUCSD/FinEtoolsDeforLinearTutorials.jl.git
git clone https://github.com/PetrKryslUCSD/FinEtoolsAcousticsTutorials.jl.git
git clone https://github.com/PetrKryslUCSD/FinEtoolsFlexBeamsTutorials.jl.git
```

Explore the tutorials with Julia:

1. Start the VS Code IDE by double-clicking the bash script `double_click_me_to_start.sh`.
2. Open the folder of the tutorial. For instance `FinEtoolsAcousticsTutorials.jl`. 
3. Start the Julia REPL (command line). Press `ctrl+shift+p` to get the command pallete and type 'Julia'. Select `Julia: Start REPL`. 
4. Now execute in the REPL the following command line (copy and paste into the terminal pane and then hit return)
```
using Pkg; pkg"activate .; instantiate"
```
5. Finally, open the tutorial you would like to execute. Individual lines can be executed with `ctrl+enter`, while entire code cells can be executed with `shift+enter`. The entire file can be executed by  `ctrl+shift+p`, typing `Julia: Execute File` and selecting this command.


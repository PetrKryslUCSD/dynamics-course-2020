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

## Software environment for running the tutorials

a. Make sure you have [Git for Windows](https://gitforwindows.org/). 

b. If you don't have Paraview for visualizing finite element meshes and results, you may wish to install that from [https://www.paraview.org/download/](https://www.paraview.org/download/). Please make sure that the executable is in the path.

c. Download the portable Julia environment for this course, 
[Portable_Julia.zip](http://hogwarts.ucsd.edu/~pkrysl/shared/Portable_Julia.zip). Expand the zip file into any folder (even the USB drives), change your working folder to be `Portable_Julia`, and follow the instructions below.

### Detailed installation and operation instructions

The portable version of Julia in this folder is only for the Windows platform.

Explore the tutorials with Julia:

1. Start the VS Code IDE by double-clicking the bash script
`double_click_me_to_start.sh`. If this is  the first time this script runs, the
installer will install and initialize Julia, and clone and initialize all the
tutorial packages. This may take 5 to 10 minutes, depending on the speed of
your CPU, the hard drive, and the network. When the installation is finished,
the IDE pops up.

2. Open the folder of the tutorial in the IDE. For instance
`FinEtoolsAcousticsTutorials.jl`. 

3. Start the Julia REPL (command line). Press `ctrl+shift+p` to get the command pallete and type 'Julia'. Select `Julia: Start REPL`. 

4. Finally, open the tutorial you would like to execute (they are in the `src`
subfolder of the tutorials folder). Individual lines can be executed with
`ctrl+enter`, while entire code cells can be executed with `shift+enter`. The
entire file can be executed by  `ctrl+shift+p`, typing `Julia: Execute File`
and selecting this command. The shortcut key combination `alt+ctrl+enter` will
run this command too. In fact, if Julia is not running to begin with, this
shortcut will fire up Julia and execute the file subsequently.


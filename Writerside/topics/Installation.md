# Installation
The basic setups and editor loading.

>Please bear in mind that currently the export is an executable and not a library!

## Pre-requisites

In order to compile this code, you will need to have these applications installed on your system:

- CMake
- GCC or another C++ compiler
- Binutils or another Linker
- Make for compiling (Ninja will work too)

<procedure title="Gathering the files" id="repo-clone">
<p>To start of you will need to clone the repo, this can either be done though the Github Desktop app or through running:
</p>
<code-block lang="bash">
    git clone https://github.com/Unified-Projects/Unified-Game-Engine.git
</code-block>
<p>Once cloned this can then be opened using your preferred IDE. VS-Code has a CMake interpreter and if this is installed, then you can ignore this step.
</p>
</procedure>

<procedure title="Building" id="build-init">
   <p>How to build the Game Engine</p>
   <step>Make a directory called build with <code>mkdir build</code></step>
   <step>Navigate to the folder with <code>cd build</code></step>
   <step>Run Cmake with <code>cmake ..</code></step>
   <step>Run make with <code>make</code></step>
   <p>You can run <code>make</code> from within the build directory whenever you want to compile the executable</p>
</procedure>
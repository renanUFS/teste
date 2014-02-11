Hi, I'm Renan Oliveira, student of Federal University of Sergipe, 
and I'm studying and developing programs in openCL.

I will use the IDE Microsoft Visual Studio 2010 Express because 
it's the lastest version that runs on Windows XP. 
And the ATIStream SDK 2.6 (SDK for openCL) for purposes of compatibility with the O.S.

Before we can make some tasks with opencl in VS, we need to establish 
the 'connection' between the SDK and the VS.

To do so:

In the VS, with a project C created, go to:

1º Project > Configuration Properties > C/C++ > General > Additional Include Directories >
add the folder include from your SDK, mine is: "C:\Arquivos de programas\ATI Stream\include"

2º Project > Configuration Properties > Linker > General > Additional Library Directories >
add the folder lib from your SDK, mine is: "C:\Arquivos de programas\ATI Stream\lib\x86"

3º Project > Configuration Properties > Linker > Input > Additional Dependencies >
add openCL.lib

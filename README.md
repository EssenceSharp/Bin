Bin
===

Binary executable files (.exe, .dll, etc.) that either implement Essence#, or are produced by the Essence# compiler. 
Currently, all the binary executables in the repository are ones that implement Essence#, because the Essence# compiler is not yet able to generate binary executable files.

The default location is %EssenceSharpPath%\Bin, although the Essence# system currently does not care where the Bin folder may be located (but that may change, once the Essence# compiler is able to generate .DLL files.)

The repository is organized first by processor architecture (x86, x64), then by .Net framework version: 35 -> .Net 3.5; 40 -> .Net 4.0+.

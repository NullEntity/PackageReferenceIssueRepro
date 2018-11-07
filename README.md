This repo shows the issues I'm having with referencing the 
FSharp.Compiler.Tools package from an old format project.
I believe there are no Restore targets by default so MSBuild
doesn't know how to restore the compiler package which
includes the build/restore targets.

<p align="center">
  <a href="https://fluidb.icu"><img src="/img/logo.png" alt="fluidB"></a>
</p>
<p align="center">  
  
## fluexe- module for running external program

## Quick Start Guide

Here's what you need to do to build your first module:

0. Build fluidB in a build supporting modules.
1. Build librmutil and the module by running `make`. (you can also build them seperatly by running `make` in their respective dirs)
2. include the module in the fluidb.conf: `loadmodule /path/to/my_module.so`

Now run `clif`  and try the commands:

```
flusql:~> system.exec "id"
"uid=0(root) gid=0(root) groups=0(root)\n"
flusql:~> system.exec "whoami"
"root\n"
flusql:~> system.rev 127.0.0.1 9999
```


    

# tunerpro
Tunerpro RT information, patches and DLLS

in ida pro you can apply a patch in tunerpro.exe (version 5.0.0.9827.00) at this address (00452477) to bypass the 10 seconds wait for unregistered users.
patched: .text:00452477                 cmovz   ecx, ecx
orignal: .text:00452477                 cmovz   ecx, edx

##ClangObfuscator
###Nope this version won't get any update from me.
###But hey, it's not complicate at all and you should be able to fix any issue by yourself
>You Must Be This Tall To Ride

>>Part Of My Private LLVM Compiler System. This version is a few commits below the one in my private repo.

>>A Simple Objective-C Class/Method Obfuscator Based On Clang As Front End.

>>Tencent ShenZhen Applied Objective-C Class/Method Obfuscation As Their Patent LMAO.

>>When whould they buy Apple and LLVM, then sue me for violating their "Patent"? Ewww I'm So Afraid.

>ToDo:In-AST Replacement
###Details:
>Debugging infos are printed using llvm::errs()---NOT REDIRECTABLE

>"Useful" infos are printed using std::---REDIRECTABLE

>So just run the plugin normally with >PATHTOOUTPUTFOLDER/Output.h would do

>That GenerateStrings.py is used for generating obfuscation characters base.

>The other .py is a wrapper for loading this plugin

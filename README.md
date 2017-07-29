# NeonObf
NeonObf-uscator is start-up obfuscator

## Usage
java -jar NeonObf.jar <jar_to_obfuscate> <jar_to_obfuscate_out> </path/to/libs/> <_transformers> <min/norm/max>

Example: java -jar NeonObf.jar IN.jar OUT.jar libs SourceFileRemover;LineNumberObfuscation;FinalRemover;LocalVariableNameObfuscator;BasicTypesEncryption;GotoFloodObfuscation;CodeHider max

It's highly recommended to use ProGuard with short names obfuscation before NeonObf (ASM are buggy and eats a lot of memory)

## License
Apache =_=

## Communications with author
Skype: moofMonkey

VK: https://new.vk.com/moofmonkey.java

## Needed APIs
ObjectWeb ASM v6.0 (BETA):

 - asm-core
 - asm-analysis
 - asm-commons
 - asm-tree
 - asm-util

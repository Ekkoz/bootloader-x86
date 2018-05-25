# x86 bootloader

## Project

This is a simple bootloader for a x86 system used only for academic and research purposes only.

## Usage

### Compilation

[NASM](https://en.wikipedia.org/wiki/Netwide_Assembler) must be installed to compile the code.

```
make
```

### Running

QEmu or Bochs can be used to try the bootloader. For example, with QEmu:

```
qemu-system-x86_64 -drive format=raw,file=bootloader-x86.bin
```

## References

* [Wikibooks - X86 Assembly/Bootloaders](https://en.wikibooks.org/wiki/X86_Assembly/Bootloaders) ;
* [Joe Bergeron - Writing a Tiny x86 Bootloader](http://joebergeron.io/posts/post_two.html) ;
* [Alex Parker - Writing a Bootloader](http://3zanders.co.uk/2017/10/13/writing-a-bootloader/) ;

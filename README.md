# Learning-Resources

These are some general CTF related topics plus some good resouces for learning.
Note that CTFs can go from trivially easy to extremely demanding.

## General

- Reading and understanding Python code

## Web Exploitation
- XML
- SQL
- SQL Injection
- Web Parameter Tampering
- Creating and setting cookies manually (Browser extensions)

[SQL Fiddle](http://sqlfiddle.com/)

[OWASP Testing for SQLi](https://www.owasp.org/index.php/Testing_for_SQL_Injection_(OTG-INPVAL-005))

## Binary Exploitation
- Reading and understanding C source code
- Decimal, hexadecimal and binary encoding
- Memory and address space layout
- Using shellcode from [external sources](shell-storm.org)

Advanced:
- Writing shellcode

## Forensics
- Knowing file system formats
- Using grep to find files
- Networking basics (TCP/IP, Server-Client, Headers, IP, MAC, etc)
- Analyzing PCAP files with `tshark` or `wireshark`

[PCAP Display Filters](https://wiki.wireshark.org/DisplayFilters)

## Cryptography
- Bitwise Operators
- Breaking substitution ciphers (using [the Black Chamber](http://www.simonsingh.net/The_Black_Chamber/substitutioncrackingtool.html))
- Building password crackers
- Breaking repeated single and multi byte XOR ciphers
- Breaking shift ciphers
- Looking up messages for hash values with a given salt

## Reverse Engineering
- Disassembling ELF flies with objdump
- Understanding an reading Java code
- Understanding x86 assembly control flow graphs
- x86 assembly
- Decompiling Java classes

## Assembly Guide
Assembly is mostly important for RE / debugging which in turn is the foundation for more advanced topics like exploit development. Writing own ASM code has a low priority since you will only write shellcode which is generally short and probably the least demanding part of exploitation.

1. [SecurityTube's Assembly Primer](https://www.youtube.com/watch?v=K0g-twyhmQ4&list=PL6brsSrstzga43kcZRn6nbSi_GeXoZQhR)
2. [SecurityTube's Windows Assembly Primer](https://vimeo.com/16496874)
3. [OST's Intro to x86](http://www.opensecuritytraining.info/IntroX86.html)
4. [Reverse Engineering Tutorials](http://octopuslabs.io/legend/blog/sample-page.html)

After this you are ready for RE-centered CtFs like [microcurruption](https://www.microcorruption.com/login). Also you can now dive into exploit development.

Reference: [ASM instructions](http://x86.renejeschke.de/)

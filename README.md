# Learning-Resources

These are some general CTF related topics plus some good resouces for learning.
Note that CTFs can go from trivially easy to extremely demanding.
There is no priority since the categories are mostly separated. You can be an expert at web exploitation but fail miserably at crypto. There are some synergistic advantages due to improved lateral thinking tho. But inside of the categories, the topics are ordered roughly by relevance so you could work through them top-down.

## General

- Reading and understanding Python code

## Web Exploitation
- Web Parameter Tampering
- Creating and setting cookies manually (Browser extensions)
- Parsing web data (`requests`, `lxml`, `BeautifulSoup`, etc)
- XML
- SQL
- SQL Injection

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
- Understanding Unix commands and permissions
- Knowing file system formats
- Knowing about magic numbers and determining file signatures
- Using grep to find files
- Networking basics (TCP/IP, Server-Client, Headers, IP, MAC, etc)
- Analyzing PCAP files with `tshark` or `wireshark`

[PCAP Display Filters](https://wiki.wireshark.org/DisplayFilters)

[List of file signatures](https://en.wikipedia.org/wiki/List_of_file_signatures)

[More file signatures](http://www.garykessler.net/library/file_sigs.html)

## Cryptography
- Bitwise Operators
- Breaking substitution ciphers (using [the Black Chamber](http://www.simonsingh.net/The_Black_Chamber/substitutioncrackingtool.html) and `grep` on a word list)
- Building password crackers
- Breaking repeated single and multi byte XOR ciphers
- Breaking shift ciphers
- Calculating RSA with online tools
- Looking up messages for hash values with a given salt

Start here: [cryptopals](https://cryptopals.com/)

## Reverse Engineering
- x86 assembly (see guide)
- Understanding and reading Java code
- Decompiling Java classes
- Disassembling ELF flies with objdump
- Understanding x86 assembly control flow graphs

## Assembly Guide
Assembly is mostly important for RE / debugging which in turn is the foundation for more advanced topics like exploit development. Writing own ASM code has a low priority since you will only write shellcode which is generally short and probably the least demanding part of exploitation.

1. [SecurityTube's Assembly Primer](https://www.youtube.com/watch?v=K0g-twyhmQ4&list=PL6brsSrstzga43kcZRn6nbSi_GeXoZQhR)
2. [SecurityTube's Windows Assembly Primer](https://vimeo.com/16496874)
3. [OST's Intro to x86](http://www.opensecuritytraining.info/IntroX86.html)
4. [Reverse Engineering Tutorials](http://octopuslabs.io/legend/blog/sample-page.html)

After this you are ready for RE-centered CtFs like [microcurruption](https://www.microcorruption.com/login). Also you can now dive into exploit development.

Reference: [ASM instructions](http://x86.renejeschke.de/)

## Programming

# Haskell

[FFPiHaskell der Uni Bielefeld](https://www.youtube.com/playlist?list=PLMqFm6rr-xOXK8G2O31Kdzllm3aYaaRKG)
[+ Übungen](https://github.com/FFPiHaskell/Vorlesung2016)
[happylearnhaskelltutorial.com](http://www.happylearnhaskelltutorial.com/contents.html)
[CIS194 by Penn University](https://www.seas.upenn.edu/~cis194/spring15/) also refers to other sources like [LYAH](http://learnyouahaskell.com/) and [Real World Haskell](http://book.realworldhaskell.org/)

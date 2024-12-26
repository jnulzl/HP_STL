# HP-STL(Alexander Stepanov,  The Father of STL)

- Alexander Stepanov and Meng Lee: The Standard Template Library, HP Laboratories, release of October 31, 1995.

  - Release directory. Contains STL, FAQ, and related materials. [unpacked](https://www.stepanovpapers.com/butler.hpl.hp/stl/index.html) (originally from ftp://butler.hpl.hp.com/stl/)

  - [stl.zip](https://www.stepanovpapers.com/butler.hpl.hp/stl/stl.zip) [unpacked](https://www.stepanovpapers.com/butler.hpl.hp/stl/stl/index.html) (originally from ftp://butler.hpl.hp.com/stl/stl.zip)

- Matt Austern with Hans Boehm (managed by Alexander Stepanov). SGI Standard Template Library. Source code and documentation for the version of the Standard Template Library developed at Silicon Graphics, Inc. during 1996-1999. ([online at sgi.com/tech/stl/ via Internet Archive](https://web.archive.org/web/20171202101253/http://www.sgi.com:80/tech/stl/))
- Bjarne Stroustrup and Alex Stepanov: Standard Container Benchmark, version 0.9. May 2003 [C++](https://www.stepanovpapers.com/container_benchmark.cpp)

## Source codes

- The Standard Template Library, HP Laboratories, release of October 31, 1995

```shell
# Release directory. Contains STL, FAQ, and related materials. [unpacked](https://www.stepanovpapers.com/butler.hpl.hp/stl/index.html) (originally from ftp://butler.hpl.hp.com/stl/)
.
├── README.md
├── bfhash
│   ├── DOC.PS
│   ├── HASH.H
│   ├── HASHBASE.H
│   ├── IMP.PS
│   ├── READ.ME
│   └── TRIPLE.H
├── bfhash.Z
├── bfhash.zip
├── bulletin
├── dd
├── dmhash
│   ├── HASH1.C
│   ├── HASHDOC.PS
│   ├── HASHFUN.H
│   ├── HASHIMP2.PS
│   ├── HASHMAP.H
│   ├── HASHMMAP.H
│   ├── HASHMSET.H
│   ├── HASHRAT.PS
│   ├── HASHSET.H
│   ├── HASHTBL.H
│   ├── READ.ME
│   └── SLIST.H
├── dmhash.Z
├── dmhash.zip
├── examples
│   ├── ACCUM1.CPP
│   ├── ACCUM2.CPP
│   ├── ADJDIFF0.CPP
│   ├── ADJDIFF1.CPP
│   ├── ADJDIFF2.CPP
│   ├── ADJFIND0.CPP
│   ├── ADJFIND1.CPP
│   ├── ADJFIND2.CPP
│   ├── ADVANCE.CPP
│   ├── ALG1.CPP
│   ├── ALG2.CPP
│   ├── ALG3.CPP
│   ├── ALG4.CPP
│   ├── ALG5.CPP
│   ├── ALLOC1.CPP
│   ├── BCOMPOS1.CPP
│   ├── BCOMPOS2.CPP
│   ├── BIND1ST1.CPP
│   ├── BIND1ST2.CPP
│   ├── BIND2ND1.CPP
│   ├── BIND2ND2.CPP
│   ├── BINSERT1.CPP
│   ├── BINSERT2.CPP
│   ├── BINSRCH1.CPP
│   ├── BINSRCH2.CPP
│   ├── BNEGATE1.CPP
│   ├── BNEGATE2.CPP
│   ├── BVEC1.CPP
│   ├── COPY1.CPP
│   ├── COPY2.CPP
│   ├── COPY3.CPP
│   ├── COPY4.CPP
│   ├── COPYB.CPP
│   ├── COPYB0.CPP
│   ├── COUNT0.CPP
│   ├── COUNT1.CPP
│   ├── COUNTIF1.CPP
│   ├── DATA.TXT
│   ├── DEQUE1.CPP
│   ├── DIVIDES.CPP
│   ├── EQLRNGE0.CPP
│   ├── EQLRNGE1.CPP
│   ├── EQLRNGE2.CPP
│   ├── EQUAL0.CPP
│   ├── EQUAL1.CPP
│   ├── EQUAL2.CPP
│   ├── EQUALTO.CPP
│   ├── ERROR1.CPP
│   ├── ERROR2.CPP
│   ├── ERROR3.CPP
│   ├── FILL1.CPP
│   ├── FILLN1.CPP
│   ├── FIND0.CPP
│   ├── FIND1.CPP
│   ├── FINDIF0.CPP
│   ├── FINDIF1.CPP
│   ├── FINSERT1.CPP
│   ├── FINSERT2.CPP
│   ├── FOREACH0.CPP
│   ├── FOREACH1.CPP
│   ├── FUNC1.CPP
│   ├── FUNC2.CPP
│   ├── FUNC3.CPP
│   ├── GENER1.CPP
│   ├── GENER2.CPP
│   ├── GENERN1.CPP
│   ├── GENERN2.CPP
│   ├── GREATEQ.CPP
│   ├── GREATER.CPP
│   ├── INCL0.CPP
│   ├── INCL1.CPP
│   ├── INCL2.CPP
│   ├── INPLMRG1.CPP
│   ├── INPLMRG2.CPP
│   ├── INRPROD0.CPP
│   ├── INRPROD1.CPP
│   ├── INRPROD2.CPP
│   ├── INSERT1.CPP
│   ├── INSERT2.CPP
│   ├── IOTA1.CPP
│   ├── ISTMIT1.CPP
│   ├── ISTMIT2.CPP
│   ├── ITER1.CPP
│   ├── ITER2.CPP
│   ├── ITER3.CPP
│   ├── ITER4.CPP
│   ├── ITERSWP0.CPP
│   ├── ITERSWP1.CPP
│   ├── LESS.CPP
│   ├── LESSEQ.CPP
│   ├── LEXCMP1.CPP
│   ├── LEXCMP2.CPP
│   ├── LIST1.CPP
│   ├── LIST2.CPP
│   ├── LIST3.CPP
│   ├── LIST4.CPP
│   ├── LOGICAND.CPP
│   ├── LOGICNOT.CPP
│   ├── LOGICOR.CPP
│   ├── LWRBND1.CPP
│   ├── LWRBND2.CPP
│   ├── MAP1.CPP
│   ├── MAX1.CPP
│   ├── MAX2.CPP
│   ├── MAXELEM1.CPP
│   ├── MAXELEM2.CPP
│   ├── MERGE0.CPP
│   ├── MERGE1.CPP
│   ├── MERGE2.CPP
│   ├── MIN1.CPP
│   ├── MIN2.CPP
│   ├── MINELEM1.CPP
│   ├── MINELEM2.CPP
│   ├── MINUS.CPP
│   ├── MISMTCH0.CPP
│   ├── MISMTCH1.CPP
│   ├── MISMTCH2.CPP
│   ├── MKHEAP0.CPP
│   ├── MKHEAP1.CPP
│   ├── MMAP1.CPP
│   ├── MMAP2.CPP
│   ├── MODULUS.CPP
│   ├── MSET1.CPP
│   ├── MSET2.CPP
│   ├── MSET3.CPP
│   ├── MSET4.CPP
│   ├── MSET5.CPP
│   ├── MYALOC.H
│   ├── NEGATE.CPP
│   ├── NEQUAL.CPP
│   ├── NEXTPRM0.CPP
│   ├── NEXTPRM1.CPP
│   ├── NEXTPRM2.CPP
│   ├── NTHELEM0.CPP
│   ├── NTHELEM1.CPP
│   ├── NTHELEM2.CPP
│   ├── OSTMIT.CPP
│   ├── OVERVIEW.STL
│   ├── PAIR0.CPP
│   ├── PAIR0.OLD
│   ├── PAIR1.CPP
│   ├── PAIR2.CPP
│   ├── PARSRT0.CPP
│   ├── PARSRT1.CPP
│   ├── PARSRT2.CPP
│   ├── PARSRTC0.CPP
│   ├── PARSRTC1.CPP
│   ├── PARSRTC2.CPP
│   ├── PARTSRT0.CPP
│   ├── PARTSUM0.CPP
│   ├── PARTSUM1.CPP
│   ├── PARTSUM2.CPP
│   ├── PHEAP1.CPP
│   ├── PHEAP2.CPP
│   ├── PLUS.CPP
│   ├── PQUEUE1.CPP
│   ├── PQUEUE2.CPP
│   ├── PREVPRM0.CPP
│   ├── PREVPRM1.CPP
│   ├── PREVPRM2.CPP
│   ├── PTITION0.CPP
│   ├── PTITION1.CPP
│   ├── PTRBINF1.CPP
│   ├── PTRBINF2.CPP
│   ├── PTRUNF1.CPP
│   ├── PTRUNF2.CPP
│   ├── QUEUE1.CPP
│   ├── RAWITER.CPP
│   ├── README.STL
│   ├── RELEASE1.CPP
│   ├── RELEASE2.CPP
│   ├── REMCOPY1.CPP
│   ├── REMCPIF1.CPP
│   ├── REMIF1.CPP
│   ├── REMOVE1.CPP
│   ├── REPCPIF1.CPP
│   ├── REPLACE0.CPP
│   ├── REPLACE1.CPP
│   ├── REPLCPY1.CPP
│   ├── REPLIF1.CPP
│   ├── REVBIT1.CPP
│   ├── REVBIT2.CPP
│   ├── REVCOPY1.CPP
│   ├── REVERSE1.CPP
│   ├── REVITER1.CPP
│   ├── REVITER2.CPP
│   ├── RNDSHUF0.CPP
│   ├── RNDSHUF1.CPP
│   ├── RNDSHUF2.CPP
│   ├── ROTATE0.CPP
│   ├── ROTATE1.CPP
│   ├── ROTCOPY0.CPP
│   ├── ROTCOPY1.CPP
│   ├── SEARCH0.CPP
│   ├── SEARCH1.CPP
│   ├── SEARCH2.CPP
│   ├── SET1.CPP
│   ├── SET2.CPP
│   ├── SETDIFF0.CPP
│   ├── SETDIFF1.CPP
│   ├── SETDIFF2.CPP
│   ├── SETINTR0.CPP
│   ├── SETINTR1.CPP
│   ├── SETINTR2.CPP
│   ├── SETSYMD0.CPP
│   ├── SETSYMD1.CPP
│   ├── SETSYMD2.CPP
│   ├── SETUNON0.CPP
│   ├── SETUNON1.CPP
│   ├── SETUNON2.CPP
│   ├── SORT1.CPP
│   ├── SORT2.CPP
│   ├── STACK1.CPP
│   ├── STACK2.CPP
│   ├── STBLPTN0.CPP
│   ├── STBLPTN1.CPP
│   ├── STBLSRT1.CPP
│   ├── STBLSRT2.CPP
│   ├── SWAP1.CPP
│   ├── SWPRNGE1.CPP
│   ├── TIMES.CPP
│   ├── TRNSFRM1.CPP
│   ├── TRNSFRM2.CPP
│   ├── UCOMPOS1.CPP
│   ├── UCOMPOS2.CPP
│   ├── UNEGATE1.CPP
│   ├── UNEGATE2.CPP
│   ├── UNIQCPY1.CPP
│   ├── UNIQCPY2.CPP
│   ├── UNIQUE1.CPP
│   ├── UNIQUE2.CPP
│   ├── UPRBND1.CPP
│   ├── UPRBND2.CPP
│   ├── VEC1.CPP
│   ├── VEC2.CPP
│   ├── VEC3.CPP
│   ├── VEC4.CPP
│   ├── VEC5.CPP
│   ├── VEC6.CPP
│   ├── VEC7.CPP
│   └── VEC8.CPP
├── examples.Z
├── examples.zip
├── mj_paper.pdf
├── mj_paper.ps
├── safeit.h
├── sharfile
├── sharfile.Z
├── stl
│   ├── ALGO.H
│   ├── ALGOBASE.H
│   ├── BOOL.H
│   ├── BVECTOR.H
│   ├── DEFALLOC.H
│   ├── DEQUE.H
│   ├── DOC.MIF
│   ├── DOC.PS
│   ├── DOCBAR.PS
│   ├── FARALLOC.H
│   ├── FDEQUE.H
│   ├── FILES.DIF
│   ├── FLIST.H
│   ├── FMAP.H
│   ├── FMULTMAP.H
│   ├── FMULTSET.H
│   ├── FSET.H
│   ├── FUNCTION.H
│   ├── HDEQUE.H
│   ├── HEAP.H
│   ├── HLIST.H
│   ├── HMAP.H
│   ├── HMULTMAP.H
│   ├── HMULTSET.H
│   ├── HSET.H
│   ├── HUGALLOC.H
│   ├── HVECTOR.H
│   ├── ITERATOR.H
│   ├── LBVECTOR.H
│   ├── LDEQUE.H
│   ├── LIST.H
│   ├── LLIST.H
│   ├── LMAP.H
│   ├── LMULTMAP.H
│   ├── LMULTSET.H
│   ├── LNGALLOC.H
│   ├── LSET.H
│   ├── MAP.H
│   ├── MULTIMAP.H
│   ├── MULTISET.H
│   ├── NERALLOC.H
│   ├── NMAP.H
│   ├── NMULTMAP.H
│   ├── NMULTSET.H
│   ├── NSET.H
│   ├── PAIR.H
│   ├── PROJECTN.H
│   ├── RANDOM.CPP
│   ├── READ.ME
│   ├── README.OLD
│   ├── SET.H
│   ├── STACK.H
│   ├── TEMPBUF.CPP
│   ├── TEMPBUF.H
│   ├── TREE.H
│   └── VECTOR.H
├── stl.faq
├── stl.zip
├── wat_stl
│   ├── ALGO.H
│   ├── ALGOBASE.H
│   ├── BOOL.H
│   ├── BVECTOR.H
│   ├── DEFALLOC.H
│   ├── DEQUE.H
│   ├── DOC.PS
│   ├── DOCBAR.PS
│   ├── FILES.DIF
│   ├── FUNCTION.H
│   ├── HEAP.H
│   ├── ITERATOR.H
│   ├── LIST.H
│   ├── MAP.H
│   ├── MULTIMAP.H
│   ├── MULTISET.H
│   ├── PAIR.H
│   ├── PROJECTN.H
│   ├── RANDOM.CPP
│   ├── READ.ME
│   ├── README.OLD
│   ├── SET.H
│   ├── STACK.H
│   ├── TEMPBUF.CPP
│   ├── TEMPBUF.H
│   ├── TREE.H
│   ├── VECTOR.H
│   └── WATCOM.PRT
└── wat_stl.zip

5 directories, 360 files
```

- The other useful files

```
others
├── MinGW-3.0.0-1-gcc3.2.3.exe
├── STLport
│   ├── STLport-2.032.tar.gz
│   └── STLport-5.0.0.tar.gz
├── cygwin-b20-full-gcc2.91.57(egcs-1.1).exe
├── egcs_gcc
│   ├── egcs-1.0.1.tar.bz2
│   ├── egcs-1.0.2.tar.bz2
│   ├── egcs-1.0.3a.tar.bz2
│   ├── egcs-1.0.tar.bz2
│   ├── egcs-1.1.1.tar.bz2
│   ├── egcs-1.1.2.tar.bz2
│   ├── egcs-1.1b.tar.bz2
│   ├── egcs-core-1.1.2.tar.bz2
│   ├── egcs-g++-1.1.2.tar.bz2
│   ├── egcs-g++-tests-1.1.2.tar.bz2
│   ├── egcs-tests-1.1.2.tar.bz2
│   ├── gcc-2.8.0.tar.bz2
│   ├── gcc-2.8.1.tar.bz2
│   ├── gcc-2.95.1.tar.bz2
│   ├── gcc-2.95.2.1.tar.bz2
│   ├── gcc-2.95.2.tar.bz2
│   ├── gcc-2.95.3.tar.bz2
│   └── gcc-2.95.tar.bz2
├── mingw32_gcc2.95.2.zip
├── mingw32_gcc2.95.3.zip
├── pdfs
│   ├── STL扩展技术手册  卷1  集合和迭代器 -- 威尔森著,金庆等译 -- 2008 -- 北京_机械工业出版社.pdf
│   ├── STL源码剖析
│   │   ├── STL源码剖析 (侯捷).pdf
│   │   ├── STL源码剖析（简体批注版）.pdf
│   │   ├── STL源码剖析（繁体批注版）tass-20020106.pdf
│   │   ├── tass-sgi-stl-2.91.57-annotated.zip
│   │   ├── tass-sgi-stl-2.91.57-source.zip
│   │   ├── 《STL 源码剖析》简体版勘误.txt
│   │   └── 《STL 源码剖析》繁体版勘误.txt
│   ├── generic programming and thd stl using and extending the c++ -- (美)MATTHEW H_AUSTERN 著 -- 2003.pdf
│   ├── 标准模板库自修教程与参考手册 STL进行C++编程  第2版 -- (美)David_R_Musser等编著;贺民,王朝阳译 -- 2003 -- 北京_科学出版社.pdf
│   └── 泛型编程与STL -- (美)Matthew H_Austern著;侯捷译 -- 2003 -- 北京_中国电力出版社.pdf
└── sgi_stl
    ├── Download_STL_source_code.url
    ├── STL_doc.zip
    ├── ms-brlnd.zip
    ├── stl2.03.zip
    ├── stl3.0.zip
    ├── stl3.1.1.zip
    ├── stl3.1.2.zip
    ├── stl3.1.3.zip
    ├── stl3.2.zip
    └── stl3.3.zip

5 directories, 45 files
```

## Reference

- [Alexander A. Stepanov](https://www.stepanovpapers.com/)

- [Standard Template Library Programmer's Guide(SGI-STL) from http://zx.net.nz/mirror](http://zx.net.nz/mirror/www.sgi.com/tech/stl/index.html)

- [Standard Template Library Programmer's Guide(SGI-STL) from www.cs.cmu.edu](https://www.cs.cmu.edu/afs/cs.cmu.edu/user/gchen/www/download/stl/index.html)

- [Standard Template Library Programmer's Guide(SGI-STL) from www.boost.org(without download)](https://www.boost.org/sgi/stl/)

- [Arthur H. Lee](https://www3.cs.stonybrook.edu/~alee/)

- [Installing c++/g++ on Windows](https://www3.cs.stonybrook.edu/~alee/g++/g++.html)

- [侯捷网站(f来自web.archive.org)](https://web.archive.org/web/20050405162104fw_/http://jjhou.csdn.net/)

- [STL 源码剖析(侯捷主页)](https://web.archive.org/web/20050405195454fw_/http://jjhou.csdn.net/jjwbooks-tass.htm)

- [HP_STL_Directory_Tree](https://www.stepanovpapers.com/butler.hpl.hp/stl/stl/index.html)

- [Safe STL(Cay S. Horstmann)](https://horstmann.com/safestl.html)

- [stlport](http://www.stlport.org/)

- [GCC Releases](https://gcc.gnu.org/releases.html)

- [Old GCC Archives](https://ftp.gwdg.de/pub/misc/gcc/old-releases/)

- [steveLauwh/SGI-STL](https://github.com/steveLauwh/SGI-STL)

- [TBLGSn/SGI-STL](https://github.com/TBLGSn/SGI-STL)

- [boostorg/container](https://github.com/boostorg/container)

- [Eclipse IDE for C/C++ Developers(for view source codes)](https://www.eclipse.org/downloads/packages/release/2024-12/r/eclipse-ide-cc-developers)
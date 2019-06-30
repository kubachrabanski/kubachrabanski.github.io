## Projects

---

### Recent

- [Kakainet, ImageToLatex](https://github.com/kakainet/ImageToLatex)  __[python, ocaml (core), dune]__   

    __[01/07/2019]__ _currently working on random latex expression generators, with various syntactic levels and conspects           describing exact behaviour within the level, here is an example of L1:1 (2, 5, 512, 50.0) latex expression:_
    
    __\frac{378 \mathbin{/} 493 \cdot \left(-277\right)}{\left(-275\right) \mathbin{/} 46 - 332}__

    <img src="https://github.com/kubachrabanski/kubachrabanski.github.io/blob/master/images/1.png?raw=true"/>
 
---

### At the university

- [indexer_searcher](https://github.com/kubachrabanski/indexer_searcher) __[java, maven]__

    a pair of tools for indexing and searching through document contents, with support for directory monitoring and
    queries with context highlighting

    ```
    > %details on  
    > %color on  
    > release   
    File count: 1  
    /Users/kuba/Documents/TEST/refman-8.0-en.pdf
    It documents MySQL 8.0 through 8.0.18, as well as NDB Cluster releases  
    based on version 8.0 of NDB through 8.0.18-ndb-8.0.18, respectively. It may include documentation of features of  
    MySQL versions that have not yet been released. For information about which versions have been released, see the  
    MySQL 8.0 Release Notes.  
    ... For notes detailing the changes in each release, see the MySQL 8.0 Release Notes.  
      
    >   
    ```
    
---

- [sudoku_backtrack](https://github.com/kubachrabanski/sudoku_backtrack) __[ocaml (core), dune]__

    a heuristic based, backtracking sudoku solver, supporting __any__ subgrid-divisible puzzle,  
    here is an example result of __[16 x 16]__ sudoku solving:
    
    ```
    $ dune exec bin/run.exe < ...
    7  13 1  15 3  12 11 10 5  4  8  9  6  2  14 16 
    9  12 11 10 2  8  13 5  14 16 6  3  1  4  15 7  
    6  14 16 5  9  4  1  15 7  13 2  12 8  3  11 10 
    2  8  3  4  6  14 16 7  11 10 1  15 5  13 12 9  
    13 15 9  2  5  11 8  16 4  12 7  6  14 10 3  1  
    8  3  14 16 4  1  15 12 10 9  13 2  7  5  6  11 
    11 5  12 6  10 13 7  2  1  3  14 8  15 9  16 4  
    10 1  4  7  14 6  3  9  15 11 16 5  13 8  2  12 
    16 7  5  3  11 10 2  4  6  14 12 13 9  15 1  8  
    1  4  13 9  15 16 6  3  2  8  5  11 10 12 7  14 
    15 2  10 14 8  9  12 13 16 7  3  1  4  11 5  6  
    12 6  8  11 7  5  14 1  9  15 4  10 2  16 13 3  
    5  16 2  12 1  15 4  11 8  6  9  14 3  7  10 13 
    4  9  15 1  13 7  10 6  3  2  11 16 12 14 8  5  
    3  11 6  8  12 2  9  14 13 5  10 7  16 1  4  15 
    14 10 7  13 16 3  5  8  12 1  15 4  11 6  9  2  
    ```
    

---
### For learning purposes

- [OCaml-AVL](https://github.com/kubachrabanski/OCaml-AVL)

```ocaml

(* example use of Avl module *)

open Avl

type ('k, 'v) t = ('k * 'v) Avl.t

let find ?compare k t = Avl.find ?compare ~key:fst ~value:snd k t

(* Avl is restructured into a polimorphic map *)

```

---

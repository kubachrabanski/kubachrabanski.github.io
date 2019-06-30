## Projects

---

### Recent

- [Kakainet, ImageToLatex](https://github.com/kakainet/ImageToLatex)
    
    __[01/07/2019]__ _currently working on random latex expression generators, with various syntactic levels and conspects           describing exact behaviour within the level, here is an example of L1:1 (2, 5, 512, 50.0) latex expression:_
    
    __\frac{378 \mathbin{/} 493 \cdot \left(-277\right)}{\left(-275\right) \mathbin{/} 46 - 332}__

    <img src="https://github.com/kubachrabanski/kubachrabanski.github.io/blob/master/images/1.png?raw=true"/>

---

### At the university

- [indexer_searcher](https://github.com/kubachrabanski/indexer_searcher)

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

- [sudoku_backtrack](https://github.com/kubachrabanski/sudoku_backtrack)
<!---
<img src="images/dummy_thumbnail.jpg?raw=true"/>
--->

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

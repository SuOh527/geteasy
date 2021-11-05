---
layout: post
type:  
title: "C Source file vs. Header file"
date: 2021-11-05 17:00:00 
category: C 
hash-tag: C
  
---



# Header file.h

### Definitions
- Implementations for the interfaces in the header file
- ⊃ Static functions (being called even uninitialized nor uninstantiated)

stdio.h; func.h (Macro arguments)
_Macro : Pre-processed or Always-True functions_



# Source file.c

### Declarations
- Prototypes
- Interfaces
- ⊃ "#include file.h"

main.c ; func.c (Custom arguments)
_Custom : Not preprocessed but Instantiated in the file only_
---
layout: post
type:  
title: "C Source file vs. Header file"
date: 2021-11-05 17:00:00 
category: C 
hash-tag: C
  
---



# Header file.h
### stdio.h; func.h (Macro arguments)
_Macro_ : Pre-processed or Always-True functions

Definitions
- Implementations for the interfaces in the header file
- ⊃ Static functions (being called even uninitialized nor uninstantiated)




# Source file.c
### main.c ; func.c (Custom arguments)
_Custom_ : Not preprocessed but Instantiated in the file only

Declarations
- Prototypes
- Interfaces
- ⊃ "#include file.h"

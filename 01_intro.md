# intro to compilers

## intro
- compilers
  - program -> **compiler** -> exec
  - data -> exec -> output
  - off-line
- interpreters
  - program & data -> **interpreter** -> output
  - on-line
- FORTRAN I
  - first high level language
  - modern compilers preserve outline of it
- outline
  1. lexical analysis
  2. parsing
    -> syntactic
  3. semantic analysis
    -> semantic, type, scope
  4. optimization
  5. code generation
    -> translation

## structure
- first step: recognize words
  - goal of **lexical analysis**: divide program text into "words" or "tokens"
  - goal of **parsing**: understand sentence structure
    - parsing = diagramming sentences
      - the diagram is a tree
  - **semantic analysis**: understand "meaning"
    - too hard!
    - compilers perform *limited* semantic analysis to *catch inconsistencies*
  - **optimization**
    - run faster
    - use less memory
    - power
    - network
    - database
    - e.g. x = y * 0 <=> x = 0
      - NO!
      - valid for integers
      - invalid for FP
      - NAN * 0 = NAN
  - **code generation**: produce assembly code (usually)
    - translation
- outline stays the same but proportions have changed

## economy of programming languages

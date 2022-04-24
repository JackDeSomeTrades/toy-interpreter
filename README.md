# toy-interpreter

Prepared as a toy example for IN104 to demonstrate to students the creation of their own language and interpreter. 

The current project uses: 

* Flex (as the lexer)
* Bison (as the Parser)
* C (for the interpreter itself)


## Small documentation: 

LOTR Quotes based language  ;_;

* Brackets define a function -  ()
* Indents define scope
* Every program must contain a main function named: "FLY YOU FOOLS"
* functions must be defined as GANDALF SAYS
* Errors should be presented as: FOOL OF A TOOK
* Return statements: MY PRECIOUS
* for: WANDER OVER <int> UNTIL <condition> 
* while: RENEW BLADE 
* integers/floats : POTATOES
* strings: STEW
* assignment operator ":="
* print: MELLON (say friend, and enter) 
* comments :   #
* if-else statements are enclosed as : IF <true> TAKING THE RING (condition)  <false> UNKNOWN WAY (condition)


#### Example:
```

GANDALF SAYS print_10_ints():
    POTATO counter :=10
    POTATO i
    WANDER OVER i UNTIL (0, counter, 1)
        MELLON i

GANDALF SAYS print_ints_here():
    POTATO counter := 0
    POTATO done := False
    IF counter < 10 TAKING THE RING
        MELLON counter
        counter := counter + 1 
    done := True
    MY PRECIOUS done 

FLY YOU FOOLS:
    STEW success:= "We are done here"
    done := print_ints_here()
    IF done TAKING THE RING
        MELLON success
```
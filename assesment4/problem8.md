// febonacci series

START
    INPUT n
    
    IF n <= 0 THEN
        OUTPUT "Please enter a positive integer"
        END
    END IF
    
    first = 0
    second = 1
    
    OUTPUT first
    
    IF n > 1 THEN
        OUTPUT second
    END IF
    
    FOR i = 3 TO n
        next = first + second
        OUTPUT next
        first = second
        second = next
    END FOR
END
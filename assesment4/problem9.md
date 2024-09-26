// Count of divisors 

START
    INPUT n
    
    IF n <= 0 THEN
        OUTPUT "Please enter a positive integer"
        END
    END IF
    
    count = 0
    
    FOR i = 1 TO n
        IF n MOD i = 0 THEN
            count = count + 1
        END IF
    END FOR
    
    OUTPUT count
END
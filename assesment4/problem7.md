// Count of even numbers

START
    INPUT n
    
    count = 0
    
    FOR i = 1 TO n
        IF i MOD 2 = 0 THEN
            count = count + 1
        END IF
    END FOR
    
    OUTPUT count
END
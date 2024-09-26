// Fizzbuzz detector 

START
    FOR number = 1 TO 50
        IF (number MOD 3 = 0) AND (number MOD 5 = 0) THEN
            OUTPUT "FizzBuzz"
        ELSE IF number MOD 3 = 0 THEN
            OUTPUT "Fizz"
        ELSE IF number MOD 5 = 0 THEN
            OUTPUT "Buzz"
        ELSE
            OUTPUT number
        END IF
    END FOR
END
//Finding the leap year

START
    INPUT year
    
    IF (year MOD 4 = 0 AND year MOD 100 != 0) OR (year MOD 400 = 0) THEN
        OUTPUT "Leap Year"
    ELSE
        OUTPUT "Not a Leap Year"
    END IF
END
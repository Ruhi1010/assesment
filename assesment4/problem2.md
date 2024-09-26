// Finding the maximum or minimum value

START
    INPUT value1
    INPUT value2
    
    IF value1 > value2 THEN
        OUTPUT value1
    ELSE IF value2 > value1 THEN
        OUTPUT value2
    ELSE
        OUTPUT "Both values are equal"
    END IF
END
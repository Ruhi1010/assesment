// Basic calculator which calculate '+', '-', '*', and '/'

START
    INPUT value1
    INPUT value2
    INPUT operator

    IF operator = "+" THEN
        result = value1 + value2
    ELSE IF operator = "-" THEN
        result = value1 - value2
    ELSE IF operator = "*" THEN
        result = value1 * value2
    ELSE IF operator = "/" THEN
        IF value2 = 0 THEN
            OUTPUT "Error: Division by zero"
            END
        ELSE
            result = value1 / value2
        END IF
    ELSE
        OUTPUT "Error: Invalid operator"
        END
    END IF

    OUTPUT result
END
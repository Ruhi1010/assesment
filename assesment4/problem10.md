// reverse number 

START 
    INPUT num

    reverse = 0

    WHILE num NOT EQUAL 0
        reverse = reverse * 10 + num MOD 10
        num = num / 10
    END WHILE 

    OUTPUT reverse 
END 
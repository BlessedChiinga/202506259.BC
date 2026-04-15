# 202506259.BC
FACTORIAL ASSIGNMENTS

#FACTORIAL WORKFLOW
Start

Input value of n

Check if n < 0

If Yes → Display "Error: Negative Number" and Stop

If No → Move to next step

Check if n = 0 or n = 1

If Yes → Return 1 and Stop

If No → Move to next step

Calculate factorial recursively

Return n × Factorial(n − 1)

End


#FACTORIAL PSUEDOCODE

START

INPUT n

IF n < 0 THEN
    PRINT "Factorial not defined"
ELSE IF n = 0 OR n = 1 THEN
    PRINT 1
ELSE
    SET result ← 1
    FOR i ← 1 TO n DO
        result ← result × i
    END FOR
    PRINT result
END IF

END




#FACTORIAL PYTHON CODE


def factorial(n):

    if n < 0:

        return "Factorial not defined for negative numbers"

    elif n == 0 or n == 1:

        return 1

    else:

        return n * factorial(n - 1)


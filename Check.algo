PROCEDURE Vector(V1,V2 : ARRAY_OF INTEGER[2]; VAR ps:INTEGER)
BEGIN
    FOR i FROM 0 TO 2 STEP 1  DO
            ps := ps + V1[i] * V2[i]
    END_FOR
END

ALGORITHM Vector
VAR
    V1 : ARRAY_OF INTEGER [2];
    V2 : ARRAY_OF INTEGER [2];
    i,j,n,ps : INTEGER
BEGIN
    Write("enter n");
    read(n);

    FOR i FROM 0 TO 2 STEP 1  DO
        Write("enter vector 1")
        read(V1[i])
        Write("enter vector 1")
        read(V2[i])
    END_FOR

  Vector (V1,V2,ps);

        IF (ps == 0) THEN
            Write("are orthogonal");
        ELSE
            Write("are not orthogonal");
        END_IF

END
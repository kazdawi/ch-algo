ALGORITHM cptchar
VAR
    n, i: INTEGER;
    cptchar, cptword, cptvo: INTEGER := 0;
    listevo: STRING := "a,e,i,o,u,y,A,E,I,O,U,Y";
    sentence: STRING := "hello world i am aziz and i study in gomycode.";

BEGIN
    cptchar := LEN(sentence);
    cptword := 1;  
    
    FOR n FROM 1 TO cptchar DO
        // Count words
        IF sentence[n] == " " THEN
            cptword := cptword + 1;
        END IF;

        // Count vowels
        IF sentence[n] IN listevo THEN
            cptvo := cptvo + 1;
        END IF;
    END FOR;

    WRITE("Nombre de char est: ", cptchar);
    WRITE("Nombre de word est: ", cptword);
    WRITE("Nombre de voyelle est: ", cptvo);
END

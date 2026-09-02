# PL_SQL-Learning

Program 1 : Find Sum of two Numbers

DECLARE
a INT;
b INT;
c INT;
begin
    a:=5;
    b:=8;
    c:=a+b;
    dbms_output.put_line('Sum of a and b='||c);
    end;


    
Sum of a and b=13
PL/SQL procedure successfully completed.

Elapsed: 00:00:00.005



Program 2 : Greatest of two numbers


DECLARE
a INT;
b INT;
begin
    a:=5;
    b:=9;
    IF(a>b)
    THEN
    dbms_output.put_line('A is greater='||a);
    else
    dbms_output.put_line('B is greater='||b);
    END IF;
    END;



B is greater=9
PL/SQL procedure successfully completed.

Elapsed: 00:00:00.006



    
Program 3: For Loop


DECLARE
a NUMBER(2);
begin
    FOR a in 0..12
    loop
    dbms_output.put_line(a);
    END loop;
    END;



0
1
2
3
4
5
6
7
8
9
10
11
12

PL/SQL procedure successfully completed.

Elapsed: 00:00:00.005



Program 4 : While loop

DECLARE
a INT;
b INT;
begin
    a:=0;
    b:=15;
    WHILE a<b
    loop 
        a:=a+1;
    dbms_output.put_line(a);
    END loop;
    END;

    
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15

PL/SQL procedure successfully completed.

Elapsed: 00:00:00.006


DECLARE
a INT;
b INT;
begin
    a:=0;
    b:=15;
    WHILE a<b
    loop 
         dbms_output.put_line(a);
        a:=a+1;
    END loop;
    END;

    
0
1
2
3
4
5
6
7
8
9
10
11
12
13
14


PL/SQL procedure successfully completed.

Elapsed: 00:00:00.005



    

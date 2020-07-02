# Implemented-SQL-Parser-using-Lex-and-Yacc
Execute the following steps
$ lex lex.l

$ yacc -d yacc.y

$ gcc lex.yy.c y.tab.c -o lexyacc

$ ./lexyacc
select * from table1 where name=manav

Syntax Correct

select name from table2 where name=manav and surname=sanghavi

Syntax Correct

select * where name=manav

error: syntax error


please dont run in any online terminal
Use Linux for best results..

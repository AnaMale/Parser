# sept

This is edu project implementing MikroJava parser and lexer generator

runnung our JFlex.Main, this is LexerGenerator
argumenti: -d src\rs\ac\bg\etf\pp1 spec\mjlexer.flex


we add new run configuration and call it ParserGenerator 
(using java_cup.Main)	
arguments: -destdir src\rs\ac\bg\etf\pp1 -parser MJParser spec\mjparser.cup
if we want to see whole LR(0) machine we have to add option -dump_states : -destdir    src\rs\ac\bg\etf\pp1 -dump_states -parser MJParser spec\mjparser.cup

test\program.obj

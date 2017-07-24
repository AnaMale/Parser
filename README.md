# sept

pokrecemo nasu klasu JFlex.Main
i to je LexerGenerator
argumenti: -d src\rs\ac\bg\etf\pp1 spec\mjlexer.flex


pokrecemo novu run configuration i zovemo je ParserGenerator 
(koristimo java_cup.Main)	
argumenti: -destdir src\rs\ac\bg\etf\pp1 -parser MJParser spec\mjparser.cup
ako hocemo da vidimo ceo LR(0) automat dodamo opciju -dump_states : -destdir    src\rs\ac\bg\etf\pp1 -dump_states -parser MJParser spec\mjparser.cup

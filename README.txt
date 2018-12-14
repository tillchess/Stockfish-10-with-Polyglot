Stockfish 10 with Polyglot book option by tillchess!


Project: I liked to have Stockfish 10 without changes to the Stockfish code but with the option to use a Polyglot book (.bin) 
- so I can play against SF in  a certain opening line for example.
Book is not used when in Analyis mode!

So I merged some code of BrainFish with Stockfish so SF can use Polyglot opening books.

UCI options

BookFile

If set to the file name of an existing Polyglot .bin opening book file Stockfish uses this book.
If set to an empty string Stockfish relies on the GUI to handle the book. 
Book is not used when in Analyis mode!


BookDepth: 0-255 moves 


BestBookMove : true uses the best book move, otherwise when false a random book move!



-------------------------------

Hint: The Chess GUI should have an option to turn their opening book off . my Chess GUI has this feature. 



Source code of Brainfish: https://zipproth.de/Brainfish/BrainFish_181110_source.zip

Soure code of Stockfish 10 from: https://stockfish.s3.amazonaws.com/stockfish-10-mac.zip



Credits:

Massimiliano Goi also did this on his own

https://chess.massimilianogoi.com/download/stockfish/

Check him out, too!


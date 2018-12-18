# Stockfish 10 with Polyglot book support

I liked to have Stockfish 10 without changes to the Stockfish code but with the option to use a Polyglot book (.bin) .
Book is not used when in Analyis mode!

So I merged some code of BrainFish by Thomas Zipproth with Stockfish so Stockfish can use Polyglot opening books.

# UCI options


BookFile

If set to the file name of an existing Polyglot .bin opening book file Stockfish uses this book.
If set to an empty string Stockfish relies on the GUI to handle the book. 
Book is not used when in Analyis mode!


BookDepth: 0-255 moves 


BestBookMove : true uses the best book move, otherwise when false a random book move!

OwnBook:    this means that the engine has its own book which is accessed by the engine itself.
			if this is set, the engine takes care of the opening book and the GUI will never
			execute a move out of its book for the engine. If this is set to false by the GUI,
			the engine should not access its own book.


# Source code used for this project

Source code of Brainfish: (https://zipproth.de/Brainfish/BrainFish_181110_source.zip)

Soure code of Stockfish 10 from: (https://stockfish.s3.amazonaws.com/stockfish-10-mac.zip)

# License

GPL version 3. 


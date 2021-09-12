INC=/usr/local/ssl/include/
LIB=/usr/local/ssl/lib/

all:
	g++ -I$(INC) -L$(LIB) cli.cpp -o cli -lssl -lcrypto -ldl -fpermissive
	g++ -I$(INC) -L$(LIB) serv.cpp -o serv -lssl -lcrypto -ldl -fpermissive

clean:
	rm -rf *~ cli serv

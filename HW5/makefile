all:Rational.o BigInt.o Complex.o testForRational.cpp testForBigInt.cpp Hw5.cpp
	g++ -o Hw5.test Complex.o Rational.o BigInt.o Hw5.cpp
	g++ -o Rational.test Rational.o BigInt.o testForRational.cpp
	g++ -o BigInt.test BigInt.o testForBigInt.cpp

Complex.o:Complex.h Complex.cpp
	g++ -c Complex.cpp
Rational.o:Rational.h Rational.cpp
	g++ -c Rational.cpp

BigInt.o:BigInt.h BigInt.cpp
	g++ -c BigInt.cpp

clear:
	rm -r *.o *.test

all: .o
	ar rvc libhgehelp.a *.o

.o:
	g++ -DHGE_DIRECTX_VER=9 -std=c++11 -O3 -c *.cpp

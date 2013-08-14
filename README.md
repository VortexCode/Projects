sudo apt-get install gcc build-essential libsdl1.2-dev

sudo apt-get install libsdl1.2-dev

sudo usermod -a -G video [your_username]

gcc `sdl-config --cflags` `sdl-config --libs` -o sdltest 

main.cpp

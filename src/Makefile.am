datadir=/etc/wavedump
bin_PROGRAMS=wavedump
wavedump_SOURCES=fft.c  flash.c  keyb.c  spi.c  WaveDump.c  WDconfig.c  WDplot.c  X742CorrectionRoutines.c
wavedump_LDADD = -lCAENComm -lCAENDigitizer -lm -lpthread
INCLUDES = -I../include
AM_CFLAGS=  -fPIC
dist_data_DATA=../Setup/WaveDumpConfig.txt ../Setup/WaveDumpConfig_X742.txt ../Setup/WaveDumpConfig_X740.txt

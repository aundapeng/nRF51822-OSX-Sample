BOARD := BOARD_NRF6310

C_SOURCE_FILES += main_rx.c
C_SOURCE_FILES += radio_config.c
C_SOURCE_FILES += nrf_delay.c

OUTPUT_FILENAME := radio_rx_example_gcc
SDK_PATH = ../../../../


#Uncomment correct line if you have softdevice programmed on the chip.
#USE_SOFTDEVICE := S110
#USE_SOFTDEVICE := S210

include $(SDK_PATH)Source/templates/gcc/Makefile.common

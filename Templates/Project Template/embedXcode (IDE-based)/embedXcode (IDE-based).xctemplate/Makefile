#
# embedXcode
# ----------------------------------
# Embedded Computing on Xcode 4.3
#
# Copyright © Rei VILO, 2010-2012
# Licence CC = BY NC SA
#


# Parameters
# ----------------------------------
# Xcode takes BOARD_TAG and BOARD_PORT from the .xcconfig file
# For other IDEs than Xcode,

# BOARD_TAG is required
# If not defined, error BOARD_TAG not defined
#
#BOARD_TAG  = mega2560

# BOARD_PORT is optional
# If not defined, BOARD_PORT = /dev/tty.usb* (default)
#
#BOARD_PORT = /dev/tty.usbmodem*

# Xcode takes SKETCHBOOK_DIR from preferences.txt 
# If not defined, each IDE has its own SKETCHBOOK_DIR (default)
# To share the same SKETCHBOOK_DIR along all IDEs, define
# 
#SKETCHBOOK_DIR =


# Libraries
# ----------------------------------
# Declare application Arduino/chipKIT/Wiring/Energia/Maple and users libraries used 
# Short-listing libraries speeds-up building
# Typing = 0 takes none
# Otherwise, leaving empty considers all (default)

# List Arduino/chipKIT/Wiring/Energia/Maple libraries here 
#
#APP_LIBS_LIST = Wire Wire/utility EEPROM Ethernet Ethernet/utility \
	SPI Firmata LiquidCrystal Matrix Sprite SD SD/utility Servo SoftwareSerial Stepper 

APP_LIBS_LIST = 0

# List users libraries here 
#
#USER_LIBS_LIST = ...

USER_LIBS_LIST = 0


MAKEFILE_PATH  = $(CURDIR)/Makefiles
UTILITIES_PATH = $(CURDIR)/Utilities

include $(MAKEFILE_PATH)/Step1.mk


CROSS_COMPILE = arm-linux-gnueabihf-
CC=$(CROSS_COMPILE)g++
LD :=$(CROSS_COMPILE)g++
LINK=$(CROSS_COMPILE)g++
TARGET = pi_marlin

_OBJ =  SdBaseFile.o  SdFatUtil.o  SdFile.o  SdVolume.o Sd2Card.o blinkm.o  cardreader.o  configuration_store.o  dac_mcp4728.o  digipot_mcp4018.o  digipot_mcp4451.o  emergency_parser.o  endstops.o  fwretract.o  G26_Mesh_Validation_Tool.o  hex_print_routines.o  I2CPositionEncoder.o  least_squares_fit.o  leds.o  LiquidCrystal.o  M100_Free_Mem_Chk.o ini_file.o  malyanlcd.o  Marlin_main.o  MarlinSerial.o  Max7219_Debug_LEDs.o  mesh_bed_leveling.o  neopixel.o  nozzle.o  parser.o  pca9632.o  planner_bezier.o  planner.o  power.o  power_loss_recovery.o  printcounter.o  runout.o   serial.o  servo.o  stepper.o  stepper_dac.o  stepper_indirection.o  stopwatch.o  temperature.o  tmc_util.o  twibus.o  U8glib.o  ubl.o  ubl_G29.o  ubl_motion.o  ultralcd.o  utility.o  vector_3.o  watchdog.o \
	/home/pi/src/utility/chessengine.o  /home/pi/src/utility/u8g_bitmap.o  /home/pi/src/utility/u8g_circle.o  /home/pi/src/utility/u8g_clip.o  /home/pi/src/utility/u8g_com_api_16gr.o  /home/pi/src/utility/u8g_com_api.o  /home/pi/src/utility/u8g_com_arduino_attiny85_hw_spi.o  /home/pi/src/utility/u8g_com_arduino_common.o  /home/pi/src/utility/u8g_com_arduino_fast_parallel.o  /home/pi/src/utility/u8g_com_arduino_hw_spi.o  /home/pi/src/utility/u8g_com_arduino_hw_usart_spi.o  /home/pi/src/utility/u8g_com_arduino_no_en_parallel.o  /home/pi/src/utility/u8g_com_arduino_parallel.o  /home/pi/src/utility/u8g_com_arduino_port_d_wr.o  /home/pi/src/utility/u8g_com_arduino_ssd_i2c.o  /home/pi/src/utility/u8g_com_arduino_st7920_custom.o  /home/pi/src/utility/u8g_com_arduino_st7920_hw_spi.o  /home/pi/src/utility/u8g_com_arduino_st7920_spi.o  /home/pi/src/utility/u8g_com_arduino_std_sw_spi.o  /home/pi/src/utility/u8g_com_arduino_sw_spi.o  /home/pi/src/utility/u8g_com_arduino_t6963.o  /home/pi/src/utility/u8g_com_arduino_uc_i2c.o  /home/pi/src/utility/u8g_com_atmega_hw_spi.o  /home/pi/src/utility/u8g_com_atmega_parallel.o  /home/pi/src/utility/u8g_com_atmega_st7920_hw_spi.o  /home/pi/src/utility/u8g_com_atmega_st7920_spi.o  /home/pi/src/utility/u8g_com_atmega_sw_spi.o  /home/pi/src/utility/u8g_com_i2c.o  /home/pi/src/utility/u8g_com_io.o  /home/pi/src/utility/u8g_com_msp430_hw_spi.o  /home/pi/src/utility/u8g_com_null.o  /home/pi/src/utility/u8g_com_raspberrypi_hw_spi.o  /home/pi/src/utility/u8g_com_raspberrypi_ssd_i2c.o  /home/pi/src/utility/u8g_com_std_sw_spi.o  /home/pi/src/utility/u8g_cursor.o  /home/pi/src/utility/u8g_delay.o  /home/pi/src/utility/u8g_dev_a2_micro_printer.o  /home/pi/src/utility/u8g_dev_flipdisc_2x7.o  /home/pi/src/utility/u8g_dev_gprof.o \
	/home/pi/src/utility/u8g_dev_ht1632.o  /home/pi/src/utility/u8g_dev_ili9325d_320x240.o  /home/pi/src/utility/u8g_dev_ks0108_128x64.o  /home/pi/src/utility/u8g_dev_lc7981_160x80.o  /home/pi/src/utility/u8g_dev_lc7981_240x128.o  /home/pi/src/utility/u8g_dev_lc7981_240x64.o  /home/pi/src/utility/u8g_dev_lc7981_320x64.o  /home/pi/src/utility/u8g_dev_ld7032_60x32.o  /home/pi/src/utility/u8g_dev_null.o  /home/pi/src/utility/u8g_dev_pcd8544_84x48.o  /home/pi/src/utility/u8g_dev_pcf8812_96x65.o  /home/pi/src/utility/u8g_dev_sbn1661_122x32.o  /home/pi/src/utility/u8g_dev_ssd1306_128x32.o  /home/pi/src/utility/u8g_dev_ssd1306_128x64.o  /home/pi/src/utility/u8g_dev_ssd1306_64x48.o  /home/pi/src/utility/u8g_dev_ssd1309_128x64.o  /home/pi/src/utility/u8g_dev_ssd1322_nhd31oled_bw.o  /home/pi/src/utility/u8g_dev_ssd1322_nhd31oled_gr.o  /home/pi/src/utility/u8g_dev_ssd1325_nhd27oled_bw.o  /home/pi/src/utility/u8g_dev_ssd1325_nhd27oled_bw_new.o  /home/pi/src/utility/u8g_dev_ssd1325_nhd27oled_gr.o  /home/pi/src/utility/u8g_dev_ssd1325_nhd27oled_gr_new.o  /home/pi/src/utility/u8g_dev_ssd1327_96x96_gr.o  /home/pi/src/utility/u8g_dev_ssd1351_128x128.o  /home/pi/src/utility/u8g_dev_ssd1353_160x128.o  /home/pi/src/utility/u8g_dev_st7565_64128n.o  /home/pi/src/utility/u8g_dev_st7565_dogm128.o  /home/pi/src/utility/u8g_dev_st7565_dogm132.o  /home/pi/src/utility/u8g_dev_st7565_lm6059.o  /home/pi/src/utility/u8g_dev_st7565_lm6063.o  /home/pi/src/utility/u8g_dev_st7565_nhd_c12832.o  /home/pi/src/utility/u8g_dev_st7565_nhd_c12864.o  /home/pi/src/utility/u8g_dev_st7687_c144mvgd.o  /home/pi/src/utility/u8g_dev_st7920_128x64.o  /home/pi/src/utility/u8g_dev_st7920_192x32.o  /home/pi/src/utility/u8g_dev_st7920_202x32.o  /home/pi/src/utility/u8g_dev_t6963_128x128.o  /home/pi/src/utility/u8g_dev_t6963_128x64.o  /home/pi/src/utility/u8g_dev_t6963_240x128.o  /home/pi/src/utility/u8g_dev_t6963_240x64.o  /home/pi/src/utility/u8g_dev_tls8204_84x48.o  /home/pi/src/utility/u8g_dev_uc1601_c128032.o  /home/pi/src/utility/u8g_dev_uc1608_240x128.o  /home/pi/src/utility/u8g_dev_uc1608_240x64.o  /home/pi/src/utility/u8g_dev_uc1610_dogxl160.o  /home/pi/src/utility/u8g_dev_uc1611_dogm240.o  /home/pi/src/utility/u8g_dev_uc1611_dogxl240.o  /home/pi/src/utility/u8g_dev_uc1701_dogs102.o  /home/pi/src/utility/u8g_dev_uc1701_mini12864.o  /home/pi/src/utility/u8g_ellipse.o  /home/pi/src/utility/u8g_font.o  /home/pi/src/utility/u8g_font_data.o   /home/pi/src/utility/u8g_line.o \
	/home/pi/src/utility/u8g_ll_api.o  /home/pi/src/utility/u8g_page.o  /home/pi/src/utility/u8g_pb14v1.o  /home/pi/src/utility/u8g_pb16h1.o  /home/pi/src/utility/u8g_pb16h2.o  /home/pi/src/utility/u8g_pb16v1.o  /home/pi/src/utility/u8g_pb16v2.o  /home/pi/src/utility/u8g_pb32h1.o  /home/pi/src/utility/u8g_pb8h1.o  /home/pi/src/utility/u8g_pb8h1f.o  /home/pi/src/utility/u8g_pb8h2.o  /home/pi/src/utility/u8g_pb8h8.o  /home/pi/src/utility/u8g_pb8v1.o  /home/pi/src/utility/u8g_pb8v2.o  /home/pi/src/utility/u8g_pb.o  /home/pi/src/utility/u8g_pbxh16.o  /home/pi/src/utility/u8g_pbxh24.o  /home/pi/src/utility/u8g_polygon.o  /home/pi/src/utility/u8g_rect.o  /home/pi/src/utility/u8g_rot.o  /home/pi/src/utility/u8g_scale.o  /home/pi/src/utility/u8g_state.o  /home/pi/src/utility/u8g_u16toa.o  /home/pi/src/utility/u8g_u8toa.o  /home/pi/src/utility/u8g_virtual_screen.o \
	TMC2208Stepper/source/TMC2208Stepper.o TMC2208Stepper/source/TMC2208Stepper_CHOPCONF.o TMC2208Stepper/source/TMC2208Stepper_DRVSTATUS.o TMC2208Stepper/source/TMC2208Stepper_GCONF.o  TMC2208Stepper/source/TMC2208Stepper_OTP_READ.o TMC2208Stepper/source/TMC2208Stepper_PWMCONF.o 
OBJ = $(patsubst %,%,$(_OBJ))
 
INC = -I./  -I./CMSIS -I/home/pi/src/utility -ITMC2208Stepper -I./CMSIS-W -Wall -g0
CFLAGS = -O0 -c     -std=c++11
LIBS = -lpi -lwiringPi -lpthread -L ./

_DEPS =  $(shell find /home/pi/src/CMSIS/*.h) $(shell find  *.h) $(shell find TMC2208Stepper/*.h) 
DEPS = $(patsubst %,%,$(_DEPS))

all: $(TARGET) 
%.o: %.cpp $(DEPS)	
	$(CC) $(INC) $(CFLAGS) -Wall -cpp $< -o $@  
	#$(CC) $(INC) $(CFLAGS) -Wall -cpp $^ -o $@  
	
$(TARGET): $(OBJ)
	$(LINK) -o $(TARGET) $(OBJ) ${LIBS} 
	



clean:
	find . -type f | xargs touch
	rm -f $(TARGET) $(shell find  *.o)

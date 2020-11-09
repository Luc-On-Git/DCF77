# DCF77
Build a clock with DS3231 and a DCF77 module arount STM32F103RB
An RTC DS3231 is used to keep date and hour in memory
A DCF77 module (got from a chinise product) is used to regularly check date and hour
In my case, i have first to experiment an better reception. The aim is to get a signal witch can be recognise as a correct date/hour
This is curruntly done with the achievement of an antenna.
If it operates, the code will have to work with interrupts.

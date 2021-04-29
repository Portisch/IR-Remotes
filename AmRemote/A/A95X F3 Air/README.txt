Changed from

#amlogic NEC remote
factory_code	= 0xdf000001 
work_mode	= 0
repeat_enable 	= 1
repeat_delay 	= 40
repeat_peroid 	= 39
release_delay	= 121
debug_enable 	= 1   

To below number values in remote.conf

#amlogic NEC remote
factory_code	= 0xdf000001 
work_mode  	= 0
repeat_enable 	= 1
repeat_delay 	= 130
repeat_peroid 	= 120
release_delay	= 20
debug_enable 	= 1 

The remote now has correct long press actions in Kodi Leia.

Long press continuous scrolling up and down.
Long press OK button for contextual / option

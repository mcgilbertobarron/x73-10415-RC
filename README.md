# x73-10415-RC
This site contains files to implement remote control between x73-10415 agent and manager.

1.- Download the lpcxpresso ide from this website http://www.lpcware.com/lpcxpresso/download

2.- Download booth .axf files to program the Agent and Manager.

3.- Using the command line flash programming tool, select the file.axf flash it to lpcxpresso 1769 board.

The commands for the command line are the followings:

crt_emu_cm_redlink -pLPC1769 -vendor=NXP -flash-load-exec "Agent.axf" crt_emu_cm_redlink -pLPC1769 -vendor=NXP -flash-load-exec "manager.axf"

for more information about this operation go to the following link. http://www.lpcware.com/content/faq/lpcxpresso/command-line-flash-programming

4.- WT12 UART Bluetooth Breakout Board,Two WT12 Bluetooth modules are necessary on both devices, these must be connected to corresponding UART ports.

5.- In the APDU file can be observed the apdus used for this implementation.

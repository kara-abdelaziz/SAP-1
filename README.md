# 8bits-Architecture

This is an implementation of an 8 bits Architecture directly inspired from Ben Eater architecture (link:https://www.youtube.com/user/eaterbc/playlists). The project is composed of several files .circ for digital logic simulation under the Logisim simulator
(link:http://www.cburch.com/logisim/) a Java based free open source and easy to learn and use logic simulator. There are 3 programs shown on Ben Eater videos to execute upon this architecture.

1). How to execute a program:

To execute a program you need first to load the program on RAM, then to launch the simulation. it is done by:

	1. Open the project under Logisim, the main circuit for the project is the file '8 bits architecture.circ', it will automatically load the other circuits.
	2. Open the RAM circuit by double clicking over 'RAM\Asynchronous RAM' file in the left panel of the simulator.
	3. When the RAM circuit is opened, right click on the RAM chip and choose load image sub-menu.
	4. You have to choose a binary image program file (files with .RAM extension).
	5. Then get back to the main project by double clicking on '8 bits architecture' on the right panel.
	6. To simulate the program you have 2 options; step by step execution or continued execution.
	7. Step by step execution is done by using the hand icon under the tools-bar to click the manual push button of the clock circuitry.
	8. For continued execution, you have to switch to automatic clock by using the hand to activate it on the clock circuitry, then to click on 'Show simulation hierarchy' button above the right panel, then 'Enable clock ticks' button nearby it.

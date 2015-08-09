PyBW lets AI agents written in Python play Starcraft Broodwar, by wrapping BWAPI.


## Features ##
  * Pythonic interface to all BWAPI and BWTA structures
  * An interactive (REPL) console
  * Supports latest version of BWAPI (Beta 3.4)

## Screenshot ##

An example working environment: The AI bot is playing the game, and everything is accessible and modifiable within the python console.

<img src='http://i.imgur.com/CZKSI.jpg'>

<h2>How to Compile and Run from the SVN</h2>
<ol><li>Get PyBW source code through the SVN<br>
</li><li>Make sure you have "BWAPI_Beta_3.4" (latest release at the moment of writing this) or later<br>
</li><li>Make sure you have Python (tested only with 2.6)<br>
</li><li>Put PyBW directory inside the BWAPI_Beta_3.4 directory<br>
</li><li>Open solution file in Visual Studio<br>
</li><li>Set build to "release"<br>
</li><li>Build solution<br>
</li><li>change bwapi-data\bwapi.ini to accept client connections (set ai_dll to NULL)<br>
</li><li>Run pybwClient.exe (or press Ctrl+F5 from Visual Studio)<br>
</li><li>Start a game and enjoy watching as exampleai.py sends your workers to collect money for daddy
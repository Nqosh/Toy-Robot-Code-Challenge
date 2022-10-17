<h3>Toy Robot Simulator</h3>
<img src = "https://github.com/jeff1978/Toy-Robot-Simulator/blob/master/robot.jpg" align = right>
This C# .NET solution is a simulator of a toy robot that moves on a tabletop. The development of this project is driven by unit tests. These are included in this repository.
<br><h4>Design Patterns Used</h4>
<b>Command :</b>
<br>A class is used to represent user input data, validate it and return appropriate object types or error messages. The class has no dependencies and it's methods are unit tested before being set to work with the rest of the application.
<h4>Instructions and Valid Commands</h4>
Follow the on screen instructions to place a robot and move it around the board. To exit the application at any time type EXIT (this must be in uppercase)
<br>PLACE X,Y,FACING : This puts the toy on the table in position X,Y and facing NORTH, SOUTH, EAST or WEST. If the toy is already placed, issuing another valid PLACE command will place the toy in the newly specified location.
<br>MOVE : This moves the toy one unit forward in the direction it is currently facing.
<br>LEFT : This rotates the toy 90 degrees to the left (i.e. counter-clockwise) without changing the position.
<br>RIGHT : This rotates toy 90 degrees to the right (i.e. clockwise) without changing the position.
<br>REPORT : This announces the X,Y and direction of the toy by printing to the console.



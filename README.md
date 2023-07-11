
<!-- Runnung the code -->

do npm install before running the code
then hit ng serve 



<!-- Explanation about the code -->

This code is a program that helps an airline assign seats to passengers on their planes. It works based on some rules for where to put people depending on how many seats they need.

Imagine you're on a plane with rows of seats. Each row has 8 seats, and there are 3 rows in total. The seats are divided into sections, like a b c in the first section, d e in the middle section, and f g h in the last section.

If someone wants 4 seats, the program will try to put them in the middle of the first row that has enough empty seats. If someone wants 3 seats, the program will look for a row with enough empty seats in the middle section. If it can't find enough seats there, it will check the next row. If someone wants 2 seats, the program will put them at the edges of a row, either on the left or right side. And if someone wants just 1 seat, the program will start from the edge of a row and give them the first empty seat they find.

The program keeps track of which seats are already taken and updates the list of allocated seats accordingly. If it can't find enough seats for the requested number, it will let you know.

There's also a part of the code that creates a user interface. It shows a screen where you can enter the number of seats you want and click a button to allocate them. The allocated seats will be shown on the screen in a table. If no seats are allocated, it will display a message saying so.

So, this code helps the airline allocate seats to passengers in a fair and organized way based on their needs and the available seats on the plane.





 ----------------------- Made By Pulkit Agarwal ------------------------------------

Welcome to the "Inventory Management System" project. 

The aim of this project was to create a system that connects both suppliers and spare parts of an inventory of some factory. 
It stores the suppliers who deal with this factory and also the spare parts they supply. Connections are established depending on the 
progress of the program. 

The program utilizes data structures, including linked lists, stacks, queues, and trees, to efficiently manage and organize inventory information.
It also uses OOP concepts to simulate real world object, suppliers and spare parts here in our case. 
The following lines state the data structures used along with their function:
1-Binary Trees: to store objects instantiated from both classes (supplier and spare parts).
2-Linked Lists: to represent connections between the supplier and their own spare parts.
3-Stacks: to store user interactions throughout the program, like a history.
4-Queues: to efficiently process and update spare part and supplier data.

To make the search time of the binary trees efficient, we had to make a function "generate_code" that is dedicated to creating IDs
for our objects. That's because nodes in binary trees inside our program are identified and searched for by their IDs.
Hence, we had to implement to function to balance the binary trees for optimizing the time efficiency. Time efficiency of binary trees in our program are best 
- always O(Log(N)) - thanks to this function. 

Finally, to make the user experience more easier and increase his interaction, we made a GUI for this program. 
You can find a screen recording while the GUI program was running in the repository.

To run the program, download the c++ files along with their header files. Run the main program and use it.
To run the GUI version, please make sure you first have this program installed: https://www.embarcadero.com/products/cbuilder. 
After installing it, run the file inside the debug folder. Everything will be stored inside txt files inside this folder.

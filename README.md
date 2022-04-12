Program - to be added


# KIWI entry task Documentation

written by **Júlia Križanová**  <br>
written in **Python** <br>
year **2021/2022**

## Classes used:
program is divided into 4 major classes:
* **`ParseInput()`** <br>
Class parsing input into suitable format and checking whether it is possible to continue with information given by user <br>

* **`FindAllFlights()`** <br>
Class traversing through graph while behaving as BFS algorithm, where vertices are represented by departure and arrival airports and edges are represented by price of the flight between two cities. <br>

* **`Main()`** <br>
Main class connection all parts of the program.

* **`OutputFormatting()`** <br>
Class ensuring correct output format of flight data. (meaning JSON compatible output)



## Input from user
During input, user can enter origin and destination airport and optionally number of bags and whether the flight is one way only or return flight. <br>

Example input and instructions for user are displayed right after the program is launched. For example it can look like this:
```
python -m solution data.csv BTW REJ --bags=1
```

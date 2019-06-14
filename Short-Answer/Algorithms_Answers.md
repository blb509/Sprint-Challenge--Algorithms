Add your answers to the Algorithms exercises here.

E1:

a. The runtime of this snippet grows by an order of O(n) because its runtime grows only based
on size of n

b. The runtime of this snippet grows by an order of O(n^4) because its runtime grows based
on size of n and the fact that there is a nested for loop four levels deep. And for each level the
power n is raised to increased by 1

c. The runtime of this snippet grows by an order of O(n) because its runtime grows only based
on size of n. If the recursion had two calls to itself in the return then it would be O(2^n)

E2:

def findMaxFloor(floors, checkBroke = checkbroke):
broke = True
maxFloor = None
currentFloor = floors // 2
while broke == true:
broke = checkbroke(currentFloor)
if broke == True:
currentFloor = currentFloor // 2
if broke == False:
maxFloor = currentFloor
currentFloor = plus 1/2th of this floor
while broke == True
broke = checkbroke(currentFloor)
if broke == False:
currentFloor = plus 1/2th of this floor
if broke == True:
currentFloor = minus 1/2th of this floor
if checkbroke(currentFloor) == False and checkbroke(currentFoor + 1) == True:
return maxFloor

return maxFloor

runtime = O(n^2)

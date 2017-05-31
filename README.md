# Else-Clauses

Else Clauses are basically the opposite of the whatever if statment you are trying to prove true. So if the if statement is false, then the else clause runs.
For example:
int x = 5;
if(x > 10){
  print(x);
}
else{
  x = 0;
}                   //outputs 0 because 5 > 10 is a false statement

if(x == 4){
  print(x);
}
else{
  x = 54;
}                   //outputs 54 because 5 == 4 is a false statement

if(x == 5){
   print(x);
}
else{
  x = 0;
}                   //outputs 5 because 5 == 5, and the else clause will not run

if(x >= 6){
  print(x);
}
else{
  x += 3;
}                   //outputs 8 because 5 >= 6 is false, and then the else clause runs and adds 3 to x

if(x != 5){
  x += 4;
}
else{
  x -= 2;
}                   //outputs 3 because skips over the if statement and subtracts 2 from 5 in else 

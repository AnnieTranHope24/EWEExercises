Ex13. 
The readloop reads the three input numbers. 
For each loop, count++ and the program
goes to end when count=capacity=3 (read 3 numbers). 
temp stores the temporary maximum
number. 
If temp>x then goto skip (read the next number without changing anything), 
else we store the new number in temp. 

Ex15.
isFirst determine whether or not the current character visited is the first character
of a word. 
If yes, isFirst=one. If no,isFirst=zero.
tmp stores the current charater visited. 
tmp = zero means end of file, then goto end.
If littlea>tmp or tmp>littlez (tmp is not a lower case), 
or if isFirst=one(tmp is not
the first character of a word), then skip, meaning no need to change anything.
Else, upper case the character and set isFirst=zero(the next char will not be the
first char of a word). 
Inside skip, if the tmp is a space then change isFirst to one, 
meaning the next char will be the first char of a word that needed 
to be uppercased.

Ex16.
Calculate the square of each integer from 0-x. If square >=x, goto end, else
continue to calculate the square of the next integer until square>=x.
Inside end, if square=x, goto substitute to print only temp. Else, print temp-1 and temp.

Ex17.
Inside loop, if temp>x, goto end to print the final factorial. Else, multiply set 
factorial=factorial*temp and increase temp by 1.

Things I learned about machine level programming by doing this assignment:
- Always need to assign memory location to every variable
- Have to create my own loop
- The program is read line by line



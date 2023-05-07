Download Link: https://assignmentchef.com/product/solved-political-riffraff-manager
<br>
In case you missed it we just had an election in the past year and America is very divided I have decided you will write a program to select our politicians that take office in a fair and just way. Last year all the slimy politicians, and all the political supporters on both sides of the aisle came out of the woodwork spouting their verbal abuse on each other. And even though the election is over the attacks and bitterness hasn’t ended. I don’t like campaigns so you are going to write a program so there is no need for elections. You are going to fix it. Every year ACM sponsors programming competitions at the local, regional and world levels. This assignment is adapted from a problem that appeared at one of these competitions………..very loosely adapted.

<strong>Purpose</strong>

The purpose of the assignment is to give you experience implementing a circular, doubly linked list and all the methods and management that is needed for such a list.

<strong>Problem Statement</strong>

In a serious attempt to downsize (reduce) the riffRaff in politics, The New Sloth Party with the motto “we promise to keep none of our promises.” has decided on the following strategy. Every day all Sloth applicants will be placed in a large circle, facing inwards. Someone is arbitrarily chosen as number 1, and the rest are numbered up to N (so N is the amount of candidates in the circle and N will be standing next to 1 as the end of the potential candidates). Now you will have two officials that will be the selectors, selector one holds a number we will call k, official two has a number we will call m. Selector k will start at candidate 1 (first candidate) and will move around the circle of candidates clockwise counting off candidates until it counts k candidates and then stop while he/she is pointing at the kth candidate. Selector m will start at candidate N (last candidate) and will move around the circle of candidates counter-clockwise counting off candidates until it gets to the mth candidate. Now one of two things will have taken place, the selectors will be pointing at two different candidates, or they will be pointing at the same candidate. If the selectors are pointing to two different candidates we will remove the candidates from the circle of candidates (these candidates will be ELIMINATED), starting with k candidate first and then the m candidate. The k selector will need to move clockwise up to the next available candidate and prepare to start counting again. The m selector will do the same but it will always move counter-clockwise. After removal the two selectors will need to be ready to start counting again at the next available candidate. If both selectors stop and they are pointing to the same candidate we have found ourselves a worthy candidate that will be put into political office…….keep this candidate off to the side, but remove the candidate from the circle of candidates…….which means k selector will need to be moved clockwise to next available and m selector will need to be moved counterclockwise to the next available candidate. Each selector then starts counting again at the next available person and the process continues until no-one is left. Note that the two victims (sorry, trainees) leave the ring simultaneously, so it is possible for one official to count a person already selected by the other official.

<strong>Input File Format</strong>

Write a program that asks the user for the name of a valid input file. If the file exists, the program should read in (in that order) the three numbers (N, k and m; k, m &gt; 0, 0 &lt; N &lt; 100) and determine the order in which the applicants are sent off for political retraining. Each set of three numbers will be on a separate line and the end of data will be signaled by three zeroes (0 0 0). Here is a sample input file:

10 4 3

17 6 4

0 0 0

<strong>Output Requirements</strong>

The output should be sent to a file named LinkedListProgram.txt. For each input, the output should show the order in which the people are chosen. For each round in which two different people are chosen, list the person chosen by the counter-clockwise official first. Here is the required output for the an input file:

Program 4

———

N = 10, k = 4, m = 3

Output

——

4 8

9 5

3 1

2 6

10

7

End of Program 4
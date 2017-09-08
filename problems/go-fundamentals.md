# Problems - Go
A few problems from around the internet to learn the fundamentals of [the Go programming language](https://golang.org/).

## 1. Kon'nichiwa, Sekai!

Source: https://tour.golang.org/welcome/1

Write a program that prints "Hello, world!" in Japanese (using Japanese characters) to the screen.


## 2. Current time

Source: https://tour.golang.org/welcome/4

Write a program that prints the current time and date to the screen.


## 3. FizzBuzz

Source: http://wiki.c2.com/?FizzBuzzTest

Write a program that prints the numbers from 1 to 100, except for the following conditions.
For multiples of three print "Fizz" instead of the number, and for the multiples of five print "Buzz".
For numbers which are multiples of both three and five print "FizzBuzz".


## 4. Multiples of 3 and 5

Source: https://projecteuler.net/problem=1

If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9.
The sum of these multiples is 23.
Find the sum of all the multiples of 3 or 5 below 1000.


## 5. Factorial digit sum

Write a function that calculates the sum of the digits of the factorial of a nubmer.
n! means n x (n − 1)  ... x 3 x 2 x 1.
For example, 10! = 10 x 9 x ... x 3 x 2 x 1 = 3628800, and the sum of the digits in the number 10! is 3 + 6 + 2 + 8 + 8 + 0 + 0 = 27.
Find the sum of the digits in the number 100!



## 6. Smallest multiple

Source: https://projecteuler.net/problem=5

2520 is the smallest number that can be divided by each of the numbers from 1 to 10 without any remainder.
What is the smallest positive number that is evenly divisible by all of the numbers from 1 to 20?


## 7. Guessing game

Source: https://adriann.github.io/programming_problems.html

Write a guessing game where the user has to guess a secret number. After every guess the program tells the user whether their number was too large or too small. At the end the number of tries needed should be printed. I counts only as one try if they input the same number multiple times consecutively.

## 8. Largest and smallest in list

Source: https://adriann.github.io/programming_problems.html

Write a function that returns the largest and smallest elements in a list.


## 9. Large sum

Source: https://projecteuler.net/problem=13

Work out the first ten digits of the sum of the following one-hundred 50-digit numbers.
- 7107287533902102798797998220837590246510135740250
- 46376937677490009712648124896970078050417018260538
- 74324986199524741059474233309513058123726617309629
- 91942213363574161572522430563301811072406154908250
- 23067588207539346171171980310421047513778063246676
- 89261670696623633820136378418383684178734361726757
- 28112879812849979408065481931592621691275889832738
- 44274228917432520321923589422876796487670272189318
- 47451445736001306439091167216856844588711603153276
- 70386486105843025439939619828917593665686757934951
- 62176457141856560629502157223196586755079324193331
- 64906352462741904929101432445813822663347944758178
- 92575867718337217661963751590579239728245598838407
- 58203565325359399008402633568948830189458628227828
- 80181199384826282014278194139940567587151170094390
- 35398664372827112653829987240784473053190104293586
- 86515506006295864861532075273371959191420517255829
- 71693888707715466499115593487603532921714970056938
- 54370070576826684624621495650076471787294438377604
- 53282654108756828443191190634694037855217779295145
- 36123272525000296071075082563815656710885258350721
- 45876576172410976447339110607218265236877223636045
- 17423706905851860660448207621209813287860733969412
- 81142660418086830619328460811191061556940512689692
- 51934325451728388641918047049293215058642563049483
- 62467221648435076201727918039944693004732956340691
- 15732444386908125794514089057706229429197107928209
- 55037687525678773091862540744969844508330393682126
- 18336384825330154686196124348767681297534375946515
- 80386287592878490201521685554828717201219257766954
- 78182833757993103614740356856449095527097864797581
- 16726320100436897842553539920931837441497806860984
- 48403098129077791799088218795327364475675590848030
- 87086987551392711854517078544161852424320693150332
- 59959406895756536782107074926966537676326235447210
- 69793950679652694742597709739166693763042633987085
- 41052684708299085211399427365734116182760315001271
- 65378607361501080857009149939512557028198746004375
- 35829035317434717326932123578154982629742552737307
- 94953759765105305946966067683156574377167401875275
- 88902802571733229619176668713819931811048770190271
- 25267680276078003013678680992525463401061632866526
- 36270218540497705585629946580636237993140746255962
- 24074486908231174977792365466257246923322810917141
- 91430288197103288597806669760892938638285025333403
- 34413065578016127815921815005561868836468420090470
- 23053081172816430487623791969842487255036638784583
- 11487696932154902810424020138335124462181441773470
- 63783299490636259666498587618221225225512486764533
- 67720186971698544312419572409913959008952310058822
- 95548255300263520781532296796249481641953868218774
- 76085327132285723110424803456124867697064507995236
- 37774242535411291684276865538926205024910326572967
- 23701913275725675285653248258265463092207058596522
- 29798860272258331913126375147341994889534765745501
- 18495701454879288984856827726077713721403798879715
- 38298203783031473527721580348144513491373226651381
- 34829543829199918180278916522431027392251122869539
- 40957953066405232632538044100059654939159879593635
- 29746152185502371307642255121183693803580388584903
- 41698116222072977186158236678424689157993532961922
- 62467957194401269043877107275048102390895523597457
- 23189706772547915061505504953922979530901129967519
- 86188088225875314529584099251203829009407770775672
- 11306739708304724483816533873502340845647058077308
- 82959174767140363198008187129011875491310547126581
- 97623331044818386269515456334926366572897563400500
- 42846280183517070527831839425882145521227251250327
- 55121603546981200581762165212827652751691296897789
- 32238195734329339946437501907836945765883352399886
- 75506164965184775180738168837861091527357929701337
- 62177842752192623401942399639168044983993173312731
- 32924185707147349566916674687634660915035914677504
- 99518671430235219628894890102423325116913619626622
- 73267460800591547471830798392868535206946944540724
- 76841822524674417161514036427982273348055556214818
- 97142617910342598647204516893989422179826088076852
- 87783646182799346313767754307809363333018982642090
- 10848802521674670883215120185883543223812876952786
- 71329612474782464538636993009049310363619763878039
- 62184073572399794223406235393808339651327408011116
- 66627891981488087797941876876144230030984490851411
- 60661826293682836764744779239180335110989069790714
- 85786944089552990653640447425576083659976645795096
- 66024396409905389607120198219976047599490197230297
- 64913982680032973156037120041377903785566085089252
- 16730939319872750275468906903707539413042652315011
- 94809377245048795150954100921645863754710598436791
- 78639167021187492431995700641917969777599028300699
- 15368713711936614952811305876380278410754449733078
- 40789923115535562561142322423255033685442488917353
- 44889911501440648020369068063960672322193204149535
- 41503128880339536053299340368006977710650566631954
- 81234880673210146739058568557934581403627822703280
- 82616570773948327592232845941706525094512325230608
- 22918802058777319719839450180888072429661980811197
- 77158542502016545090413245809786882778948721859617
- 72107838435069186155435662884062257473692284509516
- 20849603980134001723930671666823555245252804609722
- 53503534226472524250874054075591789781264330331690

## 10. Palindrome test

Source: https://adriann.github.io/programming_problems.html

Write a function that tests whether a string is a palindrome.

## 11. Merge list and sort

Source: https://adriann.github.io/programming_problems.html

Write a function that merges two sorted lists into a new sorted list. [1,4,6],[2,3,5] → [1,2,3,4,5,6].

## 12. Decimal to binary

Source: http://www.w3resource.com/java-exercises/basic/index.php

Write a Java program to convert a user inputted decimal number to a binary number printed on screen.


## 13. Newton's method for square roots

Source: https://tour.golang.org/flowcontrol/8

Implement the square root function using Newton's method.
In this case, Newton's method is to approximate Sqrt(x) by picking a starting point z and then repeating:

![z_(n+1) = z_n - ((z_n^2 - x)/(2z_n))](https://tour.golang.org/content/img/newton.png)

To begin with, just repeat that calculation 10 times and see how close you get to the answer for various values (1, 2, 3, ...).
Next, change the loop condition to stop once the value has stopped changing (or only changes by a very small delta).
How close are you to the math.Sqrt?
Hint: to declare and initialize a floating point value, give it floating point syntax or use a conversion:
z := float64(1)
z := 1.0

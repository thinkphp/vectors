# Arhiva de probleme:

## #1
Coordonatele a N puncte in planul cartezian sunt
memorate in doi vectori:
Abs - vectorul absciselor
Ord - vectorul ordonatelor
Output: Sa se determine in plan segmentul de lungime maxima.
De precizat ca se cere o singura solutie, daca sunt mai multe
segmente de lungime maxima.
 
Example:
Introduceti numarul de puncte -> 3

Introduceti coordonatele punctelor ->

Abscisa punctului 0 -> 1

Ordonata punctului 0 -> 3

Abscisa punctului 1 -> -1

Ordonata punctului 1 -> 1

Abscisa punctului 2 -> 2

Ordonata punctului 2 -> -4

Output -> 
Max Segment -> 7.07107

Points -> (1,3) - ( 2, -4)

## #2
Se citeste un vector V cu N elemente intregi si un numar natural p. Sa se elimine elementul de pe pozitia p din vectorul V
mutand elementele de pe pozitiile p+1,p+2,... cu o pozitie spre stanga. Sa se afiseze vectorul astfel obtinut.
Exemple:
n = 6, V = [10,20,30,40,50]
p = 3
Intrucat primul element al vectorului este retinut in V[0], elementul de pe pozitia p este 40. 
Output -> Nou Vector va fi: V = [10,20,30,50]

## #3
Se citeste un vector V cu N Elemente intregi si un numar natural p. Sa se introduca elementul cu valoarea 100 pe pozitia p, in vectorul V,
mutand elementele de pe pozitiile p,p+1,p+2,cu o pozitie spre dreapta. Sa se afiseze vectorul astfel obtinut.

Exemple:

N = 6, V = [10,20,30,40,50]
p = 3
Output -> 
Intrucat primul element al vectorului este retinut de V[0], noul vector va fi:
V = [10,20,30,100,40,50]

## #4
Sa se introduca intr-un vector V cu N elemente intregi, dupa fiecare element par, un element cu valoarea 0.
N = 5, V = [2,3,4,7,8]
Output -> V = [2,0,3,4,0,7,8,0]

## #5
Sa se elimine dintr-un vector V cu N elemente intregi toate elementele pare , stiind ca vectorul are cel putin un element impar.

Input -> N = 6, V = [1,2,3,4,5,6,7]
Output -> V = [1,3,5,7]

## #6
Se citeste un vector V cu N elemente intregi. Sa se mute primul element la sfarsitul vectorului.

Input -> N = 4, V = [10,20,30,40]
Output -> V = [20,30,40,10]

## #7
Se citeste un vector V cu N elemente intregi. Sa se mute ultimul element la inceputul vectorului.

Input -> N = 4, V = [10,20,30,40]
Output -> V = [40,10,20,30]

## #8

Se citesc n numere naturale nenule. Sa se determine in cate zerouri se termina produsul
lor fara a efectua operatia de inmultire.

Exemple:

Input -> n = 5; V = [4,50,48,72,25]
Output -> se termina in 4 zerouri.

## #9
Se citeste un numar natural n. Sa se verifice daca numarul n are acelasi numar de cifre de acelasi tip.

Exemple:
input -> n = 213213 

Output -> are cate doua cifre de 1, doua cifre de 2 si 2 cifre de 3 YES

input -> n = 1232

Output -> are doua cifre de 2, o cifra de 1 si o cifra de 3, nu indeplineste conditia din cerinta, NO

## #10
Sa se verifice daca un vector este ordonat crescator sau descrescator

Input -> n = 5, V = [1,2,2,4,5] 

Output -> YES, Ordonat crescator.

Input -> n = 5, V = [5,4,3,2,1] 

Output -> YES, Ordonat descrescator.

Input -> n = 5, V = [1,2,-1,4,5] 

Output -> No, neordonat.

## #11
Sa se verifice daca un vector este de tip depresiune, adica daca de la prima pozitie pana la o pozitie p oarecare este ordonat strict descrescator, iar
de la pozitia p + 1 pana la sfarsitul vectorului este ordonat strict crescator

Input -> n = 5, V = [3,2,1,2,3] -> Depresiune

Input -> n = 5, V = [3,2,2,1,3] -> Nu e depresiune!

## #12
Sa se verifice daca un vector este de tip munte, adica daca de la prima pozitie pana la o pozitie p oarecare este ordonat strict crescator, iar
de la pozitia p + 1 pana la sfarsitul vectorului este ordonat strict descrescator.

Input -> n = 5, V = [1,2,3,2,1] -> mountain.

Input -> n = 5, V = [1,2,3,4,5] -> not mountain.

## #13
Se citeste un vector cu n elemente numere intregi, n <= 10. Sa se formeze numarul minim folosind cifra minima a fiecarui numar din vectorul initial.

Input -> n = 6, V = [123, 400, 503, 284, 99, 567]

Output -> cifrele minime sunt: [1,0,0,2,9,5] -> 100259

## 14.
Sa se verifice daca componentele unui vector cu n elemente intregi n apartine lui N*, reprezinta o progresie aritmetica. Un sir a1, a2, a3,..., an este progresie
aritmentica daca oricare ar fi k apartine lui {1,2,3, ..., n - 1} avem ak+1 = nk + r, unde r se numeste ratia progresiei si este un numar constant.

Input -> n = 6, V = [2,4,6,8,10,12] este progresie aritmetica cu ratia r = 2

Input -> n = 6, V = [1,3,6,8,11,13] nu este progresie aritmetica

## 15.

Se considera un tablou unidimensional ce contine n caractere distincte. Sa se afiseze permutarea circulara a lui, care incepe cu cel mai mic caracter in sens lexicografic.

    input   -> n = 5, v = ['c','d','a','m','z']

    Output  -> v = ['a', 'm', 'z', 'c', 'd']

## 16. https://ideone.com/SgWDrV

Fie un tablou unidimensional care contine n valori intregi distincte. Realizati un program care ordoneaza crescator elementele vectorului folosind "algoritmul de numarare".

Hint:  Consideram vector A. Algoritmul de sortare prin numarare consta in gasirea pentru fiecare element A(i), a numarului de elemente din vector mai mici ca el. Numerele obtinute sunt memorate in alt vector. Elementele vectorului A vor fi initial salvate in vectorul auxiliar C. La finalul algoritmului se vor
rescrie in ordine crescatoare elementele vectorului A pe baza valorilor memorate in B si C.

## 17. https://ideone.com/mFSwm3

Turnuri in zig-zag. Un copil are n turnuri de inaltimi diferite (numere naturale). El vrea sa construiasca un zid cu toate turnurile asezandu-le unul langa altul astfel incat turnurile ce ocupa pozitii pare in zid sa fie mai inalte decat turnurile vecine. Descoperiti un algoritm cu ajutorul caruia copilul sa poata construi sirul.

          n = 7

          Input-> 1 7 2 6 4 3 5
          
          Output-> 1 5 2 6 3 7 4
          
## 18. https://ideone.com/zXuCwI

Se citesc doua siruri de numere intregi, fiecare sir citindu-se pana la
intalnirea numarului 0 (numarul zero nu face parte din sir). Sa se verifice
daca cele doua siruri formeaza doua multimi de numere direct proportionale sau
invers proportionale.
Hint:
Elementele celor doua siruri le memoram in doi vectori notati cu A si B.
Daca cei doi vectori au numar diferit de elemente atunci nu se poate
vorbi despre proportionalitate. Trebuie sa formam perechi cu Elementele
celor doi vectori (o pereche fiind formata dintr-un element al vectorului A si
un element al vectorului B) astfel incat rapoartele (in cazul proportionalitatii
directe) si produsele (in cazul proportionalitatii inverse) perechilor sa fie egale.
Pentru aceasta ordonam elementele celor doi vectori in ordine crescatoare. In
cazul proportionalitatii directe o pereche este formata din elementele situate
pe aceeasi pozitie in cei doi vectori. In cazul proportionalitatii inverse se grupeaza
primul element din vectorul A cu ultimul element din vectorul B, al doilea element
din vectorul A cu penultimul element din vectorul B, etc...

Examples:

a) Input -> sir1 = 2, 3, 5, 0 sir2 = 3 5 0 

   Output -> Nu se poate vorbi despre proportionalitate pentru ca sirurile au numar diferit de elemente.

b) Input -> sir1 = 2 3 6 0 si sir2 = 9 6 18 0 

   Output -> multimile sunt direct proportionale

c) Input -> sir1 = 2 5 4 0 si sir2 = 4 10 5 0

   Output-> multimile sunt invers proportionale.
   

## 19. https://ideone.com/6Bl5DT

Se dă un vector cu n elemente, numere naturale. Afișați în ordine descrescătoare valorile din vector care sunt prime cu ultimul element al vectorului.
  
  Input: 
  Programul citește de la tastatură numărul n, iar apoi n numere naturale, reprezentând elementele vectorului
  Output:
  Programul va afișa pe ecran valorile cerute, în ordine descrescătoare, separate prin exact un spațiu.
  
  Restrictii si precizari:
    
   - 1 <= n <= 1000
   
   - cele n numere citite vor fi mai mici decât 1.000.000.000
   
Example:


Input:
     8
     
     16 7 63  1 5 9 14 
     
Output:
     9 5 3 1

## 20. https://ideone.com/BVtXpi

Deoarece se apropie Craciunul cu pasi repezi, Petrica vrea sa fie mai bun.
Lui ii plac problemele cu limita de timp mare asa ca el vrea sa gaseasca cel
mai mic numar format doar cu cifrele 2, 3, 5 si 7 care da restul N la impartirea
cu P.

Input:
Fişierul de intrare cifre4.in contine pe prima linie un numar natural T
ce semnifica numarul de teste. Pe urmatoarele T linii se afla cate doua
numere naturale N si P, cu semnificatia din enunt.

Output:
În fişierul de ieşire cifre4.out se vor afla T linii, pe linia i se va
afla raspunsul pentru al i-lea test, sau -1 in cazul in care nu exista solutie.

Restrictii:

T = 5

1 ≤ P ≤ 5 * 106

1 ≤ N ≤ P - 1

Example:

Input:

     3

     52 100

     11 100

     51 1123

Output:

    52

    -1

    322352
    
## #21. https://ideone.com/th0Lso

At school, invatatoarea unei clase aseaza cei n students din clasa
in urmatoarea ordine: c1, c2, c3, ..., cn unde ci reprezinta inaltimea
studentului care ocupa pozitia i in sir. Invatatoarea considera ca elevii
sunt bine asezati in sir daca fiecare elev vede, privind de-a lungul sirului, cel putin
unul dintre elevii aflati la extremitatile sirului. Acest lucru este posibil
daca intre acest elev si cel aflat la un capat nu exista un alt elev cu o inaltime
mai mare sau egala cu a lui. Se cere sa se conceapa un program care sa verifice
daca elevii sunt bine asezati in sirul format de invatatoare, afisand mesajul
corect in acest caz, sau mesajul incorect in caz contrar.
exemplu:

n = 6

V = [1.2, 1.4, 1.5, 1.6, 1.3, 1.1] 

este un sir bine format intrucat elevii
din pozitiile 1,2,3 vad extremitatea stanga a sirului, al patruleaa vede
ambele extremitati. Elevii din pozitiile 5 si 6 vad extremitatea din dreapta a sirului.


## #22. https://ideone.com/tKWb8F

Given an array of integers and a value, determine is there are two integers in the array whose sum is equal to the given value. 
Return True is the sum exists and return False if it does not.

Input: 5 7 1 2 8 4 3 and the value = 10
Output: True

## #23. https://ideone.com/RXqyGL (c) https://ideone.com/eT5QcR (py)

Fiind dat vectorul x cu n elemente intregi nenule, sa se afiseze elementele distincte (elementele care se repeta sunt afisate o singura data la prima lor aparitie) in ordinea in care intervin in vector.

## #24. https://ideone.com/KVA9ML (py)

Fiind dat vectorul x cu n elemente intregi, sa se afiseze in ordinea crescatoarea a elementelor componente distincte si frecventa lor de aparitie.
Input: n = 6 , x = 45, -90, 45, 2, 45, 2
Output: 
Elementul -90 apare o data
Elementul 2 apare de 2 ori
Elementul 45 apare de 3 ori
      

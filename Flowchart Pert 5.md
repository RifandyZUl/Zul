```mermaid
flowchart TD;

A(Start)-->B[input variable Int a yg bernilai 20];
B-->B1[input variable Int b yg bernilai 10];
B1-->C[cetak contoh if else statement];
C-->D{Jika a > b};
D-->Ya
D-->Tidak
Ya-->E[Print a lebih besar dari b]
Tidak-->F[Print b lebih besar dari a]
E-->G(Finish)
F-->G(Finish)

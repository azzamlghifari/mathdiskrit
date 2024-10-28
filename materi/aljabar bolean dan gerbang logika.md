---
title: aljabar bolean dan gerbang logika

---

ALJABAR DAN GERBANG LOGIKA  
Operator Biner:
#include <iostream>
using namespace std;

int main() {
    int a = 5;  // biner: 0101
    int b = 9;  // biner: 1001

    cout << "a & b = " << (a & b) << endl;  // AND
    cout << "a | b = " << (a | b) << endl;  // OR
    cout << "a ^ b = " << (a ^ b) << endl;  // XOR
    cout << "~a = " << (~a) << endl;        // NOT
    cout << "a << 1 = " << (a << 1) << endl;  // Shift Kiri
    cout << "a >> 1 = " << (a >> 1) << endl;  // Shift Kanan

    return 0;
    operator uner:
    Increment (++): Menambah nilai operand sebanyak 1.

cpp

int a = 5;
a++;  // a sekarang bernilai 6

 Decrement (--): Mengurangi nilai operand sebanyak 1.
    
int b = 10;
b--;  // b sekarang bernilai 9

 Unary Plus (+): Menandai operand dengan tanda plus, biasanya tidak mengubah nilai operand.
    
int c = +7;  // c tetap 7

Unary Minus (-): Mengubah tanda operand. 
    
int d = -c;  // d sekarang bernilai -7

Logical NOT (!): Mengubah nilai boolean operand (true menjadi false, dan sebaliknya).
    
int f = 5;  // biner: 0101
int g = ~f;  // g sekarang bernilai -6 (biner: 1010)

Operator uner ini sering digunakan dalam berbagai jenis pemrograman untuk manipulasi nilai dan logika. Gimana, perlu penjelasan lebih detail tentang salah satu dari mereka?
    
} 
    Memahami hubungan antara logika Boolean dan sirkuit komputer digital.
Belajar cara merancang sirkuit logika sederhana.
Memahami bagaimana sirkuit digital bekerja bersama-sama untuk membentuk sistem komputer yang kompleks.
    
Aksioma-Aksioma:
Untuk setiap a, b, c ∈ B, berlaku aksioma-aksioma berikut:
Closure: a + b ∈ B dan a ⋅ b ∈ B.
Identitas: a + 0 = a dan a ⋅ 1 = a.
Komutatif: a + b = b + a dan a ⋅ b = b ⋅ a.
Distributif: a ⋅ (b + c) = (a ⋅ b) + (a ⋅ c) dan a + (b ⋅ c) = (a + b) ⋅ (a + c).
Komplemen: Untuk setiap a ∈ B, terdapat elemen unik a’ ∈ B sehingga a + a’ = 1 dan a ⋅ a’ = 0


### **2️⃣ Count the Number of Comments, Keywords, Identifiers, Words, Lines, and Spaces from Input File**
```bash
flex CC_Lab2.l
cc lex.yy.c -ll
./a.out
```
### **3️⃣ Count Number of Words Starting with 'A'**
```bash
flex CC_Lab3.l
cc lex.yy.c -ll
./a.out
```
### **4️⃣ Conversion of Lowercase to Uppercase and Vice Versa**
```bash
flex CC_Lab4.l
cc lex.yy.c -ll
./a.out
```
### **5️⃣ Conversion of Decimal to Hexadecimal Number in a File**
```bash
flex CC_Lab5.l
cc lex.yy.c -ll
./a.out
```
### **6️⃣ Test Lines Ending with “com”**
```bash
flex CC_Lab6.l
cc lex.yy.c -ll
./a.out
```
### **7️⃣ Postfix Expression Evaluation**
```bash
yacc -d CC_Lab7.y
flex CC_Lab7.l
cc lex.yy.c y.tab.c -lfl
./a.out
```
### **8️⃣ Desk Calculator with Error Recovery**
```bash
yacc -d CC_Lab8.y
flex CC_Lab8.l
cc lex.yy.c y.tab.c -lfl
./a.out
```
### **9️⃣ Parser for “FOR” Loop Statements**
```bash
yacc -d CC_Lab9.y
flex CC_Lab9.l
cc lex.yy.c y.tab.c -lfl
./a.out
```
### **🔟 Intermediate Code (IC) Generator for Arithmetic Expression**
```bash
yacc -d CC_Lab10.y
flex CC_Lab10.l
cc lex.yy.c y.tab.c -lfl
./a.out
```

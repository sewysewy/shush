# ceasar cipher
```
#include <stdio.h>
#include <string.h>
#include <ctype.h>
#include<stdlib.h>
void encrypt(char msg[], int k)
{
 char res[100] ;
 for(int i=0; i<strlen(msg); i++)
 {
 if(isupper(msg[i]))
 {
 res[i] = (char)(((int)msg[i] - 65 + k) % 26 + 65);
 }
 else
 {
 res[i] = (char)(((int)msg[i] - 97 + k) % 26 + 97);
 }
 }
 printf("%s", res);
}
void decrypt(char msg[], int k)
{
 char res[100];
 for(int i=0; i<strlen(msg); i++)
 {
 if(isupper(msg[i]))
 {
 res[i] = (char)(((int)msg[i] - 65 - k + 26) % 26 + 65);
 }
 else
 {
 res[i] = (char)(((int)msg[i] - 97 - k + 26) % 26 + 97);
 }
 }
 printf("%s", res);
}
int main()
{
 int ascii;
 int k;
 char msg[100];
 int op;
while(1){
 printf("\n1. Encryption\n2. Decryption\n3. Exit");
 printf("\nEnter your Option: ");
 scanf("%d", &op);
if (op==3){
exit(1);}
 printf("Enter the msg/cypher : ");
 scanf("%s", msg);
 printf("Enter the Key : ");
 scanf("%d", &k);
 switch(op){
 case 1:
 {
 encrypt(msg,k);
 break;
 }
 case 2:
 {
 decrypt(msg,k);
 break;
 }

 default:
 printf("Enter a valid option");
 }
 }
 return 0;
}
```
# play fair
```
```
# rail fence
```
#include<stdio.h>
#include<string.h>
void encrypt(char msg[], int key){
int msgLen = strlen(msg), i, j, k = -1, row = 0, col = 0;
char railMatrix[key][msgLen];
for(i = 0; i < key; ++i)
 for(j = 0; j < msgLen; ++j)
 railMatrix[i][j] = '\n';
for(i = 0; i < msgLen; ++i){
 railMatrix[row][col++] = msg[i];
 if(row == 0 || row == key-1)
 k= k * (-1);
 row = row + k;
}
printf("\nEncrypted Message: ");
for(i = 0; i < key; ++i)
 for(j = 0; j < msgLen; ++j)
 if(railMatrix[i][j] != '\n')
 printf("%c", railMatrix[i][j]);
}
void decrypt(char msg[], int key){
int msgLen = strlen(msg), i, j, k = -1, row = 0, col = 0, m = 0;
char railMatrix[key][msgLen];
for(i = 0; i < key; ++i)
 for(j = 0; j < msgLen; ++j)
 railMatrix[i][j] = '\n';
for(i = 0; i < msgLen; ++i){
 railMatrix[row][col++] = '*';
 if(row == 0 || row == key-1)
 k= k * (-1);
 row = row + k;
}
for(i = 0; i < key; ++i)
 for(j = 0; j < msgLen; ++j)
 if(railMatrix[i][j] == '*')
 railMatrix[i][j] = msg[m++];
row = col = 0;
k = -1;
printf("\nDecrypted Message: ");
for(i = 0; i < msgLen; ++i){
 printf("%c", railMatrix[row][col++]);
 if(row == 0 || row == key-1)
 k= k * (-1);
 row = row + k;
}
}
int main()
{
int ascii;
int key;
char msg[100];
int op;
 printf("1. Encryption\n2. Decryption\n 3.Exit");
 printf("\nEnter your Option: ");
 scanf("%d", &op);
 printf("Enter the msg/cypher : ");
 scanf("%s", msg);
 printf("Enter the Key : ");
 scanf("%d", &key);
 if(op == 1)
 encrypt(msg, key);
 else if(op == 2)
 decrypt(msg, key);
 else if(op == 3)
 printf("Thankyou... Exiting ");
 else
 printf("Enter a valid option");

 printf("\n");
return 0;
}
```

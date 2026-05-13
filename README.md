
# EX-8-ADVANCED-ENCRYPTION-STANDARD ALGORITHM

# PROGRAM:
```
#include <stdio.h>
#include <string.h>
void xorCrypt(char *in, char *key) {
for (int i = 0; in[i]; i++) in[i] ^= key[i % strlen(key)];
}
int main() {
char msg[] = "PRATHIKSHA", key[] = "secretkey";
printf("Original: %s\n", msg);
xorCrypt(msg, key);
printf("Encrypted: %s\n", msg);
xorCrypt(msg, key);
printf("Decrypted: %s\n", msg);
return 0;
}
```
# OUTPUT:
<img width="1166" height="360" alt="image" src="https://github.com/user-attachments/assets/31c51506-0cb7-4961-b4cb-4f14663aeb66" />


# RESULT:

THE CODE IS EXCUTED SUCCESSFULLY 

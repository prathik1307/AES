
# EX-8-ADVANCED-ENCRYPTION-STANDARD ALGORITHM

# PROGRAM:
#include <stdio.h>
#include <string.h>
void xorCrypt(char *in, char *key) {
for (int i = 0; in[i]; i++) in[i] ^= key[i % strlen(key)];
}
int main() {
char msg[] = "CRYPTOGRAPHY", key[] = "secretkey";
printf("Original: %s\n", msg);
xorCrypt(msg, key);
printf("Encrypted: %s\n", msg);
xorCrypt(msg, key);
printf("Decrypted: %s\n", msg);
return 0;
}
# OUTPUT:

<img width="1551" height="683" alt="image" src="https://github.com/user-attachments/assets/c44806ca-4bb3-4278-b72f-507fa73ccfc0" />

# RESULT:

THE CODE IS EXCUTED SUCCESSFULLY 

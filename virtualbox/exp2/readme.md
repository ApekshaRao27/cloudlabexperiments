## Experiment 2: Network Setup and Running C Program in Ubuntu

### Steps
1. Go to VM Settings -> Network and make sure Network Adapter 1 is enabled.
2. Start the VM and open terminal (Ctrl + Alt + T).
3. Update package list:
sudo apt update
4. Install GCC compiler:
sudo apt install build-essential
5. Check compiler version:
gcc --version
6. Create and open file:
nano hello.c
7. Write the code:
#include <stdio.h>
int main() {
    printf("Hello");
    return 0;
}
8. Save and exit (Ctrl + O, Enter, Ctrl + X).
9. Compile the program:
gcc hello.c -o hello
10. Run the program:
./hello
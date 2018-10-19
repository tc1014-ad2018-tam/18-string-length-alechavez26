# 18-string-length-alechavez26
18-string-length-alechavez26 created by GitHub Classroom
 *
 *Alejandra Chavez Cruz
 * A01411970@itesm.mx
 * 18/Oct/18
 */

#include <stdio.h>

int main() {
    char string[200];
    int x=1;
    int counter=0;

    // I ask for the string
    printf("Give me a string: \n");
    fgets(string, sizeof(string), stdin);


    while (string[counter] != '\0') {
        counter++;
        if (string[counter] == ' '){
            x++;
        }
    }

    //  I show the user how many words has the string
    printf("\nThe string has %i words",x);

return 0;
}

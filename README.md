# EVM-project
#include <stdio.h>

int main() {
    int BJP = 0, CONG = 0, RJD = 0, JDU = 0, NOTA = 0;
    int choice, totalVotes = 500;

    printf("EVM_MS\n");
    printf("------------\n");
    printf("1. Vote for BJP\n");
    printf("2. Vote for CONG\n");
    printf("3. Vote for RJD\n");
    printf("4. Vote for JDU\n");
    printf("5. Vote for NOTA\n");
    printf("Total Number of Voters: %d\n", totalVotes);

    for (int i = 0; i < totalVotes; i++) {
        printf("Enter your choice (1-5): ");
        scanf("%d", &choice);

        if (choice == 1) {
            BJP++;
            printf("You voted for BJP\n");
        } else if (choice == 2) {
            CONG++;
            printf("You voted for CONG\n");
        } else if (choice == 3) {
            RJD++;
            printf("You voted for RJD\n");
        } else if (choice == 4) {
            JDU++;
            printf("You voted for JDU\n");
        } else if (choice == 5) {
            NOTA++;
            printf("You voted for NOTA\n");
} 
else 
{
            printf("Invalid choice. Please enter a number between 1 and 5.\n");
            i--;
        }
    }

    printf("\nFinal Vote Count:\n");
    printf("BJP: %d\n", BJP);
    printf("CONG: %d\n", CONG);
    printf("RJD: %d\n", RJD);
    printf("JDU: %d\n", JDU);
    printf("NOTA: %d\n", NOTA);

    return 0;
}

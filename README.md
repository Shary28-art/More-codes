# More-codes
#include <stdio.h>

int main() {
    float basicPay; // To store the basic pay
    float hra, ta, da; // To store the allowances
    float netSalary; // To store the net salary

    // Input Basic Pay
    printf("Enter the Basic Pay: ");
    scanf("%f", &basicPay);

    // Calculate allowances
    hra = 0.10 * basicPay;
    ta = 0.15 * basicPay;  // TA = 15% of BP
    da = 0.05 * basicPay;  // DA = 5% of BP

    // Calculate Net Salary
    netSalary = basicPay + hra + ta + da;

    // Print Net Salary
    printf("The Net Salary is: %.2f\n", netSalary);

    return 0;
}

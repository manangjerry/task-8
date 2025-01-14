
#include <stdio.h>
#include <stdlib.h>





/*int main() {
    int num_items;
    float price_per_item;   // Price of each item
    float total_sales;      // Total sales amount
    float total_commission; // Total commission earned

    // Get user input
    printf("Enter the number of items sold: ");
    scanf("%d", &num_items);

    printf("Enter the price of each item: ");
    scanf("%f", &price_per_item);

    // Calculate total sales
    total_sales = num_items * price_per_item;

    // Determine the commission based on the total sales
    if (total_sales < 100) {
        total_commission = 0; // No commission for sales less than $100
    }
    else if (total_sales <= 250) {
        total_commission = (total_sales * 5) / 100; // 5% commission for sales over $100 but <= $250
    }
    else {
        total_commission = (total_sales * 10) / 100; // 10% commission for sales over $250
    }

    // Display the results
    printf("\n--- Commission Calculation ---\n");
    printf("Total Sales: $%.2f\n", total_sales);
    printf("Total Commission: $%.2f\n", total_commission);

output
Enter the number of items sold: 4
Enter the price of each item: 30000

--- Commission Calculation ---
Total Sales: $120000.00
Total Commission: $12000.00*/



/*
    int num_items_sold;          // Number of items sold
    float price_per_item;   // Price of each item
    float total_sales;      // Total sales amount
    float total_commission; // Total commission earned

    // Get user input
    printf("Enter the number of items sold: ");
    scanf("%d", &num_items_sold);

    printf("Enter the price of each item: ");
    scanf("%d", &price_per_item);

    // Calculate total sales
    total_sales = num_items * price_per_item;

    // Determine the commission based on the total sales
    if (total_sales < 100) {
        total_commission = 0; // No commission for sales less than $100
    }
    else if (total_sales <= 250) {
        total_commission = (total_sales * 5) / 100; // 5% commission for sales over $100 but <= $250
    }
    else {
        total_commission = (total_sales * 10) / 100; // 10% commission for sales over $250
    }

    // Display the results
    printf("\n--- Commission Calculation ---\n");
    printf("Total Sales: $%.2f\n", total_sales);
    printf("Total Commission: $%.2f\n", total_commission);

output_
Enter the number of items sold: 2
Enter the price of each item: 3000

--- Commission Calculation ---
Total Sales: $6000.00
Total Commission: $600.00
*/



/*
    int num_items;          // Number of items sold
    float price_per_item;   // Price of each item
    float total_sales;      // Total sales amount
    float total_commission; // Total commission earned

    // Get user input
    printf("Enter the number of items sold: ");
    scanf("%d", &num_items);

    printf("Enter the price of each item: ");
    scanf("%f", &price_per_item);

    // Calculate total sales
    total_sales = num_items * price_per_item;

    // Determine the commission based on the total sales
    if (total_sales < 100) {
        total_commission = 0; // No commission for sales less than $100
    }
    else if (total_sales <= 250) {
        total_commission = (total_sales * 5) / 100; // 5% commission for sales over $100 but <= $250
    }
    else {
        total_commission = (total_sales * 10) / 100; // 10% commission for sales over $250
    }

    // Display the results
    printf("\n--- Commission Calculation ---\n");
    printf("Total Sales: $%.2f\n", total_sales);
    printf("Total Commission: $%.2f\n", total_commission);

output
Enter the number of items sold: 3
Enter the price of each item: 4000

--- Commission Calculation ---
Total Sales: $12000.00
Total Commission: $1200.00*/






  /*  int quantity_marketed;           // Quantity of items marketed
    float price_per_item;   // Selling price per item
    float total_sales;      // Total sales amount
    float commission_per_item; // Commission per item

    // Get user input
    printf("Enter the quantity of items marketed: ");
    scanf("%d", &quantity);

    printf("Enter the selling price per item: ");
    scanf("%f", &price_per_item);

    // Calculate total sales
    total_sales = quantity * price_per_item;

    // Determine the commission per item based on the total sales
    if (total_sales < 100) {
        commission_per_item = 0; // No commission for sales less than $100
    }
    else if (total_sales <= 250) {
        commission_per_item = (price_per_item * 5) / 100; // 5% commission for sales over $100 but <= $250
    }
    else {
        commission_per_item = (price_per_item * 10) / 100; // 10% commission for sales over $250
    }

    // Display the results
    printf("\n--- Commission Calculation ---\n");
    printf("Total Sales: $%.2f\n", total_sales);
    printf("Commission per Item: $%.2f\n", commission_per_item);

output

*/


/*
int isEven(int num) {
    if (num % 2 == 0) {
        return 1;  // Return 1 if the number is even
    } else {
        return 0;  // Return 0 if the number is odd
    }
}

int main() {
    int num;  // Declare variable for user input

    // Get user input
    printf("Enter a number: ");
    scanf("%d", &num);

    // Check if the number is even or odd using the isEven function
    if (isEven(num)) {
        printf("%d is even.\n", num);
    } else {
        printf("%d is odd.\n", num);
    }

output

Enter a number: 12
12 is even.*/


/*
int max(int a, int b) {
    if (a > b) {
        return a;  // If 'a' is greater than 'b', return 'a'
    } else {
        return b;  // Otherwise, return 'b'
    }
}

int main() {
    int num1, num2;  // Declare variables for two numbers

    // Get user input for the two numbers
    printf("Enter the first number: ");
    scanf("%d", &num1);

    printf("Enter the second number: ");
    scanf("%d", &num2);

    // Call the max function and display the result
    printf("The greater of %d and %d is %d.\n", num1, num2, max(num1, num2));


output
Enter the first number: 2
Enter the second number: 4
The greater of 2 and 4 is 4.*/



/*
int isLeapYear(int year) {
    // Check if the year is divisible by 4
    // If divisible by 100, it must also be divisible by 400 to be a leap year
    if ((year % 4 == 0 && year % 100 != 0) || (year % 400 == 0)) {
        return 1;  // Return 1 if it's a leap year
    } else {
        return 0;  // Return 0 if it's not a leap year
    }
}

int main() {
    int year;  // Declare variable for user input

    // Get user input for the year
    printf("Enter a year: ");
    scanf("%d", &year);

    // Check if the year is a leap year using the isLeapYear function
    if (isLeapYear(year)) {
        printf("%d is a leap year.\n", year);
    } else {
        printf("%d is not a leap year.\n", year);
    }

output
Enter a year: 2020
2020 is a leap year.*/




/*
int signOfNumber(int num) {
    if (num < 0) {
        return -1;  // Return -1 for negative numbers
    } else if (num > 0) {
        return 1;   // Return 1 for positive numbers
    } else {
        return 0;   // Return 0 for zero
    }
}

int main() {
    int num;  // Declare a variable to store the user input

    // Get user input for the number
    printf("Enter a number: ");
    scanf("%d", &num);

    // Call the signOfNumber function and display the result
    int sign = signOfNumber(num);

    if (sign == -1) {
        printf("%d is negative.\n", num);
    } else if (sign == 1) {
        printf("%d is positive.\n", num);
    } else {
        printf("%d is zero.\n", num);
    }

output
Enter a number: 6
6 is positive.*/



/*
char calculateGrade(int score) {
    if (score >= 90) {
        return 'A';  // Grade A for scores 90 and above
    } else {
        if (score >= 80) {
            return 'B';  // Grade B for scores between 80 and 89
        } else {
            if (score >= 70) {
                return 'C';  // Grade C for scores between 70 and 79
            } else {
                if (score >= 60) {
                    return 'D';  // Grade D for scores between 60 and 69
                } else {
                    return 'F';  // Grade F for scores below 60
                }
            }
        }
    }
}

int main() {
    int score;  // Declare variable for score

    // Get user input for the score
    printf("Enter the score: ");
    scanf("%d", &score);

    // Call the calculateGrade function and display the result
    char grade = calculateGrade(score);
    printf("The grade for score %d is: %c\n", score, grade);


output
Enter the score: 50
The grade for score 50 is: F*/

/*
const char* temperatureStatus(float temp) {
    if (temp < 15.0) {
        return "Cold";  // Temperature below 15°C is considered cold
    } else if (temp >= 15.0 && temp <= 25.0) {
        return "Warm";  // Temperature between 15°C and 25°C is considered warm
    } else {
        return "Hot";  // Temperature above 25°C is considered hot
    }
}

int main() {
    float temp;  // Declare variable for temperature

    // Get user input for the temperature
    printf("Enter the temperature: ");
    scanf("%f", &temp);

    // Call the temperatureStatus function and display the result
    const char* status = temperatureStatus(temp);S
    printf("The temperature status is: %s\n", status);


output
Enter the temperature: hot
The temperature status is: Cold*/


/*
int isEligible(int age) {
    if (age >= 18) {
        return 1;  // Return 1 if age is 18 or greater (eligible to vote)
    } else {
        return 0;  // Return 0 if age is less than 18 (not eligible to vote)
    }
}

int main() {
    int age;  // Declare variable for age

    // Get user input for age
    printf("Enter your age: ");
    scanf("%d", &age);

    // Check if the person is eligible to vote using the isEligible function
    if (isEligible(age)) {
        printf("You are eligible to vote.\n");
    } else {
        printf("You are not eligible to vote.\n");
    }


output
Enter your age: 10
You are not eligible to vote.*/



/*
int isPositive(int num) {
    if (num > 0) {
        return 1;  // Return 1 if the number is positive
    } else {
        return 0;  // Return 0 for non-positive numbers (0 or negative)
    }
}

int main() {
    int num;  // Declare variable for the number

    // Get user input for the number
    printf("Enter a number: ");
    scanf("%d", &num);

    // Check if the number is positive using the isPositive function
    if (isPositive(num)) {
        printf("%d is a positive number.\n", num);
    } else {
        printf("%d is not a positive number.\n", num);
    }

output

Enter a number: 5
5 is a positive number.*/


// Function to check if three sides can form a valid triangle
int isValidTriangle(int a, int b, int c) {
    // Check if the triangle inequality theorem is satisfied
    if (a + b > c && a + c > b && b + c > a) {
        return 1;  // Return 1 if the sides can form a valid triangle
    } else {
        return 0;  // Return 0 if the sides cannot form a valid triangle
    }
}

int main() {
    int a, b, c;  // Declare variables for the sides of the triangle

    // Get user input for the three sides
    printf("Enter the first side: ");
    scanf("%d", &a);

    printf("Enter the second side: ");
    scanf("%d", &b);

    printf("Enter the third side: ");
    scanf("%d", &c);

    // Check if the sides can form a valid triangle using the isValidTriangle function
    if (isValidTriangle(a, b, c)) {
        printf("The sides can form a valid triangle.\n");
    } else {
        printf("The sides cannot form a valid triangle.\n");
    }


output
Enter the first side: 2
Enter the second side: 1
Enter the third side: 3
The sides cannot form a valid triangle.

    return 0;
}



/*
Create a program that determines if a student can apply for a scholarship.

Criteria for eligibility:

    The student has a GPA of 3.5 or higher OR has recommendations
    The student must have completed at least 60 credit hours
    The student must NOT have any academic violations
*/

#include <stdio.h>

int checkEligibility(float gpa, int creditHours, int hasViolations, int hasRecommendations) {
    // Write your code here to check eligibility
    if (( gpa >= 3.5 ) && ( creditHours >= 60 ) && ( hasViolations == 0 || hasRecommendations == 1 )) {
        return 1;}
    else {
        return 0; 
    }
    // Return 1 if eligible, 0 if not eligible
}

int main() {
    float gpa;
    int creditHours, hasViolations, hasRecommendations;
    
    // Read input values
    scanf("%f", &gpa);
    scanf("%d", &creditHours);
    scanf("%d", &hasViolations);
    scanf("%d", &hasRecommendations);
    
    // Check eligibility
    if (checkEligibility(gpa, creditHours, hasViolations, hasRecommendations)) {
        printf("The student is eligible for the scholarship.\n");
    } else {
        printf("The student is not eligible for the scholarship.\n");
    }
    
    return 0;
}
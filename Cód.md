# average_of_two_temperatures

#include<stdio.h>

float t1, t2;

float calcularmedia(){
    return (t1+t2) / 2;
}
int main() {
    printf("\nDigite as duas temperatiuras: ");
    scanf("%f %f", &t1, &t2);
    printf("\nA temperatura média é %.2f", calcularmedia());
    
    return 0;

}

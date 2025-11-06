#include <stdio.h>
int main() {
char name[30];
float num, room_rent, mess_charge,  extra_charges, total bill 

printf("Enter Student name: ");
scanf("%s", &name) ;

printf("Enter contact number:");
scanf("%d", &num);

printf("Enter room_rent:");
scanf("%d", &room_rent);

printf("Enter mess charge:");
scanf("%d", &mess_charge);

printf("Enter extra_charges:");
scanf("%d", &extra_charges); 

total_bill = room_rent + mess_charges + extra_charges;

printf("\n===== HOSTEL FEE BILL =====\n");
printf("\n");
printf("Student Name    : %s\n", name);
printf("Contact Number : %d\n", num);
printf("\n");
printf("--------------------------------------\n);
printf("\n");
printf("Room Rent      : Rs.%f\n", room_rent);
printf("Mess Charges   : Rs.%f\n",mess_charges);
printf("Extra Charges  : Rs.%f\n",extra_charges);
printf("\n");
printf("---------------------------------------\n")
printf("\n");
printf("TOTAL BILL : Rs. %d\n", total);
printf("\n");
printf("=======================\n");
return 0;
}

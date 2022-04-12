#define _CRT_SECURE_NO_WARNINGS
#include <stdlib.h>
#include <stdio.h>



//מבנה
struct Date //שם המבנה הוא
{
	int day;
	int month;
	int year;
};

void main()
{
	// d is just a name - could use anything
	struct Date d; // הגדרת המשתנה מטיפוס המבנה
	d.day = 6; 
	d.month = 1;
	d.year = 2003;

	printf("The date is %d/%d/%d.\n", d.day, d.month, d.year);

}

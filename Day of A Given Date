#include <stdio.h>
int main() {
    int dd,m,y,weekday;
    scanf("%d/%d/%d",&dd,&m,&y);
    if(dd<0 || m>12 )
    {
        printf("Invalid Date");
    }
    else
    {
        weekday  = (dd+=m<3?y--:y-2,23*m/9+dd+4+y/4-y/100+y/400)%7  ;
        switch(weekday) {
		case 0:
			printf("Sunday");
			break;
		case 1:
                        printf("Monday");
			break;
		case 2:
                        printf("Tuesday");
			break;
		case 3:
                        printf("Wednesday");
			break;
		case 4:
                        printf("Thursday");
			break;
		case 5:
                        printf("Friday");
			break;
		case 6:
                        printf("Saturday");
	}
    } 
    return 0;
}

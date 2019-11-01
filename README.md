include <time.h>

include<studio.h>

include<iostream>

｛

time_t t=time(0);​

srand(t);



int num =rand()%50;｝



printf("时间到%d\n",t)

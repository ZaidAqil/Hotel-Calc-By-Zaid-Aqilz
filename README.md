# Hotel-Calc-By-Zaid-Aqilz
//Zaids Programme :)
#include <iostream>
using namespace std;

int main()
{
    int floor,rooms,occroom,z;
    double percent,total_r=0,total_or=0,total_ur=0;
     
     cout<<"How many floors does this Hotel have?\n";
     cin>>floor;
     for(z=1;z<=floor;z++)
     {
     cout<<"What are the number of rooms on floor  "<<z <<"?" <<endl;
     cin>>rooms;
     cout<<"What is the number of occupied rooms on floor  "<<z<<"?" <<endl;
     cin>>occroom;
     total_r+=rooms;
     total_or+=occroom;
     total_ur=(total_r)-(total_or);
     }
     percent=(total_or)/(total_r) *100;
     cout<<"Number of rooms in this Hotel is  :"<<total_r<<endl;
     cout<<"Number of rooms that are currently occupied is  : "<<total_or<<endl;
     cout<<"Number of rooms that is currenlty unoccupied is  :"<<total_ur<<endl;
     cout<<"The percentage of rooms that is occupied is  :"<<percent<<endl;
     cout<<"Thank You for using our software :) =)";
     return 0;
     }

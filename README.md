code for automatic opening and closing of shed:


#include<iostream>
using namespace std;
int main()
{
  bool raining;
  cout<<"is it raining?/n";
  cout<<"enter 1 if yes\n enter 0 if no";
  cin>>raining;
  if(raining)
  {cout<<"rain detected/n";
    cout<<"opening rain shed";}
    else { cout<<"rain isn't detected/n";
      cout<<"closing shed";}
    }
  
2nd :
#include<iostream>
using namespce std;
int main()
{
  int temperature;
  cout<<"enter temperature\n";
  cin>>temperature;
  if(temprature<=18){cout<<"close fan or use at low speed";}
  else if(temperature>=18){cout<<"use fan at medium speed";}
  else if(temperature>=25){cout<<"use fan at high speed";}
  else if(temperature>=30){cout<<"use AC or use fan at higg speed";}
else {cout<<"no need of fan can use heater";}
}

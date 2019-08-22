#include <iostream>

using namespace std;

int main()
{
    
   //Sentinel-Controlled Loop
   cout << "Sentinel-Controlled Loop" << endl;
   
   int sentinel_value = 0;
   
   while(sentinel_value > -1){
       cout << "Nice one" << endl;
       sentinel_value--;
   }

    return 0;
}

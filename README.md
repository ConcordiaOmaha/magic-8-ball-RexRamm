#include <iostream>
#include <string>

int main()
{
    
int userResponse;
std::cout << "How are you feeling today on a scale of 1-10:\n";
std::cin >> userResponse;
 

if (userResponse < 4) {  

    std::cout << " We Hope you feel better tommorow...\n ";
}
else if(userResponse == 5){

   std::cout << " It could be worse...\n ";
}
else if(userResponse != 6) {

    std::cout << " NICE...\n ";
} 
else {
    std::cout << " You are having a good day...\n ";
}

int randNum = rand() % 100;

if (randNum < 49) 
{
    std::cout << " That Sucks\n ";
}    
else if(randNum == 50 ){
    std::cout <<  " Better luck next time\n ";
}    
else if (randNum == 51){
    std::cout << "life must be pretty good for you\n";
}    
else {
    std::cout << "Atleast you are lucky\n";    
}    
    
    
    
    
    
}

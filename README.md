# Magic-9-Ball---Ten-Options
#include <iostream>
#include <cstdlib>
int main(){

std::cout << "MAIGIC 8-BALL:\n\n";

srand(time(NULL));

int answer = std::rand() % 10;


if (answer == 0){

std::cout << "It is certain.\n";

}
else if (answer == 9){

  std::cout << "It is decidedly so.\n";

}
else if (answer == 8 ) {

  std::cout << "Don't count on it.\n";

}
else if (answer == 7) {

  std::cout << "My sources say no.\n";
  
}
else if (answer == 6) {

  std::cout << "Most likely.\n";
  
}
else if (answer == 5) {

std::cout << "Yes - definitely.\n";

}
else if (answer == 5){

std::cout << "Reply hazy, try again.\n";

}
else if (answer == 4){

  std::cout << "Cannot predict now.\n"; 

}
else if (answer == 3) {

  std::cout << "Outlook good.\n";
  
}
else if (answer == 2) {

  std::cout << "My reply is no.\n";
}

else{
  
  std::cout << "Very doubtful.\n";

}

return 0;

 }
 

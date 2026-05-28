```C++
# Include <iostream>
# Include <string>

int main() {std::cout << "Enter your name:";
std::string name; //
std::cin >> name;
std::cout << "Hello," << name <<"!\n";
std::cout << name << ",lets play a game!\n";
std::cout <<"What's 5+5?";
std::cout <<"1. 0\n";
std::cout <<"2. 10\n";
std::cout <<"Please enter 1 or 2.";

int choice;
std::cin >> choice; //
if (choice == 2) {std::cout << "Correct! Good job."}
else if (choice == 1) {std::cout <<"Oops! The answer was wrong."} 
else (choice == 3) {std::cout <<"Bro. This is an invalid response."} return 0;}

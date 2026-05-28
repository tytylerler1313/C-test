```C++
# Include <iostream>
# Include <string>

int main() {std::cout << "Enter your name:";
std::string name; //
std::cin >> name;
std::cout << "Hello," << name <<"!\n";
std::cout << name << ",lets play a game!\n";

int score = 0; //
std::cout <<"What's 5+5?";
std::cout <<"1. 0\n";
std::cout <<"2. 10\n";
std::cout <<"Please enter 1 or 2.";

int choice;
std::cin >> choice; //
if (choice == 2) {std::cout << "Correct! Good job.\n"; score = score + 1;//2. Increased score by 1}
else if (choice == 1) {std::cout << "Oops! The answer was wrong."} 
else {std::cout << "Bro. This is an invalid response."}

std::cout <<"Next question. What's 6*9?";
std::cout <<"1. 54\n";
std::cout <<"2. 15\n";
std::cout <<"Please enter 1 or 2.";

int choice_2;
std::cin >> choice_2; //
if (choice_2 == 1) {std::cout << "Correct! Good job.\n"; score = score + 1;//2. Increased score by 1}
else if (choice_2 == 2) {std::cout << "Oops! The answer was wrong."}
else {std::cout << "Bro. This is an invalid response."} return 0;}

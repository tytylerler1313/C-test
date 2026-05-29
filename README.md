```C++
# include <iostream>
# include <string>
# include <cstdlib>
# include <ctime>

int main() {srand(time(0));
std::cout << "Enter your name:";
std::string name; //
std::cin >> name; //
std::cout << "Hello," << name <<"!\n";
std::cout << name << ",lets play a game!\n";

std::string = "Pet
int score = 0; //
int xp = 0; //
int level = 0; //
int reward = 0; //
int coins = 0; //
int gems = 0; //
int shiny emeralds = 0; //
bool playing = true;
while (playing == true){
int num1 = rand()% 10 + 1;
int num2 = rand()% 10 + 1;
int correct_answer = num1 + num2;
int wrong_answer = num1 + num2 - rand()% 10 + 1;
std::cout << "What's" <<" "<< num1 << "+" << num2 << "?\n";
std::cout << "1." << wrong_answer << "\n";
std::cout << "2." << correct_answer <<"\n";
std::cout << "Please enter 1 or 2.";

int choice;
std::cin >> choice; //
if (choice == 2) {std::cout << "Correct! Good job.\n"; score = score + 1; xp = xp + 50;}
else if (choice == 1) {std::cout << "Oops! The answer was wrong.";} 
else {std::cout << "Bro. This is an invalid response.";}

int num3 = rand()% 7 + 1;
int num4 = rand()% 7 + 1;
int correct_answer_2 = num3 * num4;
int wrong_answer_2 = num3 * num4 - rand()% 15 + 1;
std::cout << "What's" <<" "<<num3 << "*" << num4 << "?\n";
std::cout << "1." << correct_answer_2 << "\n";
std::cout << "2." << wrong_answer_2 << "\n";
std::cout << "Please enter 1 or 2.";

int choice_2;
std::cin >> choice_2; //
if (choice_2 == 1) {std::cout << "Correct! Good job.\n"; score = score + 1; xp = xp + 50;}
else if (choice_2 == 2) {std::cout << "Oops! The answer was wrong.";}
else {std::cout << "Bro. This is an invalid response.";}

std::cout << "Your final score is" << score << "/2!";
if (xp >= 100) {std::cout <<"Nice! You have leveled up!\n"; level = level + 1;}
if (level == 1) {std::cout << "Congrats! There is a reward waiting for you!\n"; reward = reward + 1;}
if (reward == 1) {std::cout << "Choose your reward:";
std::cout << "1. 100 coins\n";
std::cout << "2. 10 gems\n";
std::cout << "Please choose one.\n";

int reward_choice; //
std::cin >> reward_choice; //
if (reward_choice == 1) {std::cout << "Great choice! +100 coins!\n"; coins = coins + 100;}
else if (reward_choice == 2) {std::cout << "Awesome choice! +10 gems!\n"; gems = gems + 10;}
else {std::cout << "Please choose a valid reward bro.";}}

std::cout << "\n--- Welcome to the Shop Of Legends ---\n";
std::cout << "Your balance:" << coins << "coins," << gems << "gems.\n";
std::cout << "Please select an item to buy:";
std::cout << "1. Normal Cat\n";
std::cout << "2. A Bag of Shiny Emeralds\n";
std::cout << "3. Exit shop\n";

int shop_option; //
std::cin >> shop_option; //
if (shop_option == 1) {(if coins >= 250){coins = coins - 100; pet = "Normal Cat"; std::cout << "NICE! You've successfully bought a Normal Cat! Pet equipped!"}
else {std::cout << "Bro. You can't afford this item.\n";}}
else if (shop_option == 2) {(if coins >= 500){coins = coins - 500; shiny emeralds = shiny emeralds + 25; std::cout << "GREAT! You've successfully bought A Bag of Shiny Emeralds! Shiny emeralds + 25!"}
else {std::cout << "Bro. You can't afford this item.\n";}}
else {std::cout << "Exiting shop. Mind your steps!"}



int play_again; //
std::cout << "Do you want to play again?\n";
std::cout << "1. Yes\n";
std::cout << "2. No\n";
std::cin >> play_again; //
if (play_again == 2) {playing = false; std::cout << "Goodbye! You finished with" << coins << "coins.\n";}
else if (play_again == 1) {playing = true;}
else {std::cout << "Bro. Select an option.";}} return 0;} //

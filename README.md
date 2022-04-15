#include <iostream>
#include <string>


using namespace std;



void coffee() {
string Firstchoice;
int choice2;
int money;
while (Firstchoice != "c" && "C")
{
cout << "Coffee it is then, great! Which one would you want?" << endl;
cout << "Please input 0 for Ice coffee, 1 for Milk coffee, and 2 for Black Coffee." << endl;
cin >> choice2;
if (choice2 == 0) {
cout << "Ice coffee! Good choice! It will cost 3 dirhams, how much money do you have?" << endl;
cin >> money;
if (money > 3) {
cout << "your change will be " << money - 3 << " dirhams, thank you very much!" << endl;
break;
}
else if (money == 3) {
cout << "thank you for providing exact amount! See you again." << endl;
break;
}
else {
cout << "Error, insufficient amount. Transaction cancelled." << endl;
break;

}
}
else if (choice2 == 1) {

cout << "Milk coffee! Good choice! It will cost 2 dirhams, how much money do you have?" << endl;
cin >> money;
if (money > 2) {
cout << "your change will be " << money - 2 << " dirhams, thank you very much!" << endl;
break;
}
else if (money == 2) {
cout << "thank you for providing exact amount! See you again." << endl;
break;
}
else {
cout << "Error, insufficient amount. Transaction cancelled." << endl;
break;
}
}
else if (choice2 == 2) {
cout << "Black coffee! Interesting choice! It will cost 1 dirham, how much money do you have?" << endl;
cin >> money;
if (money > 1) {
cout << "your change will be " << money - 1 << " dirhams, thank you very much!" << endl;
break;
}
else if (money == 1) {
cout << "thank you for providing exact amount! See you again." << endl;
break;
}
else {
cout << "Error, insufficient amount. Transaction cancelled." << endl;
break;
}
}
}
}



void tea() {
string Firstchoice;
int choice2;
int money;
while (Firstchoice != "t" && "T")
{
cout << "Tea? Wonderful! Choose your tea of choice." << endl;
cout << "Please input 0 for Ice tea, 1 for Milk tea, and 2 for Black tea." << endl;
cin >> choice2;
switch (choice2)
{
case 0:
cout << "Ice Tea! Sweet! That would be 3 dirhams, how much money do you have so I can provide change?" << endl;
cin >> money;
if (money > 3) {
cout << "your change will be " << money - 3 << " dirhams, thank you very much!" << endl;
break;
}
else if (money == 3) {
cout << "thank you for providing exact amount! See you again." << endl;
break;
}
else {
cout << "Error, insufficient amount. Transaction cancelled." << endl;
break;

}
case 1:
cout << "Milk tea! Good choice! It will cost 2 dirhams, how much money do you have?" << endl;
cin >> money;
if (money > 2) {
cout << "your change will be " << money - 2 << " dirhams, thank you very much!" << endl;
break;
}
else if (money == 2) {
cout << "thank you for providing exact amount! See you again." << endl;
break;
}
else {
cout << "Error, insufficient amount. Transaction cancelled." << endl;
break;
}

case 2:
cout << "Black tea! Strong choice! It will cost 1 dirham, how much money do you have?" << endl;
cin >> money;
if (money > 1) {
cout << "your change will be " << money - 1 << " dirhams, thank you very much!" << endl;
break;
}
else if (money == 1) {
cout << "thank you for providing exact amount! See you again." << endl;
break;
}
else {
cout << "Error, insufficient amount. Transaction cancelled." << endl;
break;
}
default:
cout << "Invalid input, please try again" << endl;
break;
}
break;
}
}



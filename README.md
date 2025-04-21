# gitHubTest
#include <iostream>
#include <cstdlib>
#include <ctime>

using namespace std;

string gjenero_fjale_motivuese() {
string fjalet[] = {"Mos u dorëzo, suksesi është afër!",
"Beso në veten tënde dhe gjithçka është e mundur!",
"Çdo ditë është një mundësi e re!",
"Puna e palodhur gjithmonë shpërblehet!"};
srand(time(0));
return fjalet[rand() % 4];
}

int main() {
cout << "Fjala motivuese e ditës: " << gjenero_fjale_motivuese() << endl;
return 0;
}

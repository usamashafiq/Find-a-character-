#include<iostream>
#include<conio.h>
#include<string>

using namespace std;
void main() {
	char name[100];
	int sum = 0;
	cout << "Enter a story" << endl;
	cin.getline(name, 100);
	for (int i = 0; i < 100; i++) {
		if (name[i] == 'a') {
			sum += 1;
		}
}

	cout << " 'a' occurred " << sum << " times";
	
	_getch();
}

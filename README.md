#include <iostream>
using namespace std;

int main() {
	int n;
	cout << "enter n: ";
	cin >> n;
	int TOTAL = 0;
	for (int i = 1; i <= n; i++) {
		if (i % 5 == 0) {
			TOTAL++;
		}
	}
	cout << "number of leading zeros is " << TOTAL;
	return 0;
}

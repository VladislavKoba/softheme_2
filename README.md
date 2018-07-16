# Algoritma_test_2
>Предложите максимально эффективный алгоритм для поиска всех целочисленных делителей числа.

```
#include <iostream>
#include <fstream>
using namespace std;

int main() {
	
	int n; 
	
	cout<< "number is: ";
	cin >> n;
	
	for (int i = 1; i <= n / 2; i++) {
			if (n % i == 0) {
				cout<< i<<endl;
			}
		}
	return 0;
}

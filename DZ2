// Project_2.cpp: определяет точку входа для консольного приложения.
//

#include "stdafx.h"
#include <iostream>
#include <windows.h>

using namespace std;

/* переворот числа */
void reverseNumber(char * number, char * reverse)
{
	int k = 0;
	int numberSize = strlen(number);

	for (int i = numberSize - 1; i >= 0; i--)
		reverse[k++] = number[i];
}

void main()
{
	SetConsoleCP(1251);
	SetConsoleOutputCP(1251);

	char num[6] = "12345";
	char reverseNum[6] = { 0 };
	reverseNumber(num, reverseNum);
	cout << "Переворот числа: " << endl << "число: " << num << " = перевёрнутое число: " << reverseNum << endl << endl;

	// изначально считаем, что все числа положительны
	bool result = true;
	int number;
	do
	{
		cout << "Введите число: ";
		cin >> number;

		if (number < 0)
		{
			result = false;
		}
	} while (number != 0);

	if (result)
		cout << "Все числа положительны" << endl;
	else
		cout << "Не все числа положительны" << endl;

	system("pause");
}

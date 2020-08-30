#include <iostream>
#include <cmath>
#include <string>

using namespace std;

int main()
{
	int a;
	int b;
	int c = 2;
	int d = 0;
	string e;

	cout << "Írja ide a nevét" << endl;
	cin >> e;

	cout << "Üdvüzlöm "   << e << endl;

	cout << "írjon be egy nem nulla számot" << endl;
	cin >> a;

	cout << "írjon be egy másik nem nulla számot" << endl;
	cin >> b;

	cout << "A két szám összege: " << endl;
	cout << a + b << endl;

	cout << "A két szám különbsége( első - második): " << endl;
	cout << a - b << endl;

	cout << "A kétszám különbsége( második - első): " << endl;
	cout << b - a << endl;

	cout << "A két szám szorzata: " << endl;
	cout << a * b << endl;

	cout << "Két szám hányadosa egészekben (első / második): " << endl;
	cout << a / b << endl;

	cout << "Két szám hányadosa maradékosan ( eslő / második): " << endl;
	cout << a % b << endl;

	cout << "Két szám hányadosa egészekben (második / első): " << endl;
	cout << b / a << endl;

	cout << "Két szám hányadosa maradékosan: (második / első): " << endl;
	cout << b % a << endl;

	cout << "AZ első szám nagyobb tíznél: " << endl;
	if (a > 10)
	{
		cout << "Igen" << endl;

	}
	if(a < 10)
	{
		cout << "Nem " << endl;
	}
	if (a = 10)
	{
		cout << "A beírt szám pont tíz." << endl;
	}

	cout << "AZ második szám nagyobb tíznél: " << endl;
	if (b > 10)
	{
		cout << "Igen" << endl;

	}
	if( b < 10)
	{
		cout << "Nem " << endl;
	}
	if (b = 10)
	{
		cout << "A beírt szám pont tíz" << endl;
	}
	
	cout << "Az első szám pozitiv vagy negativ: " << endl;
	if (a > 0)
	{
		cout << "Pozitiv" << endl;
	}
	if (a < 0)
	{
		cout << "negativ" << endl;
	}
	if (a = 0)
	{
		cout << "A beírt szám a nulla. A nulla se nem negatív, se nem pozitiv." << endl;
	}

	cout << "A második szám pozitiv vagy negativ: " << endl;
	if (b > 0)
	{
		cout << "pozitiv" << endl;
	}
	if(b < 0)
	{
		cout << "negativ" << endl;
	}
	if (b = 0)
	{
		cout << "A beírt szám a nulla. A nulla se nem negatyv, se nem pozitiv." << endl;
	}

	cout << "Az első szám logaritmusa: " << endl;
	cout << log10(a) << endl;

	cout << "A második szám logaritmusa: " << endl;
	cout << log10(b) << endl;

	cout << "Az első szám természetes alapú logaritmusa(e alapú): " << endl;
	cout << log(a) << endl;

	cout << "A második szám természetes alapú logaritmusa(e alapú): " << endl;
	cout << log(b) << endl;

	cout << "Az első szám gyöke: " << endl;
	cout << sqrt(a) << endl;

	cout << "A Második szám gyöke: " << endl;
	cout << sqrt(b) << endl;

	cout << "Az első szám köbgyöke: " << endl;
	cout << cbrt(a) << endl;

	cout << "A második szám köbgyöke: " << endl;
	cout << cbrt(b) << endl;

	cout << "Az elsö szám abszolút értéke: " << endl;
	cout << abs(a) << endl;

	cout << "A második szám abszolút értéke: " << endl;
	cout << abs(b) << endl;

	cout << "Az első szám páros vagy páratlan: " << endl;

	if( d = a % c)
	{
		cout << "páros" << endl;
	}
	else
	{
		cout << "páratlan:" << endl;
	}

	cout << "A második szám szám páratlan vagy páros: " << endl;

	if (d = b % c)
	{
		cout << "páros" << endl;
	}
	else
	{
		cout << "páratlan" << endl;
	}

	






	system("pause");

	return 0;

}

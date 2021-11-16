# Falling Star, While Loop
```
#include <iostream>
using namespace std;
int main() 
{
    int x = 1;
    int y = 1;
    while (x <= 5) {
        y = x;
        while (y <= 5) {
            cout << "*";
            y++;
        }
        cout << endl;
        x++;
    }
    return 0;
}
```
# Rising Star, While Loop
```
#include <iostream>
using namespace std;
int main()
{
    int x = 1;
    int y = 1;
    while (x <= 5) {
        y = 1;
        while (y <= 5) {
            cout << "*";
            y++;
        }
        cout << endl;
        x++;
    }
    return 0;
}

```
# Falling then Rising, While Loop
```
#include <iostream>
using namespace std;
int main()
{
    int x = 1;
    int y = 1;
    while (x <= 5) {
        y = x;
        while (y <= 5) {
            cout << "*";
            y++;
        }

        cout << endl;
        x++;
    }
    int p = 1;
    int q = 1;
    while (p <= 5) {
        q = 1;
        while (q <= p) {
            cout << "*";
            q++;
        }

        cout << endl;
        p++;
    }
}

```
# Factorial, While Loop
```
#include <iostream>
using namespace std;
int main()
{
	int a, b = 1;
	cout << "Enter a number to !: " << endl;
	cin >> a;
	while (cin.fail() || a <= 0)
	{
		cout << "Number pls! " << endl;
		cin.clear();
		cin.ignore(1000, '\n');
		cin >> a;
	}
	for (int c = 1; c <= a; c++)
		b = b * c;
	cout << "Factorial: " << b;
}
```

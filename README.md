#include <iostream>
#include <cmath>

using namespace std;
int main() {
	float t, s;

	cin >> t;
	cout << "t = " << t << "\n";

	cin >> s;
	cout << "s = " << s << "\n";

	cout << "f(x) = " << (2 * t + 2 * s - sin(1.17)) / (4.4 - t - sin(s - t));
	return 0;
}
  

#include <iostream>
#include <cstdlib>
#include <ctime>
#include <wchar.h>
#include <Windows.h>
#include <algorithm>
#include <vector>
#include <string>
#include <conio.h>

#pragma warning(disable : 4996)

using namespace std;
enum days_of_week {
    Sun = 1,
    Mon,
    Tue,
    Wed,
    Thu,
    Fri,
    Sat
};


int main()
{
    days_of_week day1, day2;

    day1 = Mon;
    day2 = Thu;
    int diff = day2 - day1;
    cout << "Difference in days: " << diff << endl;
    if (day1 < day2) {
        cout << "day 1 came earlier than day 2\n";
    }
    

    return 0;
}

#include <iostream>

int main()
{


    //  TASK 1

    int a, b;
    std::cin >> a;
    std::cin >> b;
    if ( 10 <= a && a <= 20 && 10 <= b && b <= 20 ) {
        std::cout << "true" << std::endl;
    } else {
      std::cout << "false" << std::endl;
    }


    //  TASK 2

    const int c = 12;
    const int d = -2;

    if ( c + d == 10 || c == 10 || d == 10 ) {
        std::cout << "true" << std::endl;
    } else {
        std::cout << "false" << std::endl;
    }


    //  TASK 3

    for (size_t i = 1; i < 50; i = i + 2) {
        std::cout << i << std::endl;
    }


    //  TASK 4

    int e;
    std::cin >> e;
    bool isSimple = 1;
    for (size_t i = 2; i < e; i++) {
        if ( e % i == 0) {
            isSimple = 0;
            break;
        }
    }

    if ( isSimple ) {

            std::cout << "simple" << std::endl;
    } else {

            std::cout << "not simple" << std::endl;
    }


    //  TASK 5

    int year;
    do {
        std::cout << "Enter year from 0 to 3000: ";
        std::cin >> year;
    } while ( year < 1 || year > 3000 );
    if ( ( year % 4 == 0 && year % 100 != 0 ) || year % 400 == 0) {
        std::cout << year << " is leap year";
    } else {
        std::cout << year << " isn't leap year";
    }


    return 0;
}

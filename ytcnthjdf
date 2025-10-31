#include <iostream>
#include <string>

int main() {
    setlocale(LC_ALL, "Russian");
    int monthNumber;
    int day;
    std::string monthName;

    std::cout << "[ + ] Календарь\n";
    std::cout << "[ + ] Выберите месяц:\n";
    std::cout << "[ 1 ] Январь\n";
    std::cout << "[ 2 ] Февраль\n";
    std::cout << "[ + ] Введите номер месяца: ";
    std::cin >> monthNumber;

    switch (monthNumber) {
    case 1: monthName = "января"; break;
    case 2: monthName = "февраля"; break;
    default:
        std::cout << "[ + ] Неверный номер месяца.\n";
        return 1;
    }

    std::cout << "[ + ] Выбран месяц - \"" << monthName << "\"\n";
    std::cout << "[ + ] Введите день: ";
    std::cin >> day;

    // Простая проверка
    if (day < 1 || day > 31) {
        std::cout << "[ + ] Неверный день.\n";
        return 1;
    }

    // Используем switch по дню
    switch (day) {
    case 1:
        std::cout << "[ + ] Календарь: 1 " << monthName << ".\n";
        break;
    case 2:
        std::cout << "[ + ] Календарь: 2 " << monthName << ".\n";
        break;
    case 3:
        std::cout << "[ + ] Календарь: 3 " << monthName << ".\n";
        break;
    default:
        std::cout << "[ + ] День не реализован.\n";
        break;
    }

    return 0;
}

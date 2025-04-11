#include <iostream>

int main() {
    int a, b;
    std::cout << "Enter two numbers: ";
    std::cin >> a >> b;
    std::cout << "Sum: " << a + b << std::endl;
    std::cout << "Difference: " << a - b << std::endl;
    std::cout << "Product: " << a * b << std::endl;
    if (b != 0) { // Added a check to avoid division by zero.
        std::cout << "Quotient: " << static_cast<double>(a) / b << std::endl;
    } else {
        std::cout << "Cannot divide by zero." << std::endl;
    }
    return 0;
}

```cpp
#include <iostream>
#include <vector>
using namespace std;

int main() {
    string nome = "Pablo";
    string formacao = "Ciência da Computação (PUC-GO)";
    vector<string> tecnologias = {"C/C++", "C#", "ASP.NET", "MySQL"};
    vector<string> interesses = {"Desenvolvimento de Software", "Programação Competitiva", "Lógica de Programação"};

    cout << "Olá, sou " << nome << "\n";
    cout << "Faço " << formacao << "\n\n";

    cout << "Minhas Tecnologias:" << "\n";
    for (const auto &tech : tecnologias)
        cout << " - " << tech << "\n";

    cout << "\nMeus Interesses:" << "\n";
    for (const auto &item : interesses)
        cout << " - " << item << "\n";

    return 0;
}
```

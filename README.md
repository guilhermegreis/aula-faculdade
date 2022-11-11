#include <iostream>

using namespace std;

int main() {

    const int LINHAS = 4, COLUNAS = 5;
    int m[LINHAS][COLUNAS] = { 0 };

    cout << "Imprimindo uma matriz!" << endl;
    for (int l = 0; l < LINHAS; l++) {
        for (int c = 0; c < COLUNAS; c++) {
            cout << m[l][c];
        }
        cout << endl;
    }
}

#include <iostream>
#include <math.h>
#include <ctime>
void keySearch (char key,charkay,int  n,char array) {
    int start;
    start = clock();
    for (int b = 0; b!=1;) {
    for (int g = 0; g<n; g++) {
        kay [g] = array [rand()%15];
    }
    for (int g = 0; g<n; g++) { 
        if (kay[g] == key[g]) {
            b = 1;
        }
        else {
            b = 0;
        }
    }
    }
  std::cout<<"\n"<<start<<" milisecond";
}
int main() {
    srand(time(NULL));
    int n;
    int a = 2;
    std::cout<<"Enter key bit: ";
    std::cin >> n;
    a = pow(a, n);
    std::cout<<"Amount of key variables: " << a << std::endl;
    n = n/4;
    charkey = new char[n];
    char *kay = new char[n];
    char array [20] = {"0123456789ABCDEF"};
    std::cout<<"0x"; 
    for (int i = 0; i<n;i++) {
        key [i] = array [rand()%15];
        std::cout<<key[i];
    }
    keySearch(key,kay, n,array);
    system("PAUSE");
    return 0;
}

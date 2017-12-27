```
#include <iostream>
using namespace std;

int main() {

int numberArray[10][10];

for(int i=1;i<11;i++){
for(int j=1;j<11;j++){
numberArray[i - 1][j - 1] = i*j;
cout << numberArray[i-1][j-1] << "\t " << flush;
}
cout << endl;
}
return 0;
}
```

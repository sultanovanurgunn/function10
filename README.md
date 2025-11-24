# function10
#include <iostream>
using namespace std;

void printFactorial(){
    int n;
    cout<<"bir eded daxil edin: ";
    cin>> n;
    
    int fakt=1;
    for (int i=1; i<=n; i++){
        fakt = fakt*i;
    }
    cout<<n<<"!= "<<fakt<<endl;
}
int main(){
    printFactorial();
    return 0;
}

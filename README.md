#include<iostream>
using namespace std;
//each character is replace by it's next ASCII character
int main(){
    string text="";
    string encrypt;
    cout<<"Enter Desired Text:";
    cin>>text;

    for(char enc: text){
        encrypt = encrypt + char (enc +1 );
        cout<<"So, the Encrypted one is  "<<enc<<endl;
    }
}

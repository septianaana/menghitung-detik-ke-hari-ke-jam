# menghitung-detik-ke-hari-ke-jam

     #include <iostream>
     using namespace std;

    int main (){
    int jam,menit,sisa,detik;
    cout<<"berapa detik? ";
    cin>>detik;
    jam=detik/3600;
    sisa=detik%3600;
    menit=sisa/60;
    sisa=sisa%60;
    cout<<jam<<" jam "<<endl;
    cout<<menit<<" menit "<<endl;
    cout<<sisa<<" detik"<<endl;

    }
    
    
    
hasil
![img](https://github.com/septianaana/menghitung-detik-ke-hari-ke-jam/blob/master/detik.png?raw=true)

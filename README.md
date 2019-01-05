# Konversi-Waktu



                #include <iostream>
                #include <cstdlib>
                using namespace std;
                int main()

                {system ("color e");
                int jam,menit,sisa,detik;

                cout<<"|===========================================================|\n";
                cout<<"|===================   ALIF MUSTAFANAH   ===================|\n";
                cout<<"|===========  KONVERSI DETIK KE JAM, MENIT, DETIK  =========|\n";
                cout<<"|========================   PROGRAM   ======================|\n";
                cout<<"|===========================================================|\n";
                atas :
                cout<<"\nMASUKAN DETIK : ";
                cin>>detik;
                jam=detik/3600;
                sisa=detik%3600;
                menit=sisa/60;
                sisa=sisa%60;
                cout<<jam<<" jam "<<endl;
                cout<<menit<<" menit "<<endl;
                cout<<sisa<<" detik"<<endl;

                char LG;
                cout<<"\n \n\n Apakah anda ingin mengulang program ini kembali [ Y/T ] ?";cin>>LG;
                if (LG=='Y' || LG=='y') goto atas;
                else if (LG=='T' || LG=='t') goto x;
                x:
                cout<<"\n|========================================================|";
                cout<<"\n||||||  TERIMAKASIH SUDAH MENGGUANAKAN PROGRAM INI   |||||";
                cout<<"\n|||||||||||||||||    ALIF MUSTAFANAH    ||||||||||||||||||";
                cout<<"\n|||||||||||||||||  PRESS ENTER TO EXIT  ||||||||||||||||||\n";
                return 0;

                }

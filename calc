#include<iostream>
#include<math.h>
#include<cstdlib>
using namespace std;

int main()
{
    int scelta; //variabili calcolatrice
    int numero1;
    int numero2;
    int resto;
    float risultato; //float per i numeri grandi
    char operazione; //char per lo switch

        do //inizio del ciclo do-while
            {
                system("cls"); //pulisce schermata (reset program)
                cout<<" :::::::::::::::::::::::"<<endl;
                cout<<" :: Created By SteMac ::"<<endl;
                cout<<" :::::::::::::::::::::::"<<endl;
                cout<<" :: 1.CALCOLATRICE"<<endl;
                cout<<" :: 2.coming soon"<<endl;
                cout<<" :: 3.coming soon"<<endl;
                cout<<" :: 4.ESCI"<<endl;
                cout<<" :: > "; cin>>scelta;

                    if (scelta==1)
                        cout<<"Inserisci operazione (num1 segno num2)"<<endl;
                        cout<<" :: > "; cin>>numero1>>operazione >>numero2;
                    switch (operazione) //in base alla operazione scelta fa o + o - o * o /
                        {
                            case '+':
                            risultato=numero1+numero2;
                            cout<<"\n"<<" :: "<<numero1<<"+"<<numero2<<"="<<risultato<<"\n\n"<<" :: Premi un tasto";
                            system("pause>nul");
                            break;
                            case '-':
                            risultato=numero1-numero2;
                            cout<<"\n"<<" :: "<<numero1<<"-"<<numero2<<"="<<risultato<<"\n\n"<<" :: Premi un tasto";
                            system("pause>nul");
                            break;
                            case '*':
                            risultato=numero1*numero2;
                            cout<<"\n"<<" :: "<<numero1<<"*"<<numero2<<"="<<risultato<<"\n\n"<<" :: Premi un tasto";
                            system("pause>nul");
                            break;
                            case '/':
                            risultato=numero1/numero2;
                            resto=numero1%numero2;
                            cout<<"\n"<<" :: "<<numero1<<"/"<<numero2<<"="<<risultato<<"\n"<<" :: Resto: "<<resto<<"\n\n"<<" :: Premi un tasto";
                            system("pause>nul");
                            break;
                        }

            }

        while(scelta!=2);
        return 0;

}



#include <iostream>
using namespace std;
int main()
{
    int quant;
    int choice;
    // Quantity
    int Qrooms = 0, Qpasta = 0, Qburger = 0, Qnoodles = 0, Qshake = 0, Qchicken = 0;
    // food items sold
    int Srooms = 0, Spasta = 0, Sburger = 0, Snoodles = 0, Sshake = 0, Schicken = 0;
    // Total proce of items
    int Total_rooms = 0, Total_pasta = 0, Total_burger = 0, Total_noodles = 0, Total_shake = 0, Total_chicken = 0;
    cout<<"\n.........JAI SHRI KRISHNA HOTEL AND RESTAURANT..............\n";

    cout << " \n \t Quantity of items we have for Today ";
    cout << " \n Rooms avaliabe : ";
    cin >> Qrooms;
    cout << " \n Quantity of pasta : ";
    cin >> Qpasta;
    cout << " \n Quantity of burger : ";
    cin >> Qburger;
    cout << " \n Quantity of noodles : ";
    cin >> Qnoodles;
    cout << " \n Quantity of shake : ";
    cin >> Qshake;
    cout << " \n Quantity of chicken : ";
    cin >> Qchicken;
    cout<<"\n\n\t\t..............WELCOME HOW MAY I HELP YOU...........\n\n";
    cout << " \n \t \t \t Please select from the menu options ";
m:
    cout << " \n\n1 ) Rooms ";
    cout << " \n2 ) Pasta ";
    cout << " \n3 ) Burger ";
    cout << " \n4 ) Noodles ";
    cout << " \n5 ) shake ";
    cout << " \n6 ) Chicken ";
    cout << " \n7 ) Information regarding sales and collection ";
    cout << " \n8 ) Exit ";

    cout << " \n \n Please Enter your choice ! ";
    cin >> choice;

    switch (choice)
    {
    case 1:
        cout << " \n \n Enter the number of rooms you want : ";
        cin >> quant;
        if (Qrooms - Srooms >= quant)
        {

            Srooms = Srooms + quant;
            Total_rooms = Total_rooms + (quant * 1200);
            cout << " \n \n \t \t " << quant << " room / rooms have been alloted to you ! ";
        }

        else
            cout << " \n \t Only " << Qrooms - Srooms << " Rooms remaining in hotel ";
        break;

    case 2:
        cout << " \n \n Enter Pasta Quantity : ";
        cin >> quant;
        if (Qpasta - Spasta >= quant)
        {
            Spasta = Spasta + quant;
            Total_pasta = Total_pasta + (quant * 250);
            cout << " \n \n \t \t " << quant << " pasta is the order ! ";
        }
        else
        
             cout << " \n \tOnly " << Qpasta - Spasta << " pasta remaining in hotel ";
        break;

    case 3:
        cout << "  n \n Enter Burger Quantity : ";
        cin >> quant;
        if (Qburger - Sburger >= quant)
        {
            Sburger = Sburger + quant;
            Total_burger = Total_burger + (quant * 120);
            cout << " \n \n \t \t " << quant << " burger is the order ! ";
        }
        else
            cout << " \n \tOnly " << Qburger - Sburger << " burgers remaining in hotel ";
        break;

    case 4:
        cout << "  n \n Enter noodler Quantity : ";
        cin >> quant;
        if (Qnoodles - Snoodles >= quant)
        {
            Snoodles = Snoodles + quant;
            Total_noodles = Total_noodles + (quant * 250);
            cout << " \n \n \t \t " << quant << " noodler is the order ! ";
        }
        else
            cout << " \n \tOnly " << Qnoodles - Snoodles << " noodle remaining in hotel ";
        break;

    case 5:
        cout << "  n \n Enter shakes Quantity : ";
        cin >> quant;
        if (Qshake - Sshake >= quant)
        {
            Sshake = Sshake + quant;
            Total_shake = Total_shake + (quant * 250);
            cout << " \n \n \t \t " << quant << " noodler is the order ! ";
        }
        else
            cout << " \n \tOnly " << Qshake - Sshake << " shake remaining in hotel ";
        break;

    case 6:
        cout << "  n \n Enter chicken Quantity : ";
        cin >> quant;
        if (Qchicken - Schicken >= quant)
        {
            Schicken = Schicken + quant;
            Total_chicken = Total_chicken + (quant * 250);
            cout << " \n \n \t \t " << quant << " chicken is the order ! ";
        }
        else
            cout << " \n \tOnly " << Qchicken - Schicken << " chicekn remaining in hotel ";
        break;

    case 7:
        cout << "\n\t\t.............detail of collection and sales for room.............  ";
        cout << "\n\t\t  no of room we had ::    "<< Qrooms;
        cout << "\n\t\t  no of rooms we gave for rent:: "<< Srooms;
        cout << "\n\t\t  remaining rooms::"<< Qrooms - Srooms;
        cout << "\n\t\t  Total collection for the day::"<<Total_rooms;
       cout << "\n\t\t                     ";
        cout << "\n\t\t.............detail of collection and sales for pasta.............  ";
        cout << "\n\t\t  no of room we had ::    "<< Qpasta;
        cout << "\n\t\t  no of rooms we gave for rent:: "<< Spasta;
        cout << "\n\t\t  remaining rooms::"<< Qpasta - Spasta;
        cout << "\n\t\t  Total collection for the day::"<<Total_pasta ;
        cout << "\n\t\t                     ";
          cout << "\n\t\t.............detail of collection and sales for noodle.............  ";
        cout << "\n\t\t  no of we had ::    "<< Qnoodles;
        cout << "\n\t\t  no of  we gave for :"<<Snoodles;
        cout << "\n\t\t  remaining ::"<<Qnoodles-Snoodles;
        cout << "\n\t\t  Total collection for the day::"<<Total_noodles;
        cout << "\n\t\t                     ";

   case 8:
   cout<<"\nNAMASTE OR HAVE A GOOD DAY\n";
   exit(0);

   default:\
   cout<<"\n please enter valid choice\n";
    }
goto m;
}

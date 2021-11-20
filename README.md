# Lecture-10

7 stars:

    #include <iostream>
    using namespace std;

    int main()
    {
        for (int i = 1; i <= 7; i++) {
            for (int j = i; j <= 7; j++) {
                cout << "*";
            }
            cout << endl;
        }
    }
    
5 stars:

    int main()
    {
        for (int i = 1; i <= 5; i++) {
            for (int j = 1; j <= i; j++) {
                cout << "*";
            }
            cout << endl;
        }
    }
    
Rising and falling stars:

    int main()
    {
      for (int i = 1; i <= 5; i++) {
        for (int j = 1; j <= i; j++) {
          cout << "*";

        }
        cout << endl;
      }

      for (int k = 1; k <= 5; k++) {
        for (int l = k; l <= 5; l++) {
          cout << "*";
        }
        cout << endl;
      }
    }
    
Cubes:

    int main()
    {
        int i, j;
        cout << "please enter a number:" << endl;
        cin >>j;

        while (cin.fail()) {
            cin.clear();
            cin.ignore(1000, '\n');
            cout << "Please enter a valid number:" << endl;
            cin >> j;
        }

        for (i = 1; i <= j; i++) {
            cout << "\n" << "The cube of a number:" << i << " " << i * i * i;
        }
        cout << endl;
    }   
    
Find the nine's:

    int main()
    {
        int sum = 0;
        for (int x = 100; x <= 200; x++) {
            if (x % 9 == 0) {
                cout << "\nNumber is:" << x << endl;
                sum = sum + x;
            }
            cout << "This sum is " << sum << endl;
        }
    }

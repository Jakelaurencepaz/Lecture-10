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


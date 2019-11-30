    #include <iostream>

    using namespace std;

    int main()
    {
        int x = 1, y = 2, z;
        int evensum = 0;
        while(y < 4000000){
            if(y % 2 == 0){
                evensum += y;
            }
            z = x;
            x = y;
            y += z;
        }
        cout << evensum;
        return 0;
    }

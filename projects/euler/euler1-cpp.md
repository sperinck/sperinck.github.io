    #include <iostream>

    using namespace std;

    int main()
    {
        int sum = 0;
        int n = 1;
        while(n < 1000){
            if(n % 3 == 0 | n % 5 == 0){
                sum += n;
            }
            n++;
        }
        cout << sum;
        return 0;
    }

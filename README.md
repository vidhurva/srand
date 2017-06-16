// C++ Program that uses time libraries to create random numbers
// Notes: seed = the number(s) used to generate random numbers
   
   #include <iostream>
   #include <ctime> // MUST USE TIME LIBRARY TO USE srand(time(NULL))
   #include <cstdlib>
   using namespace std;
   
   int main()
  {
          int i;
  
          srand(time(NULL)); // By adding NULL, the seed of the random number ge    nerator corresponds to the current time
          for(int i =1; i <= 10; i++)
                  cout << rand() << endl;
  
  return 0;
  }
             

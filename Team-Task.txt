#include <iostream>
#include <string.h>
using namespace std;
int count = 0, ansque = 0;
void question1()
{
    int solu1;
    std::cout << endl
              << "  Question 1" << endl
              << endl;
    std::cout << "  What is a correct syntax to output \"Hello World\" in C++?" << endl;
    std::cout << "\t1. Console.WriteLine(\"Hello World\");" << endl;
    std::cout << "\t2. cout<<\"Hello World\";" << endl;
    std::cout << "\t3. System.out.println(\"Hello World\");" << endl;
    std::cout << "\t4. print(\"Hello World\");" << endl;
    std::cout << "\n  What is ur answer? ";
    std::cin >> solu1;
    if (solu1 == 2)
    {
        count += 10;
        ansque++;
    }
}
void question2()
{
    int solu2;
    std::cout << endl
              << "  Question 2" << endl
              << endl;
    std::cout << "  Which data type is used to create a variable that should store text?" << endl;
    std::cout << "\t1. myString" << endl;
    std::cout << "\t2. Txt" << endl;
    std::cout << "\t3. String" << endl;
    std::cout << "\t4. string" << endl;
    std::cout << "\n  What is ur answer? ";
    std::cin >> solu2;
    if (solu2 == 4)
    {
        count += 10;
        ansque += 1;
    }
}
void question3()
{
    int solu3;
    std::cout << endl
              << "  Question 3" << endl
              << endl;
    std::cout << "  How do you create a variable with the numeric value 5?" << endl;
    std::cout << "\t1. int x = 5;" << endl;
    std::cout << "\t2. x = 5;" << endl;
    std::cout << "\t3. num x = 5;" << endl;
    std::cout << "\t4. double x = 5;" << endl;
    std::cout << "\n  What is ur answer? ";
    std::cin >> solu3;
    if (solu3 == 1)
    {
        count += 10;
        ansque += 1;
    }
}
void question4()
{
    int solu4;
    std::cout << endl
              << "  Question 4" << endl
              << endl;
    std::cout << "  Which method can be used to find the length of a string?" << endl;
    std::cout << "\t1. len()" << endl;
    std::cout << "\t2. getLength()" << endl;
    std::cout << "\t3. getSize()" << endl;
    std::cout << "\t4. length()" << endl;
    std::cout << "\n  What is ur answer? ";
    std::cin >> solu4;
    if (solu4 == 4)
    {
        count += 10;
        ansque += 1;
    }
}
void question5()
{
    int solu5;
    std::cout << endl
              << "  Question 5" << endl
              << endl;
    std::cout << "  Which header file lets us work with input and output objects?" << endl;
    std::cout << "\t1. #include <inputstr>" << endl;
    std::cout << "\t2. #include <iosstring>" << endl;
    std::cout << "\t3. #include <iostream>" << endl;
    std::cout << "\t4. #include <stream>" << endl;
    std::cout << "\n  What is ur answer? ";
    std::cin >> solu5;
    if (solu5 == 3)
    {
        count += 10;
        ansque += 1;
    }
}
void question6()
{
    int solu6;
    std::cout << endl
              << "  Question 6" << endl
              << endl;
    std::cout << "  Which operator can be used to compare two values?" << endl;
    std::cout << "\t1. == " << endl;
    std::cout << "\t2. ><" << endl;
    std::cout << "\t3. <>" << endl;
    std::cout << "\t4. =" << endl;
    std::cout << "\n  What is ur answer? ";
    std::cin >> solu6;
    if (solu6 == 1)
    {
        count += 10;
        ansque += 1;
    }
}
void question7()
{
    int solu7;
    std::cout << endl
              << "  Question 7" << endl
              << endl;
    std::cout << "  What is the correct way to create an object called myObj of MyClass?" << endl;
    std::cout << "\t1. class MyClass = new myObj();" << endl;
    std::cout << "\t2. new myObj = MyClass();" << endl;
    std::cout << "\t3. class myObj = new MyClass();" << endl;
    std::cout << "\t4. MyClass myObj;" << endl;
    std::cout << "\n  What is ur answer? ";
    std::cin >> solu7;
    if (solu7 == 4)
    {
        count += 10;
        ansque += 1;
    }
}
void question8()
{
    int solu8;
    std::cout << endl
              << "  Question 8" << endl
              << endl;
    std::cout << "  Which method can be used to find the highest value of x and y?" << endl;
    std::cout << "\t1. maximum(x,y)" << endl;
    std::cout << "\t2. max(x,y)" << endl;
    std::cout << "\t3. maxNum(x,y)" << endl;
    std::cout << "\t4. largest(x,y)" << endl;
    std::cout << "\n  What is ur answer? ";
    std::cin >> solu8;
    if (solu8 == 2)
    {
        count += 10;
        ansque += 1;
    }
}
void question9()
{
    int solu9;
    std::cout << endl
              << "  Question 9" << endl
              << endl;
    std::cout << "  Which operator is used to multiply numbers?" << endl;
    std::cout << "\t1. *" << endl;
    std::cout << "\t2. %" << endl;
    std::cout << "\t3. x" << endl;
    std::cout << "\t4. #" << endl;
    std::cout << "\n  What is ur answer? ";
    std::cin >> solu9;
    if (solu9 == 1)
    {
        count += 10;
        ansque += 1;
    }
}
void question10()
{
    int solu10;
    std::cout << endl
              << "  Question 10" << endl
              << endl;
    std::cout << "  How do you create a reference variable of an existing variable?" << endl;
    std::cout << "\t1. With the ref word" << endl;
    std::cout << "\t2. With the * operator" << endl;
    std::cout << "\t3. With the & operator" << endl;
    std::cout << "\t4. With the REF word" << endl;
    std::cout << "\n  What is ur answer? ";
    std::cin >> solu10;
    if (solu10 == 3)
    {
        count += 10;
        ansque += 1;
    }
}
void solut()
{
}
int main()
{
    char solu[10];
    char answery[] = "yes";
    std::cout << "\n  Quiz" << endl;
    std::cout << "\n  NOTE:\n  1. Enter your answer in number which corresponds to respective option\n";
    question1();
    question2();
    question3();
    question4();
    question5();
    question6();
    question7();
    question8();
    question9();
    question10();
    std::cout << endl
              << "  You have answered " << ansque << " out of 10 questions";
    std::cout << endl
              << "  The total score is " << count << " out of 100";
    std::cout << endl
              << "  If you need solutions for the above questions(yes/no): ";
    std::cin >> solu;
    if (strcmp(solu, answery) == 0)
    {
        cout << endl;
        std::cout << "  Solutions for the above questions" << endl;
        std::cout << "\n  Question 1\n  1. Console.WriteLine(\"Hello World\");" << endl;
        std::cout << "\n  Question 2\n  4. string" << endl;
        std::cout << "\n  Question 3\n  1. int x = 5;" << endl;
        std::cout << "\n  Question 4\n  4. length()" << endl;
        std::cout << "\n  Question 5\n  3. #include <iostream>" << endl;
        std::cout << "\n  Question 6\n  1. == " << endl;
        std::cout << "\n  Question 7\n  4. MyClass myObj;" << endl;
        std::cout << "\n  Question 8\n  2. max(x,y)" << endl;
        std::cout << "\n  Question 9\n  1. *" << endl;
        std::cout << "\n  Question 10\n  3. With the & operator" << endl;
        cout << "\n  Thankyou";
    }
    else
    {
        cout << "\n  Thankyou" << endl;
    }
    return 0;
}

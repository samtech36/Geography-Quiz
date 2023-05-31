#include "stdio.h"
#include <iostream>

using namespace std;


int main()
{
//Here's the grography quiz. Good luck students. 
  char ans;
  int correct  = 0;
  int incorrect = 0;
  int results; 

  cout << "Question #1: In which continent you could find the Ganges River? \n A)Africa B)Asia C)Europe D)The Americas \n" << endl;

  cout << "Enter your answer below: ";
  cin >> ans;

  if (ans == 'B' || ans == 'b')
  {
    cout << "Your answer is correct \n";
    correct++;
  }
  else
  {
    cout << "Your answer is incorrect \n";
    incorrect++;
  }
  cout << "Question #2: what is the smallest continent on Earth? \n A)Europe B)North America C)Antartica D)Australia \n";
  cout << "Enter your answer below: ";
  cin >> ans;

  if (ans == 'C' || ans == 'c')
  {
    cout << "Your answer is correct \n";
    correct++;
  }
  else
	{
		cout << "Your answer is incorrect \n";
		incorrect++;
	}
	cout << "Question #3: In what city can you see The Leaning Tower? \n A)Rome B)Vienna C)Pisa D)Madrid \n" << endl;


	cout << "Enter your answer below: ";
	cin >> ans;

	if (ans == 'A' || ans == 'a')
	{
		cout << "Your answer is correct \n";
		correct++;
	}
	else
	{
		cout << "Your answer is incorrect \n";
		incorrect++;
	}
	cout << "Question #4: In which country is 'Khmer' the official language? \n A) Cambodia B) Thailand C) Laos D) Vietnam \n";

	cout << "Enter your answer below: ";
	cin >> ans;

	if (ans == 'A' || ans == 'a')
	{
		cout << "Your answer is correct \n";
		correct++;
	}
	else
	{
		cout << "Your answer is incorrect \n";
		incorrect++;
	}
	cout << "Question #5: What river is important to people in India for worship? \n A) Padma River B) Ganges River C) Irawaddy River D) Jamuna River \n";

	cout << "Enter your answer below: ";
	cin >> ans;

	if (ans == 'B' || ans == 'b')
	{
		cout << "Your answer is correct \n";
		correct++;
	}
	else
	{
		cout << "Your answer is incorrect \n";
		incorrect++;
	}
	cout << "Question #6: what is known as the 'Honeymoon Capital' of the world? \n A) London B) San Francisco C) Paris D) Yellowstone National Park \n";

	cout << "Enter your answer below: ";
	cin >> ans;

	if (ans == 'C' || ans == 'c')
	{
		cout << "Your answer is correct \n";
		correct++;
	}
	else
	{
		cout << "Your answer is incorrect \n";
		incorrect++;
	}
	cout << "Question #7: In what continent is Albania situated? \n A)Europe B)Africa C)South America D)Asia \n";

	cout << "Enter your answer below: ";
	cin >> ans;

	if (ans == 'A' || ans == 'a')
	{
		cout << "Your answer is correct \n";
		correct++;
	}
	else
	{
		cout << "Your answer is incorrect \n";
		incorrect++;
	}
	cout << "Question 8: What country touches the Indian Ocean, the Arabian Sea, and the Bay of Bengal? \n A)The Maldives B)India C)Sri Lanka D)Mynamar \n";

	cout << "Enter your answer below: ";
	cin >> ans;

	if (ans == 'B' || ans == 'b')
	{

		cout << "Your answer is correct \n";
		correct++;
	}
	else
	{
		cout << "Your answer is incorrect \n";
		incorrect++;

	}
	cout << "Question 9: What's the world's smallest country? \n A)San Marino B)Malta C)Barbados D)Vatican City \n";

	cout << "Enter your answer below: ";
	cin >> ans;

	if (ans == 'D' || ans == 'd')
	{

		cout << "Your answer is correct \n";
		correct++;
	}
	else
	{
		cout << "Your answer is incorrect \n";
		incorrect++;

	}
	cout << "Question 10: Which country has the lowest elevation in the world? \n A)The Maldives B)Qatar C)The Netherlands D)Denmark \n";

	cout << "Enter your answer below: ";
	cin >> ans;


	if (ans == 'A' || ans == 'a')
	{

		cout << "Your answer is correct \n";
		correct++;
	}
	else
	{
		cout << "Your answer is incorrect \n";
		incorrect++;

	}
	cout << "You got " << correct << " out of " << 10 << " correct " << endl;

	//This Geography Quiz counts as 20% of your grade. This will be graded out of 20 points.
	double number1, result;

  cout << "Enter the questions you got right: ";
  cin >> number1;

  result = number1 / 10 * 20;
  cout << "Result = " << result << endl;

//In order to get your actual grade, convert your quiz grade into percentage.  
  double points, percentage;

  cout << "Enter your result and convert it into percentage to get your actual grade: ";
  cin >> points;

  percentage = result / 20 * 100;
  cout << " You got " << percentage << " % on your quiz " << endl;

//Since some of you did extra credit for homework, I'll add that into your quiz grade. Type 'N' after it shows "your total quiz grade is:".
    int grade1, grade2;
    double total;
    char again;
    
    do {
        cout << "Enter your quiz and extra credit points towards your homework \n";
        cin >> grade1 >> grade2;
        
        total = (grade1 + grade2);
        
        cout << "Your total quiz grade is: " << total << "\n";
        cin >> again;
    } while (again == 'Y' || again == 'y'); 



//Find out what letter grade you got on the quiz


char quizgrade;
cout << "Enter your quiz result for your letter grade:" << endl;
cin >> results;
if (result >= 90)
quizgrade = 'a';
if (result >= 80)
quizgrade = 'b';
if (result >= 70)
quizgrade = 'c';
if (result >= 60)
quizgrade = 'd';
else
quizgrade = 'f';
cout << quizgrade << endl;
switch (quizgrade) {
  case 'a':
  cout << "Excellent job" << endl;
  break;
  case 'b':
  cout << "Fair job" << endl;
  break;
  case 'c':
  cout << "Fair job" << endl;
  break;
  case 'd':
  cout << "Good but try to improve" << endl;
  break;
  case 'f':
  cout << "You fail the quiz. Do it better next time" << endl;
}




//Average what quiz grade the geography class got.
	int student;
    int sum = 0;
    int input;
    double avg;


		cout << ("Enter the number of students:");
		cin >> student;

    while (student < 21){
      break;
    }
		
    for (int i = 0; i < student; i++) {
			cout << ("Enter the quiz grade per student and average the rest: \n ");
			cin >> input;
            sum += input;

    avg = sum / student;
    	}

		cout << ("The quiz average for the whole class is: ") <<  avg << (" % "); 
    return 0;
}

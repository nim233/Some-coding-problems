                //checking \n feature and endl feature

using namespace std;

#include<conio.h>

int main()

{

	cout<<"The works of wolfgang\ninclude the following";	

       cout<<"\nThe Turkish March"<<endl;

	cout<<"and symphony no 40";

	cout<<"in G minor"<<endl;





getch();

return 0;

}

                            ------------------------------------------------------------

#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

	cout<<"success\n";

	cout<<"success\n\n";     //double space come when we use \n two times

	cout<<"success";





getch();

return 0;

}



                               ------------------------------------------------------

#include<iostream>
using namespace std;                      //checking varible and finding current balance
#include<conio.h>
int main()
{
	int starting_balance;
	int depositMade;
	int Withdrawlamount;
	int monthlyinterestrate;
	int current_balance;
	
	cout<<"starting balance"<<'\n';
	cin>>starting_balance;
	
	cout<<"deposit made"<<"\n";
	cin>>depositMade;
	
	cout<<"total withdraw amount"<<'\n';
	cin>>Withdrawlamount;
	
	cout<<"monthly interest rate"<<'\n';
	cin>>monthlyinterestrate;
	
	current_balance=starting_balance-depositMade-Withdrawlamount-monthlyinterestrate;
	
	cout<<"current balance\n"<<current_balance<<'\n';
	
	getch();
	return 0;
                                          --------------------------------------

}#include<iostream>
using namespace std;                      //checking varible and finding current balance
#include<conio.h>
int main()
{
	int starting_balance;
	int depositMade;
	int Withdrawlamount;
	int monthlyinterestrate;
	int current_balance;
	
	cout<<"starting balance"<<'\n';
	cin>>starting_balance;
	
	cout<<"deposit made"<<"\n";
	cin>>depositMade;
	
	cout<<"total withdraw amount"<<'\n';
	cin>>Withdrawlamount;
	
	cout<<"monthly interest rate"<<'\n';
	cin>>monthlyinterestrate;
	
	current_balance=starting_balance-depositMade-Withdrawlamount-monthlyinterestrate;
	
	cout<<"current balance\n"<<current_balance<<'\n';
	
	getch();
	return 0;
}
                                    --------------------------------------------

using namespace std;
#include<conio.h>
int main()
{
	cout<<"one\ntwo\nthree\n";


getch();
return 0;
                                             -----------------------------------------
}#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	int R;
	int ST;                     //finding sales tax
	int Q;
	int Y;
	int T;
	
	
	cout<<"retail price of the item being purchased"<<endl;
	cin>>R;
	
	cout<<"sales tax rate"<<endl;
	cin>>ST;
	
	cout<<"no of items"<<endl;
	cin>>Q;
	
	Y=R*ST;
	T=Q*R;
	
	cout<<"sales tax of the purchase"<<Y<<'\n';
	cout<<"total of the sale"<<T<<'\n';
	
	getch();
	return 0;
}
                              ------------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()                                    //cheking the datatype
{
	int checking;                       
	unsigned int miles;
	long diameter;
	
	checking=-20;
	miles=4276;
	diameter=10000L;
	
	cout<<"we have made a long journey of"<<miles;
	cout<<"miles\n";
	cout<<"our checking account balance"<<checking;
	cout<<"\nThe galaxy is about"<<diameter;
	cout<<"light years in diameter";
	return 0;
}
                                       ---------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()                                    //ch 1 33 by tony gaddzin
{
	int x;
	int y;
	int Y;
	
	x=0;
	y=5;
	
	x=1;
	y=6;
	
	Y=x+y;
	
	cout<<"Y\n"<<Y<<'\n';


getch();
return 0;
}
                                      -----------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	int j,k,l;
	 
	 j=10;
	 k=2;
	 l=4;
	 
	 j=j*k;
	 l=k*l;
	 
	 k=j+l;
	 
	 cout<<"k"<<k<<endl;


getch();
return 0;
}
                                              ----------------------------------------------#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	int a,b,c,x;
	a=1;
	b=10;               //35q
	c=100;
	x=0;
	x=3*c;
	x=x+6*b;
	x=x+5*a;
	
	cout<<"x"<<x<<endl;


getch();
return 0;
}
                                       --------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	char letter;
	letter=65;
	cout<<letter<<endl;      /*mtlab ka agar ham ASCII code likhte to wo ch ko print kr da ga
	                            bt agar ham ch likhte to b direct ch ko hi display kary ga
	                            printable ch are internally stored by numeric codes*/
	letter=66;
	cout<<letter<<endl;
	letter=67;
	cout<<letter<<endl;;


getch();
return 0;

}
                         --------------------------------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
#include<string.h>
int main()
{                                  /*here the concept in the memory there is also a null character as\0
                                     means in the case A ,it uses 2 bytes of memory .bt if we have to use ch 
                                     then null character is not used by default and it uses 1 byte of memory*/
      string st;
      st="A";
      cout<<st<<"\n";	


getch();
return 0;
}
                                    ----------------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	char first;    //make variable ch variable first ,middle and last ,and store ur initialz
	first='N';
	char middle;
	middle='M';
	char last;
	last='H';
	cout<<first<<endl;
	cout<<middle<<endl;
	cout<<last<<endl;


getch();
return 0;
}
                                          -----------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
#include<string.h>
int main()
{                                               //string  type
	string name;
	name="Jia";
	string adress;
	adress="pak housing scheme,sector K,landikotal";
	string number;
	number="0324-6543245";
	cout<<"name\n"<<name<<endl;
	cout<<"adress\n"<<adress<<endl;
	cout<<"number\n"<<number<<endl;
	


getch();
return 0;
}
                                   ----------------------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	float distance;
	double mass;
	
	distance=1.495979E11;
	mass=1.989E30;
	cout<<"The sun is"<<distance<<"meters away\n";
	cout<<"sun's mass is "<<mass<<"kilograms\n";


getch();
return 0;
}
                                             ----------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	int i;
	float f;
	f=3.96;               //assigning floating point values to integer varable
	i=f;
	cout<<i<<endl;

                    //diff between float and double is in float 1.23 and in double ,1.2345678 with more precison
getch();
return 0;

}
                                        --------------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{                                   //booltype
	bool boolvalue;
	boolvalue=true;
	cout<<boolvalue<<'\n';
	boolvalue=false;
	cout<<boolvalue<<'\n';
	
getch();
return 0;
}
                                    ------------------------------------------------------------------💻
#include<iostream>
using namespace std;
#include<conio.h>
int main()                  //determing the size of the datatype
{
	long double apple;
	
	cout<<"The size of int"<<sizeof(int)<<"bytes\n";
	cout<<"The size of double"<<sizeof(double)<<"bytes\n";
	cout<<"An apple can be eaten in"<<sizeof(apple)<<"bytes\n";
	


getch();
return 0;
}
                                    ------------------------------------------------------------------------💻
#include<iostream>
using namespace std;
#include<conio.h>

int main()
{                                                /*using the auto keyword ,,but in simple programs
                                                  it is prefferred not to use this autokeyword,but it is used
                                                  in complex problems,where it needed*/
                                                   
	auto interest_rate=12.9;             //ksi line ko program ma comment krne ka liye ctrl slash use krte
	
	auto stock_code='D';
	auto customer_number=459L;
	cout<<interest_rate<<'\n';
	cout<<stock_code<<'\n';
	cout<<customer_number<<'\n';


getch();
return 0;
}
                                         --------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	int zoo{6};           /*it will print 6 simply,but if we use 6.9 ,it will also show 6..but
	                        as we have used bracket ,then it will give the warning to chnge frm duble to
	                        int in the bracket*/
	cout<<zoo<<'\n';


getch();
return 0;
}
                                       -----------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    double regular_hourwages;
    int total_regularhours=40;
    double perhour_regularwages=18.25;
    double overtime_wages;
    int total_overtimehours=10;
    double perhour_overtimewages=27.78;
    double totalwages;
    
    //calaculation	
      regular_hourwages=total_regularhours*perhour_regularwages;
      overtime_wages= total_overtimehours*perhour_overtimewages;
      totalwages=regular_hourwages+overtime_wages;
      
      cout<<"total wages"<<totalwages<<'\n';

getch();
return 0;
}
                                           ----------------------------------------------
/*suppose you earn money $6,000 per month and you are allowed to contribute a portion of your gross monthly
pay to a retirement plan.you want to determine the amount of your pay that will go into the plan if you contribute
5 percent,7 percent,10 percent of your gross wages.*/




#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	int monthly_pay=6000;
	 int contribution;
	
	//calculate the 5%
	
	contribution=monthly_pay*0.05;
	cout<<"5% is $"<<contribution<<"per month\n";
	
	//claculate 7%
	
	contribution=monthly_pay*0.07;
	cout<<"7% is $"<<contribution<<"per month\n";
	
	//calculate 10% 
	contribution=monthly_pay*0.1;
	cout<<"10% is $"<<contribution<<"per month\n";
	
return 0;
	

}
                                    ---------------------------------------------------------------
/*A retail business sells an item that is regularly priced at $59.95,is planning to have a sale where the items
price will be reduced to 20%....actually means the discount is 20%,now we have to find the 20% of regularly priced
 discount/we have been asked to write a program to calcultes the sale price of the item*/




#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	double regularPrice=59.95,discount,salePrice;
	
	//finding the discount
	discount=regularPrice*0.2;
	
	//finding sale price
	salePrice=regularPrice-discount;
	
	cout<<"regular price is"<<regularPrice<<'\n';
	cout<<"discount"<<discount<<'\n';
	cout<<"sale Price"<<salePrice<<'\n';
	
return 0;
	
}

                                                  ----------------------------------------------------
//program extracts the rightmostdigit of the number...

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	int number;
	number=12345;              //modulud operator  finding remainder
	int rightmost;
	
	rightmost=number%10;
	cout<<"rightmost\n"<<rightmost<<'\n';


getch();
return 0;
}
                                                --------------------------------------------------
//convert 125 seconds to equivalent number of minutes and seconds


#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	int totalseconds=125;
	int minutes,seconds;
	
	minutes=totalseconds/60;      //divide by 60 bcoz we are converting from sec to mint,while
	                              //in one miute there are 60 seconds=1*60
	cout<<"minutes"<<minutes<<'\n';
	
	seconds=totalseconds%60;
	cout<<"seconds"<<seconds<<'\n';


getch();
return 0;
}
                                              -----------------------------------------
//this program calculates the circumference of the circle

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{                                       /*we can change the const double DIAMETER=10.0 to const double DIAMETER=12.0
                                          ,bt it should recompiled again ....means replace itwith new const,if we
                                          use two contant it would give an error*/
	const double PI=3.14159;
	const double DIAMETER=10.0;
	double circumference;
	 
	//calculation
	circumference=PI*DIAMETER;
	
	cout<<"circumference"<<circumference<<'\n';

           // const double DIAMETER=12.0;
           // circumference=PI*DIAMETER;
           // cout<<"circumference"<<circumference<<'\n';

getch();
return 0;
}
                                      --------------------------------------------------------
 #include<iostream>

using namespace std;

#include<conio.h>





int glo=6;

void sum()

{

	int a=4;

	cout<<glo;                /*global variable and local variables can made with the same as

	                          in this program ,but prefernce is on local variable'local var is made 

	                          inside the function,while that of global var is made out side the function,,

	                          global var can be assecd at any where in the program while local var only 

	                          in the function where it is made,,,first of all the value of a, b is printed

			    then function is called,cursor move to the sum function,chk,there made any

	                       local var ,if not then global var and get the reslt 6 ,while after the cout<<glo 

		            is called ,it also first chk out there is nay local var ,yes there is local var,

			        whose value is changed 56 to 78,and the value orinted will be 78*/ 

}

int main()

{

	int glo=56;

	glo=78;

	int a=5;

	int b=8;

	cout<<"values of a is"<<a<<'\n';

	cout<<"value of b is"<<b<<'\n';

	sum();

	cout<<'\n'<<glo;

	





getch();

return 0;

       }

                                 ------------------------------------------------------------------------------

#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

    cout<<"two mandolins like creatures in the\n\n\n";   //two blank lines btwn each line of text

    cout<<"dark\n\n\n";

    cout<<"creating the agony of\n\n\n";

    cout<<"george barker";

    return 0;

    }

                                         -----------------------------------------------------------

#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

    int freeze =32 ,boil =212;



    freeze =0;

    boil = 100;

    cout<<freeze<<endl<<boil<<endl;

    return 0;

}

                         -----------------------------------------------------------------------



#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

    int speed=20;

    int time=10;

    int distance;

    //calculation

    distance=speed*time;

    cout<<"distance\n"<<distance<<endl;

}

                                   -----------------------------------------------------------

#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

    double force=172.5;

    double area=27.5;

    double pressure;

    //calculation

    pressure=force/area;

    cout<<"pressure\n"<<pressure<<endl;

}

                                  -----------------------------------------------------

#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

    int x=0,y=2;

    x=y*4;

    cout<<x<<endl<<y<<endl;

    return 0;

}

                                               -------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    int a,x=23;
    a=x%4;
    cout<<x<<endl<<a<<endl;
    return 0;
}
                                    ------------------------------------------------------------------
//programming challenges chapter 2 q1

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
     int a=50;
    int b=100;
    double total;
    //calculation
    total=a+b;
    cout<<"total\n"<<total<<endl;
}
                                  -------------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
   double totalSalesOfTheYear=8600000;
   double percentoftotalsales=0.58;
   double EastCostDivision;
   //calculation
   EastCostDivision=totalSalesOfTheYear*percentoftotalsales;

   cout<<EastCostDivision<<endl;

   return 0;
}
                              ----------------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    double totalpurchase=95;
    double state_salestax=0.04;
    double fourper;
    double country_salestax=0.02;
    double twoper;
    double total_salestax;

    //calculation

    fourper=totalpurchase*state_salestax;
    twoper=totalpurchase*country_salestax;     
    total_salestax=fourper+twoper;

    
    cout<<fourper<<endl;
    cout<<twoper<<endl;
    cout<<total_salestax<<endl;


   return 0;
}
                                ------------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    double mealcharge=88.67;
    cout<<mealcharge<<endl;
    double taxformealcharge=0.0675;
    double tipformealcharge=0.1325;
    double tax;
    double tip;
    double totalbill;

    //calculation

    tax=mealcharge*taxformealcharge;
    tip=(tax+mealcharge)*tipformealcharge;     //in github repository ,this error is not corrected!be aware when next time using
    totalbill=mealcharge+tax+tip;


    cout<<tax<<endl;
    cout<<tip<<endl;igf
    cout<<totalbill<<endl;


   return 0;
}
                                ----------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    double a=28;
    double b=32;
    double c=37;
    double d=24;
    double e=33;
    double  sum;
    double avrg;

    //calculation
          sum=a+b+c+d+e;
          cout<<"sum\n"<<sum<<endl;
           avrg=sum/5;
           cout<<"avrg\n"<<avrg<<endl;


   return 0;
}
                              -----------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    double payAmount=2200.0;
    double payPeriods=26;
    double annualpay;

    //calculation
          annualpay=payAmount*payPeriods;
          cout<<"annualpay\n"<<annualpay<<endl;


   return 0;
}
                             ------------------------------------------------------

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    double currentlyoceanlevel=1.5;
    double fivyears;
    double sevyears;
    double tenyears;

    //calculation
          fivyears=currentlyoceanlevel*5;

          sevyears=currentlyoceanlevel*7;

          tenyears=currentlyoceanlevel*10;
    //cout statements

    cout<<"fivyears\n"<<fivyears<<"mm"<<endl;
    cout<<"sevyears\n"<<sevyears<<"mm"<<endl;
    cout<<"tenyears\n"<<tenyears<<"mm"<<endl;


   return 0;
}
                                  -----------------------------------------------------

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    double priceofitem1=15.95;
    cout<<"$"<<priceofitem1<<endl;
    double priceofitem2=24.95;
    cout<<"$"<<priceofitem2<<endl;
    double priceofitem3=6.95;
    cout<<"$"<<priceofitem3<<endl;
    double priceofitem4=12.95;
    cout<<"$"<<priceofitem4<<endl;
    double priceofitem5=3.95;
    cout<<"$"<<priceofitem5<<endl;
    double subtotal;

    //calculation
    subtotal=priceofitem1+priceofitem2+priceofitem3+priceofitem4+priceofitem5;
    cout<<"subtotal\n"<<subtotal<<endl;

    //amount of sales tax,assume sale tax is 7%
    double salestax=0.07;
    double tax;
   //calculation
    tax=salestax*subtotal;
    cout<<tax<<endl;

   double total;
    total=tax+subtotal;
    cout<<total<<endl;



   return 0;
}
                                      --------------------------------------------------------

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    cout<<"The size of an integer is"<<sizeof(int)<<"bytes\n";
    cout<<"The size of the char is"<<sizeof(char)<<"bytes\n";
    cout<<"The size of the float is"<<sizeof(float)<<"bytes\n";
    cout<<"The size of the double is"<<sizeof(double)<<"bytes\n";
   return 0;
}
                                   -----------------------------------------------------------

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    int gallonsofgasused=15;
    int milesdriven=375;
    int MPG;

    MPG=milesdriven/gallonsofgasused;

    cout<<"miles per gallons"<<MPG<<endl;
   return 0;
}
                              ------------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
 int noofgallons=20;
 double av1=23.5;
 double av2=28.9;
 
 double distance;
     distance=noofgallons*av1;
     cout<<"distance\n"<<distance<<endl;
 
 distance=noofgallons*av2;
 cout<<"distance\n"<<distance<<endl;


    getch();
    return 0;
}
                                 -------------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
 //one acre land=43560
  
  double track_land=391876;
  double no_ofacres;
  double sqfeet_inoneacre=43560;

  no_ofacres=track_land/sqfeet_inoneacre;
  cout<<no_ofacres<<endl;


    getch();
    return 0;
}
                                            ---------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
 double costs_electronics=14.95;
 int per_profit=35;
 double selling_price;

 selling_price=costs_electronics+costs_electronics*0.35;

 cout<<"************selling price**************\n";
 cout<<selling_price<<endl;
    getch();
    return 0;
}
                                   --------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
 cout<<"********jia**********\n";
 cout<<"********21-k,town,ghujranawla,2043*********\n";
 cout<<"*********0234-5667898**********\n";
 cout<<"***********programmingmajor***********";
    getch();
    return 0;
}
                                    --------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
 cout<<"   *\n";
 cout<<"  ***\n";
 cout<<" *****\n";
 cout<<"*******\n";
    return 0;
}
                             ---------------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
 cout<<"   *\n";
 cout<<"  ***\n";
 cout<<" *****\n";
 cout<<"*******\n";
 cout<<" *****\n";
 cout<<"  ***\n";
 cout<<"   *\n";
    return 0;
}
                             ------------------------------------------------------------------

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
 int total_shares=750;
 double stock_price=35;
 doube paidAmount_withcommission;
 double commission_fortransection=0.02;
 double total_Amount;

 //calculation
  paidAmount_withoutcommission=total_shares*stock_price;
  paidAmount_withcommission=paidAmount_withoutcommission*commission_fortransection;
  total_Amount=paidAmount_withoutcommission+paidAmount_withcommission;

  //cout statements
  cout<<"****paidAmount_withoutcommission******\n"<<paidAmount_withoutcommission<<endl;
  cout<<"****paidAmount_withcommission****\n"<<paidAmount_withcommission<<endl;
  cout<<"****total_Amount****\n"<<total_Amount<<endl;
return 0;
}
                               ---------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
   double total_customers=16500;
   double oneormore_energydrinks=0.15;
   double citrusflavoured_energydrinks=0.58;
   double firstsurvey;
   double secsurvey;

   //calculation
   firstsurvey=total_customers*oneormore_energydrinks;
   secsurvey=firstsurvey*citrusflavoured_energydrinks;

   //cout statements
   cout<<"*****firstsurvey*****\n"<<firstsurvey<<endl;
   cout<<"*****secsurvey******\n"<<secsurvey<<endl;
    return 0;
}
                                  --------------------------------------------------------------
//Annual High Temperature

#include<iostream>

using namespace std;



int main()

{

	int NewYork=85;
	int Denver=88;
	int Phoenix=106;

	double NewYork_Temp;
	double Denver_Temp;
	double Phoenix_Temp;

	
           //calculation
	NewYork_Temp=NewYork*0.02;
	Denver_Temp=Denver*0.02;
	Phoenix_Temp=Phoenix*0.02;

	
           //cout  statements
	cout<<"Rise in Temperature of NewYork is "<<NewYork_Temp<<endl;
	cout<<"Rise in Temperature of Denver is "<<Denver_Temp<<endl;
	cout<<"Rise in Temperature of  Phoenix is "<<Phoenix_Temp<<endl;

	

	double nN;
	double nD;
	double nP;


	nN=NewYork+NewYork_Temp;
	nD=Denver+Denver_Temp;
	nP=Phoenix+Phoenix+Phoenix_Temp;
	
	//cout statements
          cout<<"New Temperature is"<<nN<<endl;
	cout<<"New Temperature is"<<nD<<endl;
	cout<<"New Temperature is"<<nP<<endl;

	

	return 0;
}
                                     -------------------------------------------------------------------

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
   int hight=6;
    int length=100;
   int sqaurefeet_pergallon=340;
    int gallonfor_wopdenbox;
     //calculation
    gallonfor_wopdenbox=length*hight*2*sqaurefeet_pergallon;
      //cout statements
      cout<<"******gallonfor_wopdenbox******\n"<<gallonfor_wopdenbox<<endl;

      return 0;

}
                                  -----------------------------------------------------

 //chapter 3 programmes



//program calculates the area of the of a circle

#include<iostream>

using namespace std;

#include<cmath>

#include<conio.h>

int main()

{

    const double PI =3.14159;

    double area,radius;



    cout<<"this program calculates the area of the circle\n";

    cout<<"enter radius\n";

    cin>>radius;

    //calculation

    area=PI*pow(radius,2.0);



    cout<<"area of the circle\n"<<area<<endl;



    return 0;





}

                                ---------------------------------------------------------------

#include<iostream>

using namespace std;

#include<cmath>

#include<conio.h>

int main()

{

    double value1, value2 ,value3;



    cout<<"enter a number\n";

    cin>>value1;



    value2=2*pow(value1,2.0);

    value3=3+value2/2-1;



    cout<<value3<<endl;

    return 0;

}

                              ----------------------------------------------------------------



#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

    double volume ,radius ,height;

    const double PI=3.14159;



    cout<<"height of the cylinder\n";

    cin>>height;

    cout<<"radius of the cylinder\n";

    cin>>radius;

    volume=PI*(radius*radius)*height;

    cout<<"volume of the cylinder"<<volume<<endl;



    return 0;

}

                            ---------------------------------------------------------------------

//practice qs

//This programm demostrates integer overflow and underflow

#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

    short testvar=32767;

    cout<<testvar<<endl;



    //Add 1 to testvar to make it overflow.....give in output datatypes lowest possible values

    testvar=testvar+1;

    cout<<testvar<<endl;



    //subtract 1 from testvar to make it underflow.....return the same value AS INitial

    testvar=testvar-1;

    cout<<testvar<<endl;



    return 0;

}

                                      -------------------------------------------------

//This program show how our system behave with the overflow and underflow

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    float test;
    test=2.0e38*1000;    //should overlow test
    cout<<test<<endl;
    test=2.0e-38/2.0e38;   //should underflow test
    cout<<test<<endl;

    return 0;
}
                              --------------------------------------------------------
//how to direct call the global variable direct
#include<iostream>
using namespace std;
#include<conio.h>
int c=45;
int main()
{
    int a,b,c;
    

    cout<<"enter the value of a"<<endl;
    cin>>a;
    cout<<"enter the value of b"<<endl;
    cin>>b;
    c=a+b;
    cout<<"the sum is"<<c<<endl;
    cout<<"the global variable is"<<::c<<endl;    //use of scope resolution

    return 0;

}
                             -------------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    float d=34.4f;
    long double e=34.4l;
    /*this will work at the places where we want no conv ,as to take 34.4 always double ,but we want to take it 
    float also next in the complex programmes ,so we use f AND L With the values so specified them one id float and
    other is long double*/
                   

    cout<<"The value of d\n"<<d<<endl;
    cout<<"The value of e\n"<<e<<endl;

    return 0;
}
                               ---------------------------------------------------
//operator precedence
#include<iostream>
using namespace std;
int main()
{
    int a=3,b=4;
    int c=((((a*5)+b)-45)+87);
    cout<<"The value of c\n"<<c<<endl;

    return 0;
}
                      ------------------------------------------------------------------
//usage of setw /usage of manipulators
#include<iostream>
using namespace std;
#include<iomanip>
#include<conio.h>
int main()
{
    int a=3;
    int b=76;
    int c=1233;
    //without setw
    cout<<"The value of a without setw"<<a<<endl;
    cout<<"The value of b without setw"<<b<<endl;
    cout<<"The value of c without setw"<<c<<endl;

    //with setw 
    cout<<"The value of a with setw"<<setw(4)<<a<<endl;
    cout<<"The value of b with setw"<<setw(4)<<b<<endl;
    cout<<"The valu of c with setw"<<setw(4)<<c<<endl;

    return 0;


}
                     --------------------------------------------------------------
//referenced variable
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    float x=455;
    float & y=x;        //if we use float y=x....then output is same
    cout<<x<<endl;
    cout<<y<<endl;
}
              ------------------------------------------------------------
//finding the size of bytes by assigning values

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    float d=34.4f;
    long double e=34.4l;

    cout<<"The size of 34.4 is"<<sizeof(34.4)<<endl;
    cout<<"The size of 34.4f is"<<sizeof(34.4f)<<endl;
    cout<<"The size of 34.4F is"<<sizeof(34.4F)<<endl;
    cout<<"The size of 34.4l is"<<sizeof(34.4l)<<endl;
    cout<<"The size of 34.4L is "<<sizeof(34.4L)<<endl;

    return 0;
}
                       -----------------------------------------------------------
//type casting...converting one datatype to the other datatype
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    int a=45;
    float b=45.56;
    cout<<"The value of a is"<<(float)a<<endl;   //out put a=45  rmain in int
     cout<<"The value of a is"<<float(a)<<endl;

    cout<<"The value of b is"<<(int)b<<endl;
    cout<<"The value of b is"<<int(b)<<endl;      //output   b=45 ,bcoz floating conv into int
    int c=int(b);

    cout<<"The expression is"<<a+b;               //90.46
    cout<<"The expression is"<<a+int(b);         //90
    cout<<"The expression is"<<a+(int)b;        //90

    return 0;
}
                                 -------------end of practice qs part 1-----------------------------------------
ch3 programs
//type casting to avoid integer division
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    int books;
    int months;
    double permonth;

    //cout
    cout<<"enter the no of books to read\n"<<endl;
    cin>>books;
    cout<<"enter the no of months in which books are read\n"<<endl;
    cin>>months;

    //calculation
    permonth=static_cast<double>(books)/months;  //if we use (books/months)then integer division take place

    cout<<"no of books read per month\n"<<permonth<<endl;

    return 0;

}
                             ------------------------------------------------------------------
//to print a character from a number
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    int number =65;

    cout<<"Dispaly the value of number variable\n"<<number<<endl;

    cout<<static_cast<char>(number)<<endl;
    return 0;
}
                      ---------------------------------------------------------------------------
//type cast
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    int integer1,integer2;
    double result;
    integer1=19;
    integer2=2;

    //calculation
    result=integer1/integer2;
    cout<<result<<endl;

    result=static_cast<double>(integer1)/integer2;
    cout<<result<<endl;

    result=static_cast<double>(integer1/integer2);
    cout<<result<<endl;

    return 0;
}
                            ------------------------------------------------------
//diplsay ASCII code for the input letter
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
char letter;

cout<<"Display letter"<<endl;
cin>>letter;

cout<<static_cast<int>(letter)<<endl;

return 0;
}
                ------------------------------------------------------------------------
//checking output of the expressions
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    int a =5, b=12;
    double x=3.4, z=9.1;
    //cout and calculation combined
    cout<<b/a<<endl;
    cout<<x*a<<endl;
    cout<<static_cast<double>(b/a)<<endl;
    cout<<static_cast<double>(b)/a<<endl;
    cout<<b/static_cast<double>(a)<<endl;
    cout<<static_cast<double>(b)/static_cast<double>(a)<<endl;
    cout<<b/static_cast<int>(x)<<endl;
    cout<<static_cast<int>(x)*static_cast<int>(z)<<endl;
    cout<<static_cast<int>(x*z)<<endl;
    cout<<static_cast<double>(static_cast<int>(x)*static_cast<int>(z))<<endl;

    return 0;
}
                           ----------------------------------------------------------------

//number of widgets each store has sold from its inventory,the current inventory can be calculated
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    int beginvt,         //beginning inventory for all stores
    sold,                 //number of widgets sold
    store1,                //store 1's inventory
    store2,                //store 2's inventory
    store3;                //store 3's inventory

    //get the begginning inventory for all the stores
    cout<<"one week ago,3 new widgets store opened at the same time with the same beginning inventory\n";
    cout<<"what was the beginning inventory?";
    cin>>beginvt;

    //set each store inventory           
                                             /*comment for getting the main idea
                                             current inventory=beginning inventory-sold
                                             store1=store1-sold....and so on*/
    store1=store2=store3=beginvt;

    //get the no of widgets sold at store1
    cout<<"how many widgets has store1 store?";
    cin>>sold;
    store1-=sold;   //adjust stores 1's inventory

    //get the no of widgets sold at store2
    cout<<"how many widgets has sold store2?";
    cin>>sold;
    store2-=sold;     //adjust stores 2 's inventory

    //get the no of widgets sold at store 3
    cout<<"how many widgets has sold at store 3";
    cin>>sold;

    store3-=sold;         //adjust stores 3 inventory


    //display each stores current ineventoy
    cout<<"\nThe current inventory for each store is\n";
    cout<<"store1"<<store1<<endl;
    cout<<"store2"<<store2<<endl;
    cout<<"store3"<<store3<<endl;

    return 0;
}
                                   -----------------------------------------------------------
//guessing output
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    int unus,duo,tres;

    unus=duo=tres=5;
    unus +=4;
    duo *=2;
    tres -=4;
    unus /=3;
    duo += tres;
    cout<<unus<<endl;
    cout<<duo<<endl;
    cout<<tres<<endl;
    

    return 0;
}
                     -----------------------------------------------------------------------
//formatting output...display 3 rows of nos
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    int num1=2897,  num2=5, num3=637,
        num4=34,    num5=7, num6=1623,
        num7=390,  num8=3456, num9=12;

        //display the first row of numbers
        cout<<num1<<" "<<num2<<" "<<num3<<" "<<endl;
        //display the 2nd row of numbers
        cout<<num4<<" "<<num5<<" "<<num6<<" "<<endl;
        //display the 3rd row of numbers
        cout<<num7<<" "<<num8<<" "<<num9<<" "<<endl;

        return 0;

}
                                  --------------------------------------------------------------
//formatting output...display 3 rows of nos and columns by using setw
#include<iostream>
using namespace std;
#include<iomanip>
#include<conio.h>
int main()
{
    int num1=2897,  num2=5, num3=637,
        num4=34,    num5=7, num6=1623,             /*the output would be right sided and if one put left 
                                                     the output wpuld be left sided*/
        num7=390,  num8=3456, num9=12;

        //display the first row of numbers
        cout<<left<<setw(6)<<num1<<setw(6)<<num2<<setw(6)<<num3<<endl;
        //display the 2nd row of numbers
        cout<<setw(6)<<num4<<setw(6)<<num5<<setw(6)<<num6<<endl;
        //display the 3rd row of numbers
        cout<<setw(6)<<num7<<setw(6)<<num8<<setw(6)<<num9<<endl;

        return 0;

}
                            -------------------------------------------------------------
//this program demonstrates the setw manipulator being used with values of diff data type
#include<iostream>
using namespace std;
#include<conio.h>
#include<iomanip>
int main()
{
    int value=3928;
    double dvalue=91.5;
    string stvalue="John J smith";


    cout<<"("<<setw(16)<<value<<")"<<endl;
    cout<<"("<<setw(16)<<dvalue<<")"<<endl;
    cout<<"("<<setw(16)<<stvalue<<")"<<endl;

    return 0;
}
                               ------------------------------------------------------------------
//use of set precision manipulator...how setprecision rounds a floating point value
#include<iostream>
using namespace std;
#include<iomanip>
#include<conio.h>
int main()
{
    double quotient,
    number1=132.364,
    number2=26.91;

    //caculation
    quotient=number1/number2;

    //couts
    cout<<quotient<<endl;
     cout<<setprecision(5)<<quotient<<endl;
    cout<<setprecision(4)<<quotient<<endl;
    cout<<setprecision(3)<<quotient<<endl;
    cout<<setprecision(2)<<quotient<<endl;
    cout<<setprecision(1)<<quotient<<endl;

    return 0;
}
                            ----------------------------------------------------------------

//setw and setprecision in one program
#include<iostream>
using namespace std;
#include<conio.h>
#include<iomanip>
int main()
{
    double day1,day2,day3,total;

    //get the sales for each day
    cout<<"Enter the sales for day1:";
    cin>>day1;
    cout<<"Enter the sales for day2:";
    cin>>day2;
    cout<<"Enter the sales for day3:";
    cin>>day3;

    //calculates the totall sales
    total=day1+day2+day3;

    //display the sales amounts
    cout<<"\nsales amounts\n";
    cout<<"-----------------\n";
    cout<<setprecision(5);
    cout<<"Day 1:"<<setw(8)<<day1<<endl;
    cout<<"Day 2:"<<setw(8)<<day2<<endl;
    cout<<"Day 3:"<<setw(8)<<day3<<endl;
    cout<<"total:"<<setw(8)<<total<<endl;

    return 0;

}
                         ------------------------------------------------------------------

//setw and setprecision in one program  ,and use of fixed 
#include<iostream>
using namespace std;
#include<conio.h>
#include<iomanip>
int main()
{
    double day1,day2,day3,total;

    //get the sales for each day
    cout<<"Enter the sales for day1:";
    cin>>day1;
    cout<<"Enter the sales for day2:";
    cin>>day2;
    cout<<"Enter the sales for day3:";
    cin>>day3;

    //calculates the totall sales
    total=day1+day2+day3;

    //display the sales amounts
    cout<<"\nsales amounts\n";
    cout<<"-----------------\n";
    cout<<setprecision(2)<<fixed;     //fixed kr di means fractional la bd 2 values must ae gin
    cout<<"Day 1:"<<setw(8)<<day1<<endl;
    cout<<"Day 2:"<<setw(8)<<day2<<endl;
    cout<<"Day 3:"<<setw(8)<<day3<<endl;
    cout<<"total:"<<setw(8)<<total<<endl;

    return 0;

}
                         ----------------------------------------------------------------
//show point
#include<iostream>
using namespace std;
#include<iomanip>
#include<conio.h>
int main()
{
    double x=123.4, y=456.0;
    cout<<setprecision(6)<<showpoint<<x<<endl;
    cout<<y<<endl;

    return 0;
}
                       ------------------------------------------------------------------
//chkpoint 3.19..ask for an angle in degrees and converts it to radians.the formatting output will be left to you
#include<iostream>
using namespace std;
#include<conio.h>
#include<iomanip>
int main()
{
    const double PI=3.14159;
    double degrees,radians;

    cout<<"Enter an angle in degrees and i will convert it to radians"<<endl;
    cin>>degrees;

    //calculation
    radians=degrees*PI/180;

    cout<<setprecision(4)<<fixed;
    cout<<left<<setw(5)<<radians<<endl;

    return 0;

}
                            ----------------------------------------------------------------
//chkpoint 3.17 (D)
#include<iostream>
using namespace std;
#include<iomanip>
#include<conio.h>
int main()
{
    int number=67;
    cout<<left<<setw(7)<<number<<endl;

    return 0;
}
                      ---------------------------------------------------------------------------------

//display the number 34.789 in a field of nine spaces with two decimal places of precision
#include<iostream>
using namespace std;
#include<iomanip>
#include<conio.h>
int main()
{
    double number=34.789;
    cout<<setprecision(02);
    cout<<setw(9)<<number;

    return 0;
}
                      ----------------------------------------------------------------------------------
//display the number 7.0 in a field of five spaces with three decimal places of precision
#include<iostream>
using namespace std;
#include<iomanip>
#include<conio.h>
int main()
{
    double number=7.0;
    cout<<setprecision(03);
    cout<<setw(5)<<showpoint<<number;

    return 0;
}
                   ---------------------------------------------------------------------------------------
//working with characters and string objects
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    string name;
    string city;

    cout<<"Enter your name";
   // cin>>name;
    getline(cin,name);
    cout<<"Enter the city u live in";
    //cin>>city;
    getline(cin,city);
    cout<<"hello"<<name<<endl;
    cout<<"You live in"<<city<<endl;

    return 0;
}
                                   ----------------------------------------------------------
//This program reads a single character into a char variable
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    char ch;

    cout<<"type a character and press enter";
    cin>>ch;
    cout<<"you entered"<<ch<<endl;

    return 0;
}
                               --------------------------------------------------------------
//This program demonstrates three ways to use cin.get() to pause a program

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    char ch;

    cout<<"This program is paused.press Enter to continue";
    cin.get(ch);
    cout<<"This program is paused second time.press Enter to continue";
    cin.get();
    cout<<"This program is paused.press Enter to continue";
    ch=cin.get();
    cout<<"Thank u";

    return 0;
}
                                 -------------------------------------------------
//mixing cin and cin.get()...and use of cin.ignore()
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    char ch;
    int number;

    cout<<"Enter a number";
    cin>>number;
    cin.ignore();        //skip the newline ch
    cout<<"Enter a character";
    ch=cin.get();

    cout<<"Thanku";

    return 0;
}
                                ----------- -------- ---------- ----------------- ------------
//strings can be combined
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    string greeting1="Hello ";
    string greeting2;
    string name1="world";
    string name2="people";

    greeting2=greeting1+name1;
    greeting1+=name2;

    cout<<greeting2<<endl;
    cout<<greeting1<<endl;

    return 0;
}
                                  --------------------------------------------------------------
//string length
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    string state="taxes";
    int size=state.length();
    cout<<size<<endl;

    return 0;
}
                        --- ----------------------------------------------------------------------
//mathematical library functions
#include<iostream>
using namespace std;
#include<conio.h>
#include<cmath>
int main()
{
    double num;
    double s;
    cout<<"Enter the number"<<endl;
    cin>>num;
    //calculation

    s=sqrt(num);

    cout<<"number\n"<<s<<endl;
    return 0;
}
                                 -------------------------------------------------------
/*This program asks for the lenghts of the two sides of a right triangle.The lenghts  of the hypotenuse 
is then calculated and displayed*/
#include<iostream>
using namespace std;
#include<conio.h>
#include<iomanip>
#include<cmath>
int main()
{
    double a ,b,c;
    cout<<"Length of one side of triangle"<<endl;
    cin>>a;
    cout<<"Length of other side of triangle"<<endl;
    cin>>b;
    c=sqrt(pow(a,2)+pow(b,2));
    cout<<"The length of hypotenuse"<<setprecision(2)<<c<<endl;

    return 0;


}
                                    ------------------------------------------------------------------

//random numbers
#include<iostream>
using namespace std;
#include<conio.h>
#include<cstdlib>   //for random number
#include<ctime>   //for the time function
int main()
{
   
   unsigned seed=time(0);     //get the system time
    srand(seed);              //seed the random number generator 
                               /*agar ham sirf rand use krte to ik system ma har bar random values ik jaise 
                               print hotoi so hum us sa bachne ka liye srand use krte lakin srand ka sth hm ko seed
                               b use krnna pary ga ,r seed ka unsigned int hona lazmi ha,seed ko time ka function dena 
                               b lazmi ha  r time ko 0 argument pass krna b zarori ha;ye sab conditions fulfill krne
                               ka bad output ma diff random numbers show ho gain har bar*/
    //display the three random numbers
    cout<<rand()<<endl;
    cout<<rand()<<endl;
    cout<<rand()<<endl;

    return 0;


                               

}
                                      ---------------------------------------------------------------

//usage of formula :y=(rand()%(maxvalue-minvalue+1))+minvalue BY the example of rolling dice
#include<iostream>
using namespace std;
#include<conio.h>
#include<cstdlib>
#include<ctime>
int main()
{
    //constants
    const int Min_value=1;      //min die value
    const int Max_value=6;     //max die value

    //variables
    int die1;
    int die2;

    unsigned seed=time(0);
    srand(seed);

    cout<<"Rolling the dice\n";
     //calculation
     die1=(rand()%(Max_value-Min_value+1))+Min_value;
     die2=(rand()%(Max_value-Min_value+1))+Min_value;

     cout<<die1<<endl;
     cout<<die2<<endl;
     return 0;
}
                           -------------------------------------------
/*chkpoint 3.21  assume the variables angle1 and angle2 hold angles stored in radians .write a statement that adds
the sine of angle1 to the cosine of angle2 and stores the result in the variable x*/
#include<iostream>
using namespace std;
#include<cmath>
#include<conio.h>
int main()
{
    double angle1=2.34;
    double angle2=3.47;
    double x;
    double y;
    double z;

    x=sin(angle1);
    y=cos(angle2);
    z=x+y;
    cout<<x<<"radians"<<endl;
    cout<<y<<"radians"<<endl;
    cout<<z<<"radians"<<endl;

    return 0;
}
                                    --------------------------------------------------------------
/*chk.point 3.22 write a statement that fill find out the fifth root of the variable x and store the result in 
the variable y*/
#include<iostream>
using namespace std;
#include<conio.h>
#include<cmath>
int main()
{
    int x,y;
    cout<<"give value of x"<<endl;
    cin>>x;
    y=pow(x,1/5);
    cout<<y<<endl;
    return 0;

}
                                        ----------------------------------------------------------------
/*cosecant=1/sina...write a statement that calculates the cosecant of the angle stored in the variable and
stores it in variable y*/
#include<iostream>
using namespace std;
#include<conio.h>
#include<cmath>
int main()
{
    double a,y;
    cout<<"Give value of a"<<endl;
    cin>>a;
    y=1/sin(a);
    cout<<y<<endl;
    return 0;
}
                                ---------------------------------------------------------------------------

//chapter 3 question 37 ,guessing output checking assume user enter 36720152

#include<iostream>

#include<iomanip>

using namespace std;

int main()

{

    long seconds;

    double minutes,hours,days,months,years;



    cout<<"Enter the no of seconds that havr\n";

    cout<<"elapsed since some time in the past and\n";

    cout<<"I will tell you how many minutes,hours,\n";

    cout<<"days,months,and years have passed:";

    cin>>seconds;



    minutes=seconds/60;

    hours=minutes/60;

    days=hours/24;

    years=days/365;

    months=years*12;



    cout<<setprecision(4)<<fixed<<showpoint<<right;

    cout<<"minutes"<<setw(6)<<minutes<<endl;

    cout<<"hours"<<setw(6)<<hours<<endl;

    cout<<"days"<<setw(6)<<days<<endl;

    cout<<"months"<<setw(6)<<months<<endl;

    cout<<"years"<<setw(6)<<years<<endl;



    return 0;    

}

                             ------------------------------------------------------------

//q 36 ch 3

#include<iostream>

using namespace std;

#include<iomanip>

#include<string>

int main()

{

    string user_input;

    cout<<"What is your name";

    getline(cin,user_input);

    cout<<"hello"<<user_input<<endl;



    return 0;

}

                                 ---------------------------------------------------------

#include<iostream>

using namespace std;

int main()

{

    long x,y,z;



    x=y=z=4;

    x += 2;

    y -= 1;

    z *= 3;



    cout<<x<<" "<<y<<" "<<z<<" "<<endl;



    return 0;

}

                            ------------------------------------------------------------

#include<iostream>

using namespace std;

int main()

{

    double salary,monthly;



    cout<<"what is your annual salary?";

    cin>>salary;

    monthly=static_cast<int>(salary)/12;



    cout<<"Your monthly wages are"<<monthly<<endl;

    return 0;

}

                            ---------------------------------------------------------------



#include<iostream>

using namespace std;

#include<conio.h>

//#include<iomanip>

//#include<cmath>

int main()

{

    double number,half;



    cout<<"Enter a number and I will divide it\n";

    cout<<"in half for you\n";



    cin>>number;



    half=number/2;



    cout<<fixed <<showpoint<<half<<endl;

    return 0;



}

                          --- -------------------------------------------------------

//q 32

#include<iostream>

using namespace std;

int main()

{

    int number1,number2;



    cout<<"Enter two numbers and I will multiply\n";

    cout<<"them by 50 for you\n";



    cin>>number1>>number2;



    number1*=50;

    number2*=50;



    cout<<number1<<" "<<number2;



    return 0;

}

                                -------------------------------------------------------------

//q 29

#include<iostream>

using namespace std;

int main()

{

    int number1,number2;

    float quotient;



    cout<<"Enter two numbers and I will divide\n";

    cout<<"the first by the second for you\n";

    cin>>number1>>number2;

    quotient =static_cast<float>(number1)/number2;

    cout<<quotient;



    return 0;

}

                                  ------------------------------------------------------------

//q 28

#include<iostream>

using namespace std;

int main()

{

    double number1,number2,sum;

    cout<<"Enter a number";

    cin>>number1;

    cout<<"Enter another number";

    cin>>number2;

    sum=number1+number2;



    cout<<"The sum of the two numbers is"<<sum;



    return 0;

}

                                         -------------------------------------------

//WAP that asks the user to enter a golfer's score for three games of golf ,and then display the average of three score!

#include<iostream>

using namespace std;

int main()

{

    int G_1,G_2,G_3;

    double average;



    cout<<"Enter the 1st score of golf's"<<endl;

    cin>>G_1;

     cout<<"Enter the 2nd score of golf's"<<endl;

    cin>>G_2;

      cout<<"Enter the  3rd score of golf's"<<endl;

    cin>>G_3;



    average=(G_1+G_2+G_3)/3.0;



    cout<<"average"<<average<<endl;



    return 0;





}

                                ---------------------------------------------------------------



/*WAP that calculates the calculates the total of retail sale.The programmer should ask for the amount of the sale and the sales tax rate.

the sales tax rate should be entered as floating point such as if the sale tax rate is 6% the user should enter 0.06.display amount of the 

sales tax and the total of the sale*/

#include<iostream>

using namespace std;

int main()

{

    int sale_amount;

    const float sales_tax=0.07;

    float total_salestax;

    double total_sale;





    cout<<"Enter the amount of sale"<<endl;

    cin>>sale_amount;

    //total sales tax

    total_salestax=sale_amount*sales_tax;



    cout<<"total_salestax"<<total_salestax<<endl;

    //total sale



    total_sale=sale_amount+total_salestax;



    cout<<"total_sale"<<total_sale<<endl;



    return 0;







}

                                     --------------------------------------------------------------

/*A retail store grants its customers a maximum amount of credit.Each customers available credit is his/her maximum amount of credit  minus

the amount of credit used.WAP  that ask the user for customers maximum amount of credit  and the amountof credit used.The program should then

display the customers available credit*/

#include<iostream>

using namespace std;

int main()

{

    int max_credit;

    int used_credit;

    int available_credit;



    cout<<"Give maximum credit"<<endl;

    cin>>max_credit;



    cout<<"Enter the used credit"<<endl;

    cin>>used_credit;



    available_credit=max_credit-used_credit;



    cout<<"available credit"<<available_credit<<endl;



    return 0; 

}

                                   ------------------------------------------------------



/*Write a cout statement so the variable population is displayed in a field of 12 spaces ,left_justified,with a precision of 8 decimal

places.The decimal point should always be displayed*/



#include<iostream>

using namespace std;

#include<iomanip>

#include<string>

int main()

{

    const string population="population";



    cout<<setprecision(8)<<left;

    cout<<setw(12)<<population<<endl;



    return 0;

}

                                --------------------------------------------------------------

/*Write a cout statement so the variable population is displayed in a field of 12 spaces ,left_justified,with a precision of 8 decimal

places.The decimal point should always be displayed*/



#include<iostream>

using namespace std;

#include<iomanip>



int main()

{

    float population;



    cout<<"ENter population"<<endl;

    cin>>population;



    cout<<setprecision(8)<<left;

    cout<<setw(12)<<population<<endl;



    return 0;

} 

                                               ----------------------------------------------------

/*write a cout statement so the variable totalAge is displayed in a field of 12 spaces,in a fixed point notation ,with a precision 

of 4 decimal places*/

#include<iostream>

using namespace std;

#include<iomanip>

int main()

{

    float totalAge;



    cout<<"Enter totalAge"<<endl;

    cin>>totalAge;



    cout<<setprecision(4)<<fixed;

    cout<<setw(12)<<totalAge<<endl;



    return 0;

}

                                         ---------------------------------------------------



/*write a cout statement so the var divsales is diplayed in a field of 8 spaces,in fixed -point notation,with a precision of 2 

decimal places.The decimal point should always be displayed*/

#include<iostream>

using namespace std;

#include<iomanip>

int main()

{

    float divsales;



    cout<<"Give divsales"<<endl;

    cin>>divsales;



    cout<<setprecision(2)<<fixed;

    cout<<setw(8)<<divsales;



    return 0;

}

                                  -----------------------------------------------------------

programming challenges of the chapter 3



//programming challenges challenge no 1



#include<iostream>

using namespace std;

#include<iomanip>

int main()

{

     float no_gallons;

     float no_miles;

     float x;



     //cout statements

     cout<<"give the no of gallons"<<endl;

     cin>>no_gallons;



     cout<<"give no of miles"<<endl;

     cin>>no_miles;



     x=no_miles/no_gallons;



     cout<<"The value of x\n"<<setprecision(3)<<showpoint<<x<<endl;



     return 0;

}

                                       -----------------------------------------------------



//programming challenge 2



#include<iostream>

using namespace std;

#include<iomanip>

int main()

{

   const int class_A=15;

   const int class_B=12;

   const int class_C=9;



   int ticket_A,ticket_B,ticket_C;



   int A_income,B_income,C_income;



   //cout statements

   cout<<"class A sold how many tickets"<<endl;

   cin>>ticket_A;



   cout<<"class B sold how many tickets"<<endl;

   cin>>ticket_B;



   cout<<"class C sold how many tickets"<<endl;

   cin>>ticket_C;



   //calculation  amount of income generated



        A_income=class_A*ticket_A;

        B_income=class_B*ticket_B;

        C_income=class_C*ticket_C;



   //Dispaly



       cout<<setprecision(2)<<fixed<<endl;

       cout<<"$"<<A_income<<endl;

       cout<<"$"<<B_income<<endl;

       cout<<"$"<<C_income<<endl;



       return 0;

}

                                          ------------------------------------------------
//programming challenge 3

#include<iostream>
using namespace std;
#include<iomanip>
int main()
{
     float t1_score,t2_score,t3_score,t4_score,t5_score;

     double average;

     cout<<"give the value of five test score"<<endl;
     cin>>t1_score>>t2_score>>t3_score>>t4_score>>t5_score;
     //calculation
     average=(t1_score+t2_score+t3_score+t4_score+t5_score)/(5);
  
      //cout statements
      cout<<setprecision(1)<<fixed<<endl;
      cout<<"Give average"<<average<<endl;

  return 0;
}
                                           -------------------------------------------------

//programming challenge 4

#include<iostream>
using namespace std;

int main()
{
    float june_rainfall,july_rainfall,august_rainfall;

    double average;

    //cout statements

    cout<<"give the june_rainfall"<<endl;
    cin>>june_rainfall;

    cout<<"give the july_rainfall"<<endl;
    cin>>july_rainfall;

    cout<<"give the august"<<endl;
    cin>>august_rainfall;

    average=(june_rainfall+july_rainfall+august_rainfall)/3;

    cout<<"The average rainfall for june,july,and august is"<<" "<<average<<" "<<"inches"<<endl;

    return 0;

}
                                         --------------------------------------------

//programming challenge 5
#include<iostream>
using namespace std;
int main()
{
    int males,females;
     float total_members;
    

    double per_males;
    double per_females;

    cout<<"No of males in the class"<<endl;
    cin>>males;

    cout<<"no of females in the class";
    cin>>females;

    total_members=males+females;

   per_males=(males/total_members)*100;
   per_females=(females/total_members)*100;

   cout<<"per_males\n"<<per_males<<endl;
   cout<<"per_females\n"<<per_females<<endl;


   return 0;


}
                                --------------------------------------------------------

//programming challenge 6


#include<iostream>
using namespace std;
int main()
{
    const float sugar_cups=1.5;
    const float cup_butter=1;
    const float cups_offlour=2.75;

    const float total_cookies=48;

    float user_cookies;

    //user cookies ingredients

     float user_sugarcups;
     float user_cupbutter;
     float user_cupsflour;

    cout<<"user wants to make cookies"<<endl;
    cin>>user_cookies;

    //calculation

    user_sugarcups=(sugar_cups/total_cookies)*user_cookies;
    user_cupbutter=(cup_butter/total_cookies)*user_cookies;
    user_cupsflour=(cups_offlour/total_cookies)*user_cookies;

    cout<<"user suger cups "<<user_sugarcups<<endl;
    cout<<"user cup butter"<<user_cupbutter<<endl;
    cout<<"use cups flour"<<user_cupsflour<<endl;


    return 0;

}
                                      ------------------------------------------------------

//programming challenge no 7

#include<iostream>
using namespace std;
#include<string>
#include<conio.h>
int main()
{
    //declaration
    int theaters_gross;
    int NetBox_officeprofit;
    int paid_distributor;

    string movie_name;
    int adult_tickets_sold;
    int child_ticket_sold;
    const int price_adult_ticket=10;
    const int price_child_ticket=6;
    int adult_cost;
    int child_cost;

   //cout statements
    cout<<"Enter the movie broadcasted in theater"<<endl;
    getline(cin,movie_name);

    cout<<"no of tickets taken by adult"<<endl;
    cin>>adult_tickets_sold;

    cout<<"no of tickets taken by child"<<endl;
    cin>>child_ticket_sold;

    //calculations
    adult_cost=adult_tickets_sold*price_adult_ticket;
    child_cost=child_ticket_sold*price_child_ticket;

    //gross and net calculations

    theaters_gross=adult_cost+child_cost;
    NetBox_officeprofit= theaters_gross*0.2;                        //20% of the total amount

    //amount paid to the distributor

    paid_distributor=theaters_gross-NetBox_officeprofit;


    cout<<"The movie broadcasted in the theater is"<<" "<<movie_name<<endl;
    cout<<"NO of tickets sold to adults"<<" "<<adult_tickets_sold<<endl;
    cout<<"No of tickets sold to child"<<" "<<child_ticket_sold<<endl;
    cout<<"Total amount earned or gross of thearter"<<" "<<theaters_gross<<endl;
    cout<<"Net amount ,which is 20% of the total amount ..the amount actually goes to theater"<<" "<<NetBox_officeprofit<<endl;
    cout<<" paid_distributor,the amount which maximally goes to investerors of the movie"<<" "<<paid_distributor<<endl;

    return 0;






}
                                              ----------------------------------------------

//programming challenge 8

#include<iostream>
using namespace std;
int main()
{
    //1 widgets weight is equal to 12.5 pounds

    float pallet_itself_weight;
    float pallet_plus_widgets;
    float widgets_weight;
    float no_of_widgets;
    const float one_widget_weight=12.5;


    cout<<"The weight of the pallet is"<<endl;
    cin>>pallet_itself_weight;

    cout<<"The weight of the pallet plus widgets ,collectively"<<endl;
    cin>>pallet_plus_widgets;

    widgets_weight=pallet_plus_widgets-pallet_itself_weight;
    no_of_widgets=widgets_weight/one_widget_weight;

    cout<<"no of widgets on the pallet"<<" "<<no_of_widgets<<endl;
    return 0;





}
                                -------------------------------------------------------------------



                                                              ☝ calculation output

                                                       

//challenge 9 ch 3



#include<iostream>

using namespace std;

int main()

{

   const int cookies_given=30;

   const int servings=10;

   /*one serving is equal to 300 calories  ,for 10 servings each person take 3 cookies ,,,with 300 calories

   means a person eat 3 cookies with 300 calories*/



   int user_eat_cookies;

   int calories_consumed;



   cout<<"how many cookies you eat ,don't lie"<<endl;

   cin>>user_eat_cookies;



   calories_consumed=(300/3)*user_eat_cookies;



   cout<<"No of calories you comsumed"<<calories_consumed<<endl;



   return 0;







}

                                     -------------------------------------------------------

//programming challenge 10



#include<iostream>

using namespace std;

int main()

{



    float replacement_cost_building;

    float insurance;



    //insurance atleast  80% 



    cout<<"Enter the replacement cost of the building"<<endl;

    cin>>replacement_cost_building;



    insurance=replacement_cost_building*0.8;



    cout<<"isurnace of the property"<<insurance<<endl;



    return 0;

}

                                   ---------------------------------------------------



//programming challenge 11



#include<iostream>

using namespace std;

int main()

{

    float loan_payments,insurance,gas,oil,tires,maintenance;



    double total_monthly_expenses;

    double annual_expenses;



    cout<<"Give loan payments,insurance,gas,oil,tires,maintenance expenses"<<endl;

    cin>>loan_payments>>insurance>>gas>>oil>>tires>>maintenance;



    total_monthly_expenses=loan_payments+insurance+gas+oil+tires+maintenance;



    annual_expenses=total_monthly_expenses*12;



    cout<<"total_monthly_expenses"<<total_monthly_expenses<<endl;

    cout<<"annual_expenses"<<annual_expenses<<endl;



    return 0;





}

                                     -------------------------------------------------

//challenge 12



#include<iostream>

using namespace std;

int main()

{

    float value_in_celcius;

    float value_in_fahrenheit;



    cout<<"Enter the value of temperature in degree celcius"<<endl;

    cin>>value_in_celcius;



    value_in_fahrenheit=(1.8)*value_in_celcius+32;



    cout<<"value in fahrenheit"<<value_in_fahrenheit<<endl;



    return 0;





}

                                         ---------------------------------------------

//programming challenge 13

#include<iostream>
using namespace std;
int main()
{
    float US_doller;
    float japanese_yen;
    float japanese_euro;

    const float Yen_per_doller=98.9;
    const float Euro_per_doller=0.74;

    cout<<"enter the US doller wahich you want to convert in euru and yen"<<endl;
    cin>>US_doller;

    japanese_yen=Yen_per_doller*US_doller;
    japanese_euro=Euro_per_doller*US_doller;

    cout<<"coverted currency of YEN"<<endl;
    cout<<japanese_yen;

    cout<<"converted currency of EURO"<<endl;
    cout<<japanese_euro;


    return 0;



}
                                     --------------------------------------------------

//programming challange

#include<iostream>
using namespace std;
#include<cmath>
int main()
{
    string month;
    int year;
    double collected_amount;
    double sales;
    const float country_tax=0.02;
    double country_taxrate;
    const float state_tax=0.04;
    double state_taxrate;

    //input 

     cout<<"Enter the month"<<endl;
     getline(cin,month);
     cout<<"Enter the year"<<endl;
     cin>>year;
     cout<<"total collected amount"<<endl;  //it an be done by 2nd method like we input sales in that case
     cin>>collected_amount;
    //we add that sales and total sales= total collected
    //find out the sales or product sales from total collected amount

     sales=(collected_amount)/1.06;
     cout<<"collected_amount "<<collected_amount<<endl;
     cout<<"product sales    "<<sales<<endl;

     //country sales tax which is 2%
     country_taxrate=sales*country_tax;
     //state sales tax which is 4%
     state_taxrate=sales*state_tax;

     cout<<"country_taxrate  "<<country_taxrate<<endl;
     cout<<"state_taxrate    "<<state_taxrate<<endl;
     cout<<"total sales tax  "<<country_taxrate+state_taxrate<<endl;

     return 0;


}
                                            ----------------------------------------------------

//programming challenge  15

#include<iostream>
using namespace std;
int main()
{
    double value_property;
    double assessment_value;  //which is 60% of the original property
    double tax;


    cout<<"Actual amount of the piece of property"<<endl;
    cin>>value_property;

    assessment_value=value_property*0.6;

    cout<<"assessment value of the property"<<assessment_value<<endl;
    //property tax

    tax=(0.0075)*assessment_value;    //75% ,it will 0.75 then 0.75/100 then 0.0075

    cout<<"tax will be"<<tax<<endl;


    return 0;




}
                                        ------------------------------------------------------

//programming challenge 16

#include<iostream>
using namespace std;
int main()
{
   const double owner_exemption=5000;
   double actual_value;
   float tax_rate;
   double assessed_value;     //60% of the original value
   double pay_tax;
   double property_tax;
   double annual_property_tax;        //annual
   double quaterly_tax;


   cout<<"actual value of the property"<<endl;
   cin>>actual_value;

   cout<<"Give the value of tax rate"<<endl;
   cin>>tax_rate;

   assessed_value=actual_value*0.6;
   pay_tax=assessed_value-owner_exemption;

   cout<<"actual value of property $"<<actual_value<<endl;
   cout<<"assessed value           $"<<assessed_value<<endl;
   cout<<"tax paid on actual value $"<<pay_tax<<endl;

   //property tax

   property_tax=tax_rate/100;
   annual_property_tax=property_tax*assessed_value;

   cout<<"annual property tax      $"<<annual_property_tax<<endl;

   //quaterly paid tax

   quaterly_tax=annual_property_tax*0.25;   //1/4=0.25

   cout<<"quaterly paid tax        $"<<quaterly_tax<<endl;


   return 0;

}
                                       --------------------------------------------------------

//programming challenge 17

#include<iostream>
using namespace std;
#include<cstdlib>
#include<cmath>
#include<ctime>
#include<iomanip>
int main()
{
    //var declaration
    int num1,num2;

    //constant declaration
    const int max=1000;
    const int min=10;

    //for random number
    unsigned seed=time(0);
    srand(0);

    //calculations

    num1=(rand()%(max-min+1))+min;
    num2=(rand()%(max-min+1))+min;

    cout<<"  "<<num1<< "\n+" << num2 <<endl;
    //cout<<"+"<<num2<<endl;

    cin.get();      //pause a program

    cout<<num1+num2<<endl;

    return 0;
}
                                           -----------------------------------------------------

//programming ch 18

#include<iostream>
using namespace std;
#include<iomanip>
#include<cmath>

int main()
{

    double principal;  
    float interest_rate;
    int time_compounded;
    long double amount_in_savings;
    double interest;
    double without_per_interest;


    //inputs
    cout<<"principal"<<endl;
    cin>>principal;

    cout<<"interest rate"<<endl;
    cin>>interest_rate;

    cout<<"time compounded"<<endl;
    cin>>time_compounded;
    
    //calculation
    without_per_interest=interest_rate/100;
    amount_in_savings=principal*pow(1+(without_per_interest/time_compounded),time_compounded);
    interest=amount_in_savings-principal;

    cout<<"**************************"<<endl;


    cout<<setprecision(2)<<fixed<<endl;
    //automatically right justified!
    cout<<"interest rate         "<<interest_rate<<" %"<<endl;
    cout<<"time compounded         "<<time_compounded<<endl;
    cout<<"principal       $     "<<principal<<endl;
    cout<<"interest        $       "<<interest<<endl;
    cout<<"savings         $     "<<amount_in_savings<<endl;


    cout<<"**************************"<<endl;

    return 0;




}
                                    ----------------------------------------------------------

//programming challenge 19

#include<iostream>
using namespace std;
#include<iomanip>
#include<cmath>
int main()
{
    double loan;
    const float monthly_interest_rate=0.01;
    int no_of_payments;
    double monthly_payments;
    double final_monthly_payments;
    int paid_back;
    double interest_paid;

    cout<<"Enter the amount of loan"<<endl;
    cin>>loan;

    

    cout<<"no of payments"<<endl;
    cin>>no_of_payments;
    //monthly payments
    cout<<setprecision(4)<<fixed<<endl;
    cout<<"Amount of loan       $ "<<loan<<endl;
    cout<<right<<"Monthly inte rate    $ "<<"1%"<<endl;
    cout<<right<<"no of payments         "<<no_of_payments<<endl;
    
    monthly_payments=(monthly_interest_rate*pow(1+monthly_interest_rate,no_of_payments)
                                         )/(pow(1+monthly_interest_rate,no_of_payments)-1);
    final_monthly_payments=monthly_payments*loan;

    cout<<right<<"Monthly payment      $  "<<final_monthly_payments<<endl;

    //amount paid back
    paid_back=final_monthly_payments*no_of_payments;

    cout<<right<<"amount paid back     $  "<<paid_back<<endl;

    //interest paid
    interest_paid=paid_back-loan;

    cout<<"interest paid        $  "<<interest_paid<<endl;

    return 0;

}
                                             --------------------------------------------------

//programming challenge 20 and 21


#include<iostream>
using namespace std;
#include<cmath>
int main()
{
    float pizza_d_inches;
    const float pi=3.1459;
    float radius;
    double area;
    const float each_slice_area=14.125;
    float no_of_slices;
    int people_in_party;
    int total_no_pizza;


    cout<<"Give the diameter of pizza in inches "<<endl;
    cin>>pizza_d_inches;

    cout<<"calculation to find radius ,to  find the area of the pizza"<<endl;

    radius=pizza_d_inches/2;

    cout<<radius<<endl;

    cout<<"calculations to find the area of the pizza"<<endl;

    area=pi*pow(radius,2);

    cout<<area<<endl;

    cout<<"total no of slices in a pizza of diameter entered is"<<endl;

    no_of_slices=area/14.125;

    cout<<no_of_slices<<endl;

    //we entered 12 diameter so we get 8 slices ,a pizza have


    //program 21 related to the 20 program

    //if one person eats  4 slices of pizza 

    //ask the user how many people will attend the party

    cout<<"how many people will attend the party"<<endl;
    cin>>people_in_party;

    //2 people will eat 1 pizza ,suppose we entered 20 people attend the party then 10 pizza will be ordered

    total_no_pizza=people_in_party/2;

    cout<<"20 people needed how many pizzas to ordered\n"<<total_no_pizza<<endl;

    return 0;


}
                                           ---------------------------------------------------

//programming challenge 22

#include<iostream>
using namespace std;
#include<iomanip>
#include<cmath>
int main()
{
    float  w;
    double x;
    double y;
    double z;

    cout<<"Enter the angle in radians"<<endl;
    cin>>w;

    //use library functions to find sine ,cos,and tan of the given angle
    //sine
    x=sin(w);
    //cos
    y=cos(w);
     //tan
    z=tan(w);

     cout<<setprecision(4)<<fixed<<endl;
    cout<<"sine of angle radian"<<x<<endl;
    cout<<"cos of angle radian"<<y<<endl;
    cout<<"tan of angle radian"<<z<<endl;
     

     return 0;
}
                                        -----------------------------------------------------------

//programming challenge 23
#include<iostream>
using namespace std;
int main()
{
    //purchase
    const int no_of_purchase_share=1000;
    const float per_share=45.50;
    const float stock_commission=0.02;

    //sale
    const int no_of_sold_share=1000;
    const float per_sold_share=56.90;
    const float stock_sold_commission=0.02;

    float joe_paid;
    float joe_commission;
    float joe_sold_stock;
    float joe_sold_commission;
    float joe_profit;
    float total_receive_amount;
    float total_paid_amount;

     //purchase history
    //joe paid for stock
    joe_paid=no_of_purchase_share*per_share;

    //commission joe paid for stock
    joe_commission=joe_paid*stock_commission;
     //sale history
    //joe sold the stock,how much amount he gets
    joe_sold_stock=no_of_sold_share*per_sold_share;

    //joe paid commission to his client
    joe_sold_commission=joe_sold_stock*stock_sold_commission;

    // calculations to get profit that joe gets
    //total amount that joe gets after sale=joe_sold_stock
    total_receive_amount=joe_sold_stock;
    //total amount joe paid,we have to calculate it  by adding the paid amount for stock+double commisssion
    total_paid_amount=joe_sold_commission+joe_commission+joe_paid;

    //now profit
    joe_profit=total_receive_amount-total_paid_amount;


    //output statements
    cout<<"joe paid for stock"<<joe_paid<<endl;
    cout<<"commission joe paid for stock"<<joe_commission<<endl;
    cout<<"joe sold the stock"<<joe_sold_stock<<endl;
    cout<<"joe paid commission for stock"<<joe_sold_commission<<endl;
    cout<<"profit that joe gets in this dealing"<<joe_profit<<endl;


    return 0;
}
                                            ------------------------------------------------------------

//programming challenge 24
#include<iostream>
using namespace std;
#include<iomanip>
int main()
{
    int length_row;
    int space_end_post;
    int space_between_vines;
    int no_of_grapevines;
    float total_grapevines;

    //cout statements
    cout<<"Length of the row in feet"<<endl;
    cin>>length_row;

    cout<<"Amount of space in feet ,used by an end_past assembly"<<endl;
    cin>>space_end_post;

    cout<<"space between the vines"<<endl;
    cin>>space_between_vines;

    //calculation

    no_of_grapevines=length_row-2*space_end_post;
    total_grapevines=no_of_grapevines/space_between_vines;
     
     cout<<setprecision(2)<<fixed<<endl;
    cout<<"total grapevines\n"<<total_grapevines<<endl;

    return 0;


}
                                      ------------------------------------------------------

//programming challenge 25 word game
#include<iostream>
using namespace std;
#include<string>
int main()
{
    string name;
    string age;
    string city;
    string college;
    string profession;
    string animal;
    string pets_name;
    //cout  statements
    cout<<"what is your name?"<<endl;
    getline(cin,name);

    cout<<"what is your age?"<<endl;
    getline(cin,age);

    cout<<"what is your city?"<<endl;
    getline(cin,city);

    cout<<"what is your college?"<<endl;
     getline(cin,college);

    cout<<"what is your professsion"<<endl;
    getline(cin,profession);

    cout<<"which animal does you have?"<<endl;
    getline(cin,animal);

    cout<<"What is the name of your pet_animal"<<endl;
    getline(cin,pets_name);

    //output statemnts as word game

    cout<<"There once was a person named"<<" "<<name<<" "<<"who lived in"<<" "<<city<<"."<<" "
    <<"At the age of"<<" "<<
    age<<","<<name<<" "<<"went to college at "<<college<<"."<<name<<" Graduated and went to work as a "<<
    profession<<
    "."<<"Then, "<<name<<" "<<"adopted a(n) "<<" animal named "<<pets_name<<"."<<
    "They both lived happily ever after!"<<
    endl;

    return 0;
}
                                               ----------------------------------------------------
 //chapter 4 practice qs by tony gaddzin

//This program displays  the values of true and false,use of relational operations





#include<iostream>

using namespace std;

int main()

{

  const int x=5,y=10;

   bool true_value,false_value;



   true_value=y>x;

   false_value=x==y;



   cout<<"true value"<<true_value<<endl;

   cout<<"false value"<<false_value<<endl;



   return 0;

}

                                       -----------------------------------------------

//chkpoint 4.4





#include<iostream>

using namespace std;

int main()

{

    int a=0,b=2,x=4,y=0;

    cout<<(a==b)<<endl;

    cout<<(a!=y)<<endl;

    cout<<(b<=x)<<endl;

    cout<<(y>a)<<endl;



    return 0;



}

                                    ------------------------------------------

//chapter 4 program 4.2 without exercise



#include<iostream>

using namespace std;

#include<iomanip>

int main()

{

    const int High_score=95;

    int score1,score2,score3;

    double average;



    cout<<"Enter the 3 test score"<<endl;

    cin>>score1>>score2>>score3;



    average=(score1+score2+score3)/3.0;

    cout<<fixed<<showpoint<<setprecision(1);

    cout<<"The average of the 3 test score is\n"<<average<<endl;



    if(average>95)

    {

        cout<<"congratulations ,you have a gud academic report"<<endl;

    }

    return 0;



}

                                   -------------------------------------------------

//practice qs of the table

#include<iostream>

using namespace std;

int main()

{

    bool overtime;

    int payrate;

    



    cout<<"Give value of payrate "<<endl;

    cin>>payrate;

    if(overtime=1)

    {

        cout<<"overtime is true"<<endl;

    }

    else

    {

        cout<<"overtime is false"<<endl; 

    }



    if(overtime==true)

    {

        cout<<"invalid number\n"<<endl;

    }

    return 0;

}

                           -------------------------------------------------

//practice qs of the table

#include<iostream>

using namespace std;

int main()

{

    int value;

    



    cout<<"Give value "<<endl;

    cin>>value;



    if(value>32)

    {

        cout<<"invalid number\n"<<endl;

    }

    return 0;

}

                                     -----------------------------------------------------

//practice qs of the table
#include<iostream>
using namespace std;
int main()
{
    bool overtime;
    int payrate;
    

    cout<<"Give value of payrate "<<endl;
    cin>>payrate;
    
    cout<<"enter the bool type value of overtime"<<endl;
    cin>>overtime;
    if(overtime==1)  //here comes the error if we use only one = bcoz its the assignment operator,not the equality
    {
        cout<<"overtime is true"<<endl;
    }
      else
         {
        cout<<"overtime is false"<<endl;
         }
    payrate*=2;

    if(overtime==true)
    {
        cout<<payrate<<endl;
    }
    return 0;
}
                                        --------------------------------------------------
//This program demonstrates how a misplaed semicolon prematurely termintes an if statement

#include<iostream>
using namespace std;
int main()
{
    int x=0,y=10;

    cout<<"x is"<<x<<"y is"<<y<<endl;

    //condition
    if(x>y); //error misplaced semicolon
    {
        cout<<"x is greater than y\n";//this will always executed
    }
    return 0;
}
                                        --------------------------------------------------------
/*this program demonstrates how floating-point round off errors can make equality 
operations unreliable,ch4 4.4*/


#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	double a=1.5;
	double b=1.5;
	
	a+=0.0000000000000001;//add a little to a
	if(a==b)                     //better to use greater than and less than relational operations ==
	                               //while dealing with floating points,to prevent round off errors
	{
		cout<<"both a and b are the same"<<endl;
	}
	else
	{
		cout<<"a and b are not the same"<<endl;
	}
	return 0;
	
}

                                      ----------------------------------------------------
//chapter 4 program 4.2 without exercise

#include<iostream>
using namespace std;
#include<iomanip>
int main()
{
    const int High_score=95;
    int score1,score2,score3;
    double average;

    cout<<"Enter the 3 test score"<<endl;
    cin>>score1>>score2>>score3;

    average=(score1+score2+score3)/3.0;
    cout<<fixed<<showpoint<<setprecision(1);
    cout<<"The average of the 3 test score is\n"<<average<<endl;

    if(average=100)    //== use this not = bcoz if we use = the next statement
 always executed
    {
        cout<<"congratulations ,you have a gud academic report"<<endl;
    }
    return 0;

}
                   ------------------------------------
impotant thing to remember is there is a block of code for if statement such as

    if(Nimra==cute)
       {
          cout<<"she is a human being"<<endl;
          cout<<"she is not an alien"<<endl;
          cout<<"she is a surviver and warrior"<<endl;😂
       }
ok the above is the block of the code(if statement containing more 
than one statement)
then putting the {} is very impotant,if we do not use {}in multiple
 statement ,like

     if(Nimra==cute)

          cout<<"she is a human being"<<endl;
          cout<<"she is not an alien"<<endl;              second last
          cout<<"she is a surviver and warrior"<<endl;😂 last one

in this case the last two statements always executed,if nimra is not cute even

                      -----------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()         //chkpoint 4.5
{
	int x;
	const int y=0;
	cout<<"enter the value of the x"<<endl;
	cin>>x;
	if(x==20)
	{
		cout<<"y = "<<y<<endl;
	}
getch();
return 0;
}
                     ---------------------------------------
//chkpoint 4.6

#include<iostream>
using namespace std;
#include<iomanip>
#include<conio.h>
int main()
{
	int price;
	const float discount_rate=0.2;
	
	cout<<"Enter the value of price"<<endl;
	cin>>price;
	
	if(price>500)
	{
		cout<<setprecision(1)<<fixed<<endl;
		cout<<"discount_rate = "<<discount_rate<<endl;
	}


getch();
return 0;
}
                                            ------------------------------------------------
 

//4.7


#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	int hours;
	double payrate;
	
	cout<<"enter the hours"<<endl;
	cin>>hours;
	
	cout<<"value of payrate"<<endl;
	cin>>payrate;
	
	payrate*=1.5;    //in this program we can also use setprecision feature 
	
	if(hours>40)
	{
		cout<<"payrate is "<<payrate<<endl;
	}
	


getch();
return 0;
}
                    ------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	double sales;
	float commission_rate=0.25;
	double bonus=250;
	
	cout<<"enter the value of the sales"<<endl;
	cin>>sales;
	
  if(sales>50000)  //dont use comma after 50 like this 50,000 <it will give error>
	{
		cout<<commission_rate<<endl;
		cout<<bonus<<endl;
	}


getch();
return 0;
}
                                          -------------------------------------------------


/*This program ask the user for the two numbers as num1 and num2,num1is divided by numb2 and 
the result is displayed,before the division operation ,hoewver,num2 is tested for the value 0.
if it conatins 0 ,division will not take place*/


#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	int num1,num2;
	int x;
	
	cout<<"enter the number 1 and the number 2"<<endl;
	cin>>num1>>num2;
	
 //dont perform the calculation first ,first chk the num2 and then calculation..otherwise error
	if(num2!=0) //if num2 is not equal to 0 then perform the division
	{
		x=num1/num2;
		cout<<"display the value of x "<<x<<endl;
	}
	else
	{
		cout<<"infinity condition has  been occured"<<endl;
	}
	
	
	


getch();
return 0;
}
                            ----------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	int number;
	
	cout<<"Give value of the number"<<endl;
	cin>>number;
	
	if(number%2==0)   //use of modulus operator
	{
		cout<<"number is Even"<<endl;
	}
	else      //if else take exclusive paths
	{
		cout<<"number is odd"<<endl;
	}   
	return 0;
	
}
                     ---------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	int y;
	int x;
	
	
      cout<<"give value of y"<<endl;
      cin>>y;
      
      x=1;        //this x declaration can be made at any place as int x=1  or x=1 
                   //or after applying the condition as we have apply x=0 ,it would not effect the output
      
      if(y==100)
      {
      	
      	cout<<"The value of x "<<x<<endl;
      }
      else
      {
      	x=0;
      	cout<<" x will be "<<x<<endl;
      }

getch();
return 0;
}
                  --------------------------




#include<iostream>
using namespace std;
#include<iomanip>
#include<conio.h>
int main()
{
	double sales;
	float commission_rate=0.20;
	
	
	cout<<"Give value of sales "<<endl;
	cin>>sales;
	
	if(sales>=50000.00)
	{
		cout<<setprecision(2)<<fixed<<endl;
		cout<<"commissione_rate will be "<<commission_rate<<endl;
	}
	else
	{
		commission_rate=0.10;
		cout<<setprecision(2)<<fixed<<endl;
		cout<<"commission_rate will be in this case "<<commission_rate<<endl;
		
	}


getch();
return 0;
}
                  ----- -----------------------------
//this program demonstrates the nested-if satatement

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    char employed,recent_grad;
    
    cout<<" answer the following questions with the Y or N"<<endl;
    
    cout<<"Are you employed"<<endl;
    cin>>employed;
    
    cout<<"Are you recent graduate"<<endl;
    cin>>recent_grad;
    
    if(employed=='Y')                             
    {
    	if(recent_grad=='Y')
    	{
    		cout<<"you qualify for special interest rate"<<endl;
	    }
    }

getch();
return 0;
}
                      -----------------------------

//this program demonstrates the nested-if satatement

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    char employed,recent_grad;
    
    cout<<" answer the following questions with the Y or N"<<endl;
    
    cout<<"Are you employed"<<endl;
    cin>>employed;
    
    cout<<"Are you recent graduate"<<endl;
    cin>>recent_grad;
    
    if(employed=='Y')                             
    {
    	if(recent_grad=='Y')
    	{
    		cout<<"you qualify for special interest rate"<<endl;
	    }
        else
        {
            cout<<"You must have graduate from college in the last 2 years"<<endl;
        }
    }
    else
    {
        cout<<"You must be employed to qualify"<<endl;
    }

getch();
return 0;
}
                -------------------------------


//4.12 program

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	const int A_score=90;
	const int B_score=80;
	const int C_score=70;
         const int D_score=60; 
	
	int test_score;
	
	cout<<"Enter the test score"<<endl;
	cin>>test_score;
	
	if(test_score>=A_score)
	{
		cout<<"garde is A"<<endl;
	}
	else
	{
		if(test_score>=B_score)
		{
			cout<<"grade is B"<<endl;
		}
		else
		{
			if(test_score>=C_score)
			{
				cout<<"garde is C"<<endl;
			}
			else
			{
				if(test_score>=D_score)
				{
					cout<<"garde is D"<<endl;
				}
			}
		}
	}
	 

getch();
return 0;
}
                                 --------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	int number;
	cout<<"Enter a number"<<endl;
	cin>>number;
	
	if(number>0)
	{
		cout<<"zero\n";
	}
	if(number>10)
	{
	   cout<<"ten\n"	;
	}
	if(number>20)
	{
		cout<<"twenty\n";
	}
	else
	{
		cout<<"nothing\n";
	}


getch();
return 0;
}
                             ----- -------- -----------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
 {
	int number;
	cout<<"Enter a number"<<endl;
	cin>>number;
	
	if(number>0)
	{
		cout<<"zero\n";
	
		if(number>10)
           	{    
	             cout<<"ten\n"	;
           	
	            if(number>20)
            	{
		cout<<"twenty\n";
           	}
        }
        
        
} 
else
        {
        	cout<<"nothing\n";
        }



return 0;
}
                                        -----------------------------------------




/*now there are three types of control structures ,one is sequence control,other r selection control 
and 3rd one is the looping .Till now we are discussing about 
sequence control .now we discuss selection control..
under the head of selection control ,there comes if-else 
 statements,and their ladder plus the switch statements<3 
now we are going to code about selection structures*/
#include<iostream>
using namespace std;
int main()
{
    int age;
    cout<<"GIVE your age\n";
    cin>>age;
                                  //if else ladder
    if((age<18) && (age>0))
    {
        cout<<"you are not elligible for this post"<<endl;
    }
    else if(age==18)
    {
        cout<<"you should go abroad for higher studies"<<endl;
    }
    else if((age>18) &&(age<50))
    {
        cout<<"you are elligible for this post"<<endl;
    }
    else if(age==0)
    {
        cout<<"you are not in this cruel world"<<endl;
    }
    else
    {
    	cout<<"you live on another planet"<<endl;
    }
    

return 0;
}
                                          ----------------------------------------

//nested if-else statements

#include<iostream>
using namespace std;
int main()
{
    int a;

    cout<<"give value of a"<<endl;
    cin>>a;

    if(a>=0)
    {
        if(a==0)
        {
            cout<<"zero"<<endl;
        }
        else
        {
            cout<<"positive"<<endl;
        }
    }
    else
    {
        cout<<"Negative"<<endl;
    }
    return 0;
}
                                            ---------------------------------------------
	

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	const int A_score=90;
	const int B_score=80;
	const int C_score=70;
         const int D_score=60; 
	
	int test_score;
	
	cout<<"Enter the test score"<<endl;
	cin>>test_score;
	
	if(test_score>=A_score)
	{
		cout<<"garde is A"<<endl;
	}
	else if(test_score>=B_score)
		{
		cout<<"grade is B"<<endl;
		}
	else if(test_score>=C_score)
		{
		cout<<"garde is C"<<endl;
		}
         else if(test_score>=D_score)
		{
		cout<<"garde is D"<<endl;
		}
	else
	{
		cout<<"grade is F"<<endl;
	}
	
		
	
	 

getch();
return 0;
}
                                 
                                         -----------------------------------------------------
//chkpoint 4.16
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	int funny=7;
	int serious=15;
	funny=serious%2;
	
	if(funny!=1)
	{
		funny=0;
		serious=0;
	}
	else if(funny==2)
	{
		funny=10;
		serious=10;
	}
	else
	{
		funny=1;
		serious=1;
	}
	cout<<funny<<" "<<serious<<endl;


getch();
return 0;
}
                                      ------------------------------------------------------

//chkpoint 4.17
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	int num_books,num_coupons;
	
	cout<<"how many books are being purchased"<<endl;
	cin>>num_books;
	
	if(num_books<1)
	{
		num_coupons=0;
	}
	else if(num_books<3)
	{
		num_coupons=1;
	}
	else if(num_books<5)
	{
		num_coupons=2;
	}
	else
	{
		num_coupons=3;
	}
	cout<<"The number of coupons to give is"<<num_coupons<<endl;
	


getch();
return 0;
}
                                          ---------------------------------------------

//use of flag in boolean

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	bool flag;  //doubt in declaration 
	int sales;
	int quota;
	
	cout<<"Enter the value of sales"<<endl;
	cin>>sales;
	
	cout<<"Enter the value of quota"<<endl;
	cin>>quota;
	
	if(sales>=quota)
	{
		flag=true;
	}
	else
	{
		flag=false;
	}
	cout<<flag<<endl;
	if(flag)
	{
		cout<<"sales  met with quota"<<endl;
	}
	
	
	


getch();
return 0;
}
                                       ---------------------------------------------------
//falg as integer value

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	int flag=0;
	int sales;
	int quota;
	
	cout<<"Enter the value of sales"<<endl;
	cin>>sales;
	
	cout<<"enter the value of quota"<<endl;
	cin>>quota;
	
	if(sales>=quota)
	{
		flag=1;
	}
	else
	{
		flag=0;
	}
	cout<<flag<<endl;
	if(flag)
              {
              	cout<<"you have met your sales quota"<<endl;
              	
	
                  }
	


getch();
return 0;
}
                                                     -----------------------------------------
//uses the same program which we used as employ .....bt now with logical operators

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
   char employed,recentGrad;
   
   cout<<"Are you employed? "<<endl;
   cin>>employed;
   
   cout<<"Have you graduated from college?"<<endl;
   cin>>recentGrad;
   
   if(employed=='Y' && recentGrad=='Y')
   {
   	cout<<"You qualify for the special interest rate"<<endl;
   }
   else
   {
   	cout<<"You must be employed and have graduated from college in the past two years to qualify"<<endl;
   }
   	


getch();
return 0;
}
                                      -----------------------------------------------
//this program demostrates the logical OR operator

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	
	//constants for minimum income and years
	
	const double min_income=35000.0;
	const int min_years=5;
	
	double income;
	int years;
	
	cout<<"What is your annual income"<<endl;
	cin>>income;
	
	cout<<"how many years have you worked at a current job"<<endl;
	cin>>years;
	
	if(income>=min_income || years>min_years)
	{
	    cout<<"you qualify"<<endl;	
	}
	else
	{
		cout<<"you must earn atleast $"<<min_income<<"employed more than "<<min_years<<endl;
	}
	


getch();
return 0;
}
                                             -----------------------------------------

//this program demostrates the logical OR operator

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	
	//constants for minimum income and years
	
	const double min_income=35000.0;
	const int min_years=5;
	
	double income;
	int years;
	
	cout<<"What is your annual income"<<endl;
	cin>>income;
	
	cout<<"how many years have you worked at a current job"<<endl;
	cin>>years;
	
	if(!(income>=min_income || years>min_years))
	{
	 	cout<<"you must earn atleast $"<<min_income<<"employed more than "<<min_years<<endl;
	}
	else
	{
	
                 cout<<"you qualify"<<endl;
	}
	


getch();
return 0;
}
                                          -------------------------------------------------------
//chkpoint 4.20

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	int speed;
	
	cout<<"Give any number"<<endl;
	cin>>speed;
	
	if(speed>=0 && speed<=200)
	{
		cout<<"The number is valid"<<endl;
	}
	else
	{
		cout<<"The number is not valid"<<endl;
	}
	


getch();
return 0;
}
                                            ---------------------------------------------------
//chkpoint 2.21

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	int speed;
	
	cout<<"give value of any number"<<endl;
	cin>>speed;
	
	if(speed<0 || speed>200)
	{
		cout<<"The number is not valid"<<endl;
	}
	else 
	{
		cout<<"The number is valid"<<endl;
	}
	


getch();
return 0;
}
                                       --------------------------------------------------
//Menus
/*This program displays a menu and ask the user to make a selection.an if/else if statement
determines which item the user has entered*/


#include<iostream>
using namespace std;
#include<iomanip>
#include<conio.h>
int main()
{
	int choice;        //to hold a menu choice
	int months;       //to hold the number of months
	double charges;   //to hold the monthly charges
	
	//constants for membership rates
	const double adult=40.0;
	const double senior=30.0;
	const double child=20.0;
	
	//constants for menu choice
	const int adult_choice=1;
	const int senior_choice=2;
	const int child_choice=3;
	const int quit_choice=4;
	
	//display a menu and get a choice 
	cout<<"\t\tHealth club Memebership Menu\n\n"
	     <<"1.standard adult membership\n"
	     <<"2.senior membership\n"
	     <<"3.child citizen membership\n"
	     <<"4.Quit the program\n\n"
              <<"Enter your choice: ";
              
         cin>>choice;
         
         //set the numeric output formatting
         cout<<fixed<<showpoint<<setprecision(2);
         
         if(choice==adult_choice)
         {
         	cout<<"enter the months for which you want membership"<<endl;
         	cin>>months;
         	charges=months*adult;
         	cout<<"charges"<<charges<<endl;
         	
	}
	else if(choice==senior_choice)
	{
		cout<<"enter the months for which you want membership"<<endl;
		cin>>months;
		charges=months*senior;
		cout<<"charges"<<charges<<endl;
	}
	else if(choice==child_choice)
	{
		cout<<"enter the months for which you want membership"<<endl;
		cin>>months;
		charges=months*child;
		cout<<"charges"<<charges<<endl;
	}
	else if(choice==quit_choice)
	{
		cout<<"Quit the program"<<endl;
	}
	else
	{
		cout<<"The valid choices are from 1 to 4.Run the\n"
                      <<"program again and select one of month.\n";
	}

getch();
return 0;
}
                                        -------------------------------------------------
//Validating user output
//this test scoring program does not accept test score that are less than 0 and greater than 100

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	//constants for grade thresholds
	
	const int A_score=90;
	const int B_score=80;
	const int C_score=70;
	const int D_score=60,
	          Min_score=0,    //minimumvalid score
         	Max_score=100;   //maximum valid score
	
	int test_score; //numeric test score
	
	//get the numeric test score
	cout<<"Enter your numeric test score and I will tell you\n"
	     << "the letter grade you earned:";
         cin>> test_score;
         
         
        //validating the input and determine the grade
        
        if(test_score>=Min_score&& test_score<=Max_score)
        {
        	   //determine the letter grade
        	   
        	   if(test_score>=A_score)
        	   {
        	   	cout<<"your grade is A"<<endl;
	   }
	   else if(test_score>=B_score)
	   {
	   	cout<<"your grade is B"<<endl;
	   }
	   else if(test_score>=C_score)
	   {
	   	cout<<"your grade is C"<<endl;
	   }
	   else if(test_score>=D_score)
	   {
	   	cout<<"your grade is D"<<endl;
	   }
	   else
	   {
	   	cout<<"your grade is F"<<endl;
	   }
        }
	   else
	   {
	   	cout<<"That is invalid score.Run the program again"<<endl;
	   }
	   return 0;
	   
  }
	
	
                                        -------------------------------------------
//comparing characters and strings with realational operator
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
     char ch;
     
     cout<<"Get a digit or letter from the user"<<endl;
     cin>>ch;
     
     if(ch>='0'&&ch<='9')
     {
     	cout<<"You entered a digit"<<endl;
     }
     else if(ch>='A'&&ch<='Z')
     {
     	cout<<"you entered  an uppercase letter"<<endl;
     	
     }
     else if(ch>='a'&&ch<='z')
     {
     	cout<<"you entered an lowercase letter"<<endl;
     }
     else
     {
     	cout<<"THAt is not a digit or a letter\n"<<endl;
     }
     
getch();
return 0;
}
                                          ----------------------------------------
//coparing string objects

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    string str1="ABC";
    string str2="XYZ";
    
    if(str1<str2)
    {
    	cout<<"str 1 is less than str 2"<<endl;
    }
    else
    {
    	cout<<"str 1 is not less than str 2"<<endl;
    }
    	


getch();
return 0;
}
                                         -----------------------------------------------
//st compare

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    string name1="Mary";
    string name2="Mark";
    
    if(name1>name2)
    {
    	cout<<"marry is greater than mark"<<endl;
	    }    
    	


getch();
return 0;
}
                                            ----------------------------------------------
//string compared to string literals

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
     string name1="Mary";
     
     if(name1<"Mary jane")
     {
     	cout<<"Mary jane is greater"<<endl;
	       }	


getch();
return 0;
}
                                             -----------------------------------------------
//str compare
#include<iostream>
using namespace std;
#include<conio.h>
#include<iomanip>
#include<string>
int main()
{
	const double price_A =249.0,
                      price_B=199.0;
                      
            string part_num;
            
            cout<<"The headphone partnumbers are\n"
                <<"Noice cancelling:part number S-29A\n"
                <<"wireless:part number S-29B\n"
                <<"Enter the part number of the headphones that "
                <<"you want to purchase";
            cin>>part_num;
	   
	   cout<<fixed<<showpoint<<setprecision(2);
	   
	   if(part_num=="S-29A")
	   {
	   	cout<<"THe price is $"<< price_A<<endl;
	       }
	    else if(part_num=="S-29B")
	    {
	    	cout<<"The price is $ "<<price_B<<endl;
	    	
	        }
	        else
	        {
	        	cout<<part_num<< " is not valid"<<endl;
	        	
		   }    
	
	


getch();
return 0;
}
                                   ----------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
     char ch1='1';
     
     if(ch1==49)
     {
     	cout<<"expression is true"<<endl;
     }
     else
     {
     	cout<<"expression is false"<<endl;
     }
     	


getch();
return 0;
}
                                      ----------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
   //  string str="MaryEllen";
      if("MaryEllen"<"Mary Ellen")
      {
      	cout<<"expression is true"<<endl;
	      }
	      else
	      {
	      	cout<<"expression is false"<<endl;
		      }	


getch();
return 0;
}
                                        ----------------------------------------------------------
//coditional operator
//this program calculates a consultants charges at $50
//per hour for a minimum of 5 hours.THe ?: operator 
//adjusts hours to 5 if less than 5 hours were worked
//use of conditional operator
#include<iostream>
using namespace std;
#include<conio.h>
#include<iomanip>
int main()
{
  const double pay_rate=50.0;
  const int min_hour=5;
  
  double hours;
  double charges;
  
  cout<<"give hours"<<endl;
  cin>>hours;
  
  //conditional operator
 /* if(hours>min_hour)
  {
  	cout<<hours<<endl;
	  }
	  else
	  {
	  	cout<<min_hours<<endl;
		  } */
		  
    hours= hours>min_hour ? hours:min_hour;
    
    charges=pay_rate*hours;
    cout<<fixed<<showpoint<<setprecision(2);
    cout<<charges<<endl;		  	


getch();
return 0;
}
                                     ------------------------------------------------
//conditional operator

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
      int score;
      
      cout<<"give value of score"<<endl;
      cin>>score;
      
    /*  if(score<60)
         cout<<"your grade is:fail ";
      else
         cout<<"your grade is :pass ";  */
	
	cout<<"your grade is:"<< (score<60?"fail":"pass");	


getch();
return 0;
}
                                        -----------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()

{
     int x,y,z;
     
     cout<<"give value of x and y"<<endl;
     cin>>x>>y;
     
     z=(x>y)?1:20;
     
     cout<<z<<endl;
     	


getch();
return 0;
}
                                               --------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
     int result;
     
     cout<<"give value of result"<<endl;
     cin>>result;
     
  /*   if(result>=0)
     {
     	cout<<"The result is positive"<<endl;
	     }
	     else
     {
	     	cout<<"The result is negative"<<endl;
		     
      }	
      */
      cout<<"The result is "<<(result>=0?"positive":"neagtive");
      
      cout<<result<<endl;

getch();
return 0;
}
                                   ------------------------------------------------

/*now there are three types of control structures ,one is sequence control,other r selection control 
and 3rd one is the looping .Till now we are discussing about sequence control .now we discuss selection control..
under the head of selection control ,there comes if-else  statements,and their ladder plus the switch statements<3 
now we are going to code about selection structures*/
#include<iostream>
using namespace std;
int main()
{
    int figure;
    cout<<"GIVE figure";
    cin>>figure;

    switch(figure)
    {
        case 1:
           cout<<"MUSLIM";
           break;
        case 2:
            cout<<"Not MUSLIM";
            break;
        case 3:
            cout<<"Alive";
            break;
        case 4:
            cout<<"Dead";
            break;
    }
    return 0;
    }
                                             -------------------------------------------
//switch program

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
   char choice;
   
   cout<<"Give choice"<<endl;
   cin>>choice;
   
   switch(choice)
   {
   	case 'A':cout<<"you entered A.\n";
   	break;
   	case 'B':cout<<"you entered B\n";
   	break;
   	case 'C':cout<<"you entered C\n";
   	break;
   	default:cout<<"you did not enter A,B,C!\n";
   }	

getch();
return 0;
}
                                    ---------------------------------------------
/*THis program is craefully constructed to
use the fall through feature using switch statement*/

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    int modelNum;  //Model number
    
    //get a model number from the user
    
    cout<<"Our TVs come in three models:\n";
    cout<<"The 100, 200 ,300.which do you want?";
    cin>>modelNum;
    
    cout<<"That model has following features:\n";
    
    switch(modelNum)
    {
    	case 300:cout<<"\tpicture in a picture\n";
    	case 200:cout<<"\t   stereo sound\n";
    	case 100:cout<<"\t   remote control\n";
    	         break;
    	 default:cout<<"you can only choose 100,200"
	               <<"or 300.\n";
     }	


getch();
return 0;
}
                                              -------------------------------------------------
//fall through  to catch both upper case and the lower case letters

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    char feedGrade;
    
    //get the desired grade of feed
    
    cout<<"Our pet food is availble in three grades:\n";
    cout<<"A,B,C.which do you want for pricing for?";
    cin>>feedGrade;
    
    switch(feedGrade)
    {
    	case 'a':
    	case 'A':cout<<"30 cents per pound.\n";
    	         break;
    	case 'b':
	case 'B':cout<<"20 cents per pound.\n";
	         break;
         case 'c':
	case 'C':cout<<"10 cents per pound.\n";
	         break;
		
	default:cout<<"That is an invalid choice.\n";		             
	    	
    }	
	

getch();
return 0;
}
  
                                          -------------------------------------------------
//use of switch statements in menu system

#include<iostream>
using namespace std;
#include<conio.h>
#include<iomanip>
int main()
{
      int choice ;
      int months;
      double charges;
      
      const  double adult=40.0,
                    child=20.0,
		  senior=30.0;
		  
      const int adult_choice=1,
                child_choice=2,
	       senior_choice=3,
	       quit_choice=4;
	       
      cout<<"\thealth club membership menu\n\n"
          <<"1.standard Adult Membership\n"
          <<"2.child membership\n"
          <<"3.senior membership\n"
          <<"4.Quit the program\n\n"
          <<"Enter your choice:";
      cin>>choice;
      
      cout<<fixed<<showpoint<<setprecision(2);
      
      
      switch(choice)
      {
      	case adult_choice:
      		
      	     cout<<"For how many months?\n";
              cin>>months;
              charges=months*adult;
              cout<<"The total charges are $ "<<charges<<endl;
              break;
	     
	     
	     
	     case child_choice:
      		
      	     cout<<"For how many months?\n";
              cin>>months;
              charges=months*child;
              cout<<"The total charges are $ "<<charges<<endl;
              break;
	     
	     
	     case senior_choice:
      		
      	     cout<<"For how many months?\n";
              cin>>months;
              charges=months*senior;
              cout<<"The total charges are $ "<<charges<<endl;
              break;
	     
	     
	     case quit_choice:
	     cout<<"The valid choices are 1 through 4 .Run the\n"
	          <<"program again and select one of those.\n";
		 break;    //no need but to maintain consistency	   	
}
getch();
return 0;
}
                                      --------------------------------------------------
//chking the output

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	
    int funny=7,serious=15;
    
    funny=serious*2;
    
    switch(funny)
    {
    	case 0:cout<<"That is funny.\n";
    	       break;
         case 30:cout<<"That is serious\n";
                 break;
         case 32:cout<<"That is seriously funny\n";
                 break;
                 
         default:cout<<funny<<endl;30/07/22 15:06
    }

getch();
return 0;
}
                                           --------------------------------------------
//4.30

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
     int userNum;
     
     cout<<"Enter one of the numbers 1,2, or 3";
     cin>>userNum;
     
     switch(userNum)
     {
     	case 1:cout<<"You enter 1"<<endl;
     	       break;
     	case 2:cout<<"you enter 2"<<endl;
                break;
     	case 3:cout<<"you enter 3"<<endl;
     	       break;
         default:cout<<"1,2,3 entered"<<endl;
     	
     	
     }
     	


getch();
return 0;
}   
                                           ---------------------------------------
//4.31

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
        int selection;
        
        
        cout<<"\twhich formula do you want to see\n\n";
        cout<<"\t      1. Area of circle\n";
        cout<<"\t      2. Area of a rectangle\n";
        cout<<"\t      3. Area of a cylinder\n";
        cout<<"\t      4. None of them\n";
        cin>>selection;
        
        
        switch(selection)
        {
        	   case 1:cout<<"pi times radius squared\n";
        	          break;
        	   case 2:cout<<"length times width\n";
        	          break;
        	   case 3:cout<<"pi times radius squared times height\n";
        	          break;
        	   default:cout<<"Well,ok bye";
        }	
	


getch();
return 0;
}
                                   --------------------------------------------
//scope of variable

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
   const double min_income=35000.0;
   const int    min_years=5;
   
   cout<<"What is your annual income?";
   double income;     //variable definition
   cin>>income;
   
   if(income>=min_income)
     {
     	cout<<"How many years have you worked at"
     	     <<"your current job?\n";
         int years;   //variable definition
         cin>>years;
         
         if(years>min_years)
         {
         	cout<<"You qualify"<<endl;
	}
	else
	{
		cout<<"You must be employed for more than"
		     <<min_years <<"to qualify";
	}
    }
    else
    {
    	cout<<"you must earn atleast $"<<min_income<<"to qualify"<<endl;
    }
         
	     


getch();
return 0;
}
                                                   ----------------------------------------------------  
//variables with same name

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
	int number;
	
	cout<<"Enter a number greater than 0"<<endl;
	cin>>number;
	
	if(number>0)
	{
		int number;  //another number definition
		cout<<"Now enter another number ";
		cin>>number;
		
		cout<<"The second number you entered "
		     <<number<<endl;
	}
	cout<<"Your first number was "<<number<<endl;


getch();
return 0;
}
                                         --------------------------------------------
 #include<iostream>

using namespace std;

#include<conio.h>

int main()

{                     //q 31

   int x,y;

   

   if(y==0)

   {

   	x=100;

   	cout<<"give value of x "<<x<<endl;

   }	





getch();

return 0;

}

                                             ----------------------------------

#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

int x,y;



cout<<"give value of y"<<endl;

cin>>y;



if(y==10)        //q32

{

	x=0;

	cout<<"give value of x "<<x<<endl;

	}	

else

{

	x=1;

	cout<<"give value of x "<<x<<endl;

}



getch();

return 0;

}

                                            ----------------------------------

#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

    double sales;

    double commission_Rate;     //q33

    

    cout<<"give value of sales"<<endl;

    cin>>sales;	

    

    if(sales<=10000)

    {

    	commission_Rate=10;

    	cout<<"commission_Rate="<<commission_Rate<<"%"<<endl;

    }

    else if(sales>=10000 && sales<=15000)

    {

    	commission_Rate=15;

    	cout<<"commission_Rate="<<commission_Rate<<"%"<<endl;

    	

    }

    else if(sales>=15000)

    {

    	commission_Rate=20;

    	cout<<"commission_Rate="<<commission_Rate<<"%"<<endl;

    	

    }

    else

    {

    	cout<<"invalid range"<<endl;

    }



getch();

return 0;

}

                                        ---------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    double hours;
    bool minimum;
    
    cout<<"give value of hours"<<endl;
    cin>>hours;
    
    if(hours==10)
    {
    	minimum=true;       //q34
    }
   else
    {
        minimum=false;
    }
   cout<<minimum<<endl;

   if(minimum)
    {
	cout<<"The hours are set to ten"<<endl;
    }

getch();

return 0;
}
                                    ----------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
     double amount1,amount2;
     
     cout<<"give value of amount1"<<endl;
     cin>>amount1;
                                            //q35
     cout<<"give value of amount2"<<endl;
     cin>>amount2;
     	
     if(amount1>10 && amount2<100)
     {
     	if(amount1>amount2)
     	{
     		cout<<"amount1 is greater than amount2"<<endl;
         }
         else
         {
	     	cout<<"amount2 is greater than amount1"<<endl;
         }
     }
     else
     {
     	cout<<"Error message"<<endl;
     }
     
     
     
getch();
return 0;
}
                                -------------------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    int number;      //q36
    
    
    cout<<"give value of any number"<<endl;
    cin>>number;
    
    if(number>=0 && number<=100)
    {
    	cout<<"The number is valid"<<endl;
    }
    else
    {
	cout<<"The number is not valid"<<endl;
    	    	
    }	


getch();
return 0;
}
                                               -----------------------------------------

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    double temp;      //q37
    
    
    cout<<"give value of temperature"<<endl;
    cin>>temp;
    
    if(temp>=-50 && temp<=150)
    {
    	cout<<"The number is valid"<<endl;
    }
    else
    {
	cout<<"The number is not valid"<<endl;
    	    	
    }	


getch();
return 0;
}
                                         -------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    double hours;      //q38
    
    cout<<"give value of hours"<<endl;
    cin>>hours;
    
    if(hours<0 || hours>80)
    {
    	cout<<"The number is",
	    cout<<" not valid"<<endl;
	    }	
else
{
	cout<<"The number is valid"<<endl;
}

getch();
return 0;
}
                                      ------------------------------------------
#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
   string str1,str2;
   
   str1="Nimra";      //q39
   str2="Alia";
   
   if(str1>str2)
   {
   	cout<<"Nimra is greater than Alia"<<endl;
   }
   else
   {
	   	cout<<"Alia is greater than Nimra"<<endl;
   }	

getch();
return 0;
}
                                     ------------------------------------------------
//chapter 4 programming challenges

//challenge no 1

/*write a program that ask the user to enter two numbers.The number 
should use the conditional operator to determine which number is smaller
and which is larger*/

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
    int numb1,numb2;

    cout<<"give values of number 1 and 2"<<endl;
    cin>>numb1>>numb2;

    cout<<"The number1 is "<< (numb1>numb2 ? "greater":"less");

    return 0;
}
                                       -------------------------------------------------

//challenge no 2

/*Roman numerical conmvertor*/

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
   int num;

   cout<<"give value of number"<<endl;
   cin>>num;

   switch(num)
   {
    case 1:cout<<"I"<<endl;
           break;
    case 2:cout<<"II"<<endl;
           break;
    case 3:cout<<"III"<<endl;
            break;
    case 4:cout<<"IV"<<endl;
            break;
    case 5:cout<<"V"<<endl;
            break;
    case 6:cout<<"VI"<<endl;
            break;
    case 7:cout<<"VII"<<endl;
            break;
    case 8:cout<<"VIII"<<endl;
            break;
    case 9:cout<<"IX"<<endl;
            break;
    case 10:cout<<"X"<<endl;
            break;
    default:cout<<"out of range"<<endl;
            break;
      
   }

    return 0;
}
                                       ----------------------------------------------

//challenge no 3

//Magic-dates

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
     int month,day,year;

     cout<<"Give month"<<endl;
     cin>>month;

     cout<<"Give day"<<endl;
     cin>>day;

     cout<<"Give year"<<endl;
     cin>>year;


     if(year==month*day)
     {
        cout<<"The date is magic"<<endl;
     }
     else
     {
        cout<<"The date is not magic"<<endl;
     }

     
    return 0;


}
                                       -------------------------------------------------

//challenge no 4

//Areas of rectangle

#include<iostream>
using namespace std;
#include<conio.h>
int main()
{
        int L1,L2,W1,W2;

        long int A1,A2;

        cout<<"length of Ist rectangle"<<endl;
        cin>>L1;

        cout<<"width of 1st rectangle"<<endl;
        cin>>W1;

        A1=L1*W1;

          cout<<"length of 2st rectangle"<<endl;
        cin>>L2;

        cout<<"width of 2st rectangle"<<endl;
        cin>>W2;

        A2=L2*W2;

        if(A1>A2)
        {
                cout<<"Area of Ist rectangle is greater than 2nd rectangle"<<endl;
        }
        else if(A2>A1)
        {
                cout<<"Area of 2st rectangle is greater than 1st rectangle"<<endl;
        }
        else
        {
                cout<<"Area of both rectangles are same"<<endl;
        }
    
    return 0;
        


}  
                                  --------------------------------------------------

//challenge no 5

//body mass index

#include<iostream>
using namespace std;
#include<conio.h>
#include<cmath>
int main()
{
       double weight,kgwei,height,heifeet;
       long double BMI;

       cout<<"give weight in kg"<<endl;
       cin>>kgwei;

          weight=kgwei*2.2;     //in pounds

          cout<<"give height in feet"<<endl; //1 feet is equal to 12 inches =12*5=60inches for 5 feet
          cin>>heifeet;
          
          height=heifeet*12;
          

          BMI=weight*703/pow(height,2);
          
          cout<<"BMI"<<BMI<<endl;

          if(BMI>18.5 && BMI<25)
          {
                cout<<"person's weight is optimal"<<endl;
          }
          else if(BMI<18.5)
          {
                cout<<"person's is under weight"<<endl;
          }
          else if(BMI>25)
          {
                cout<<"person is overweight"<<endl;
          }
          else
          {
                cout<<"nothing happened"<<endl;
          }
    
    return 0;
        


}

                                     --------------------------------------------------

//challenge no 6

//mass and weight

#include<iostream>
using namespace std;
#include<conio.h>
#include<cmath>
int main()
{
       double mass,weight;

       cout<<"Give mass in kg"<<endl;
       cin>>mass;

       weight=mass*9.8;

       cout<<"***weight of the object***"<<endl;
       cout<<weight<<"N"<<endl;


       if(weight>1000)
       {
        cout<<"It's too heavy"<<endl;
       }
       else if(weight<10)
       {
        cout<<"It's too light"<<endl;
       }
       else
       {
        cout<<"Its not heavy not light either"<<endl;
       }
    
    return 0;
        


}
                                            ------------------------------------------



 



//chapter 5 



//This program demonstrates the ++ and -- operators



#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

    int num=4;  //num starts out with 4



    //Display the value in num

    cout<<"The variable num is "<<num<<endl;



    cout<<"I will now increment num\n\n";

    num++; //use postprefix to increment number

    cout<<"Now the variable num is "<<num<<endl;



    cout<<"Now I will increment num again.\n\n";

    ++num;  //use prefix to increment number

    cout<<"Now the variable num is "<<num<<endl;



    cout<<"Now I will decrement number\n\n";

    num--;   //post prefix to decremnt number

    cout<<"Now the variable num is"<<num<<endl;



    cout<<"Now I  will decrement number again\n\n";

    --num;   //prefix to increment number

    cout<<"Now the variable number is"<<num<<endl;



    return 0;





}

                                           ----------------------------------------



//chapter 5 



//This program demonstrates the prefix and postfix modes

//of the increment and decrement operators.



#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

    int num=4;  //num starts out with 4



    cout<<num<<endl;       //display 4

    cout<<num++<<endl;     //display 4

    cout<<num<<endl;       //display 5

    cout<<++num<<endl;     //display 6

    cout<<num<<endl;       //display 6

    cout<<num--<<endl;     //display 6

    cout<<num<<endl;       //display 5

    cout<<--num<<endl;      //display 4

    cout<<num<<endl;        //display 4





    return 0;





}

                                       -----------------------------------------------------



//chapter 5 



//examples



#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

     int x=1;

     int y;       //after execution x will contain 2 and y is 1

     y=x++;



     cout<<"x = "<<x<<" y ="<<y<<endl;



    return 0;





}

                                        -----------------------------------------------------

//multiplication table using for loop



#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

	

     int i;

     

     for(i=1;i<=10;i++)

     {

     	cout<<i<<"*6 ="<<i*6<<endl;

     	

     }







//multilplication table using while loop



i=1;

 while(i<=10)

 {

 	cout<<i<<"*6 = "<<i*6<<endl;

 	i++;

 }

 getch();

return 0;

}

                                     --------------------------------------------

//chapter 5 while loop



#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

     int number =0;

     

     while( number < 5)

     {

     	cout<<"hello\n";

     	number++;

     }	

    cout<<"That's all!\n";

getch();

return 0;

}

                                         ----------------------------------------------

//while lopp is a prestest loop



#include<iostream>

using namespace std;

#include<conio.h>

int main()

           //does not give any output bcoz condition gets wrong

{

      int number =6;

      

      while(number<5)

      {

         cout<<"hello\n"; 

	

 //bracket is very necessary bcoz if no then execute only one 

 //statement just after and execute infinite loop

	number++;	

      }	





getch();

return 0;

}

                                                 -----------------------------------------------

//infinite loops..dont reccommended because it takes alot space

//to create infinite loops make condition always true 

#include<iostream>

using namespace std;

#include<conio.h>

int main()



{

    int number =0;

    

    while(number<5)

    {

    	cout<<"Helloworld\n";

    }

//it is infinte lopp bcoz updation factor is absent so n=0 always and 0 always less than 5

getch();

return 0;

}

                                   -----------------------------------------------

//while loop



#include<iostream>

using namespace std;

#include<conio.h>

int main()



{

	int remainder,num;

	cout<<"Enter the number\n";

    	cin>>num;

	remainder=num%2;

	

    while(remainder==1)

    {

    	cout<<"Enter the number\n";

    	cin>>num;

    	remainder=num%2;

	    }	





getch();

return 0;

}

                                        -------------------------------------------

//infinte loop



#include<iostream>

using namespace std;

#include<conio.h>

int main()



{

    int number=0;

    

    while(number<0);  //due to this semicolon

    {

    	cout<<"helloword\n";

    	number++;

    }	





getch();

return 0;

}

                                          --------------------------------------------

//This program assists a technician in the process

//of checking  a substance's tempertaure.



#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

    const double max_temp = 102.5; 

    double temperature;

    

    cout<<"Enter the substance's celsius  temperature"<<endl;

    cin>>temperature;

    

    while(temperature>max_temp)

    {

           cout<<"Temperature is too high,\n";

           cout<<"Turn the thermostat down and wait for 5 mint,\n";

           cout<<"Then take celsius again,and enter it here,\n";

           cin>>temperature;

    }

    //Remind the technician to chk the tempewrature after 15 moinutes

    

    cout<<"The temperature is acceptable .\n";

    cout<<"chk it again in 15 minutes.\n";	



getch();

return 0;

}

                                      ---------------------------------------------------

//while loop as input validation

//enter the number in the range 1 to 100

#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

   int number;

   

   cout<<"Enter the number in the range 1 to 100"<<endl;

   cin>>number;

   

   while(number<1 || number>100 )

        {

   	cout<<"Error message:Enter number between range"<<endl;

   	cin>>number;

        }	





getch();

return 0;

}

                                  -------------------------------------------------------------

//This program calculates the number of soccer teams

//that a youth league may create from the number of avaible 

//players.input validation is demonstrated with while loop



#include<iostream>

using namespace std;

#include<conio.h>

int main()



{

   const int min_player=9;

   const int max_player=15;

   

   int players,

     team_players,

     numteams,

     leftover;

     

     cout<<"how many players do you wish per team?";

     cin>>team_players;

     //validate the input

     while(team_players<min_player||team_players>max_player)

        {

        	//get the input again

        	cout<<"how many players do you wish per team?";

         cin>>team_players;

        }

        

        //get the number of players available

        cout<<"how many players are available?";

        cin>>players;

     //validate the input

     

     while(players<=0)

     {

     	//get the number of players available again,greater than zero

        cout<<"how many players are available?";

        cin>>players;

     }

     

     //calculates the number of teams

      numteams=players/team_players;

      

      //calculates the leftover 

      leftover =players %team_players;

      

      //getting the results

      cout<<"There will be "<<numteams<<" teams with "<<leftover<<" players leftover \n";

     

     return 0;

        

}



                                       ------------------------------------------------

//chkpoint 5.2



#include<iostream>

using namespace std;

#include<conio.h>

int main()



{

     int number;

     //within the range of 10 through 25

     cout<<"Give value of number"<<endl;

     cin>>number;

     

     while(number<10 || number>25)

     {

     	cout<<"Error:Give value of number"<<endl;

     	cin>>number;

     }

          cout<<"input is valid"<<endl;



getch();

return 0;

}

                                    -----------------------------------------------

//chkpoint 5.3



#include<iostream>

using namespace std;

#include<conio.h>

int main()



{

   char ch;

   

   cout<<"Enter Y,y,N,n"<<endl;

   cin>>ch;

   

   while(ch!='y' && ch!='Y' && ch!='N' && ch!='n' )

   {

      	cout<<"Enter Y,y,N,n"<<endl;

         cin>>ch;

   }

   cout<<"okkay,valid input"<<endl;	





getch();

return 0;

}

                                  -----------------------------------------------

//5.4chkpoint



#include<iostream>

using namespace std;

#include<conio.h>

int main()



{

      	

    string str1="yes";

    string str2="No";

    string str;

    

    cout<<"Enter the string"<<endl;

    cin>>str;

    

    while(str!="yes" && str!="No")

    {

    	 cout<<"Error message"<<endl;

    	 cout<<"Enter the string"<<endl;

          cin>>str;

    }

    cout<<"valid data"<<endl;

    



getch();

return 0;

}

                                              -----------------------------------------------

//do-while loop is a post test loop

#include<iostream>

using namespace std;

#include<conio.h>

int main()



{

      int x=1;

      do

      {

      	cout<<x<<endl;

      }	while(x<0);





getch();

return 0;



}

                                                    --------------------------------------

//This program average 3 test scores.It repeats as

// many times as the user wishes

#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

     int score1,score2,score3;

     double average;

     char again;

     

     do

     {

     	//get three scores

     	cout<<"Enter the three test score and I will average them:";

     	cin>>score1>>score2>>score3;

     	

     	//calculates and display the average

     	average=(score1+score2+score3)/3.0;

     	cout<<"The average is "<< average <<endl;

     	

     	cout<<"Do you want to average another set?(Y,N)";

     	cin>>again;

     }	while(again=='Y'||again=='y');

getch();

return 0;

}

                                     -----------------------------------------------

//This program dispalys a menu and asks the user to make

//a selection.A do-while loop repeats the program until 

//the user selects item 4 from the menu.



#include<iostream>

using namespace std;

#include<iomanip>

#include<conio.h>

int main()

{

    //contants for menu choices	

    const int adult_choice =1,

              child_choice =2,

	     senior_choice=3,

	     quit_choice  =4;

	     

    //constants for membership rates

    const double adult =40.0,

                 child =20.0,

                 senior=30.0;

                 

    //variables

    

    int choice;

    int months;

    double charges;

    

    //set a numeric output formatting

    cout<<fixed<<showpoint<<setprecision(2);

    

    do

    {

    	//display the menu

    	

    	cout<<"\n\t\tHealth club membership menu\n\n"

             <<"1.Standard adult membership\n"

             <<"2.Child membership\n"

             <<"3.senior citizen membership\n"

             <<"4.quit the program\n"

             <<"Enter your choice:";

         cin>>choice;

         

         //validate the menu input

         while(choice<adult_choice || choice>quit_choice)

         {

         	cout<<"please enter a valid menu choice:";

         	cin>>choice;

	}

	

	//process the user choice

	if(choice!=quit_choice)

	{

		//get the number of months

		cout<<"For how many months"<<endl;

		cin>>months;

		

	//respond to user menu selection

	switch(choice)

           	{

		case adult_choice:

			charges=months*adult;

			break;

		case child_choice:

			charges=months*child;

			break;

		case senior_choice:

			charges=months*senior;

			break;

		}

	// display the monthly charges

	cout<<"The total charges are $"<<charges<<endl;	

	}

    }while(choice!=quit_choice);

	return 0;

}

	     	

                                              -------------------------------------------

//chkpoint 5.5 (B)



#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

    int v =10;

    

    do

    {

    	cout<<v<<endl;

    }while(v<5);  //ouput 10	

	





getch();

return 0;

}

                                   -------------------------------------------------

//chkpoint (c)



#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

        int count=0;

        int number=0;

        int limit=4;

        

        do

        {

        	number += 2;

        	count++;

        }while(count <limit);

        

        cout<<number<<" "<<count <<endl;	



getch();

return 0;

}

                                          --------------------------------------------

//for loop



#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

   int number;

   

   for(number=0;number<5;number++)

   {

   	cout<<"hello world"<<endl;

   }

   cout<<"thats all\n";	





getch();

return 0;

}

                                       ----------------------------------------------

//this program displays the numbers between 1 to 10



#include<iostream>

using namespace std;

#include<conio.h>

int main()





{

    const int min_number=1;

    const int max_number=10;

    int number;

    

    for(number=min_number;number<=max_number;number++)

    {

       cout<<number<<"\t\t"<<(number*number)<<endl;	

    }	





getch();

return 0;

}

                                         -------------------------------------------

//use of updation twice changes the final-results



#include<iostream>

using namespace std;

#include<conio.h>

int main()



{

    int x;

    

    for(x=1;x<=10;x++)

    {

    	cout<<x<<endl;

    	x++;  //wrong changes the results

    }	

     	





getch();

return 0;

}

                                 ----------------------------------------------------

//other forms of updation



#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

    int num;

    

    for(num=2; num<=100; num +=2)

    {

        cout<<num<<endl;	

    }	



getch();

return 0;

}

                                --------------------------------------------------

//other form of updation

#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

      int num;

      

      for(num=10; num>=0 ; num--)

      {

      	cout<<num<<endl;

      }	

	



getch();

return 0;

}

                                ---------------------------------------------------------

//if not use brackets in the loop

#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

	int i;

    for(int i=1;i<=10;i++)

    cout<<i<<endl;

    //if we dont put bracket it uses only 

    //the statement just after 

    cout<<"count is "<<i<<endl; //it is giving error bcoz i is 

                                //initializatoion only in the loop ,not

	//still creates the error		     //outside the loop	

 

//yopu cannot acess the variable outside the loop	



getch();

return 0;

} 

                                   ----------------------------------------------

//This program demosntrates a user-controlled for loop



#include<iostream>

using namespace std;

#include<conio.h>

int main()



{

    int min_number,

        max_number;

        

     //get the minimum maximum values to display

     

     cout<<"I will display a number of tablesand their squares\n";

     cout<<"Enter the starting number";

     cin>>min_number;

     cout<<"Enter the ending number";

     cin>>max_number;

     

     //display the table

     

     cout<<" number number squared\n"

         <<"------------------------\n";

	

    for(int num =min_number;num<=max_number;num++)

    {

    	cout<<num<<"\t\t"<<(num*num)<<endl;

    }

return 0;

}

                                      ---------------------------------------------

//two initialization



#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

	

	int x,y;

	

	for(x=1,y=1;x<=5;x++)

	{

		cout<<x<<" plus "<<y<<" equals "<<(x+y)<<endl;

	}



getch();

return 0;

}

                              ------------------------------------------

//use of two updation with two initializatoion

#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

    int x,y;

    for(x=1,y=1;x<=5;x++,y++)

    {

    	 cout<<x<<" plus "<<y<<" equals "<<(x+y)<<endl;

    }	

 	



getch();

return 0;

}

                                    -----------------------------------------

//ways to use for loop

#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

    const int maxvalue=10;

    int num =1;

    

    for(;num <= maxvalue; num++)	

        cout<< num <<"\t\t"<<num*num<<endl;





//int num =1;

    

    for(;num <= maxvalue; )

    {

        cout<< num <<"\t\t"<<num*num<<endl;

        num++;

    }

getch();

return 0;

}

                                        --------------------------------------------

//infinte loop



#include<iostream>

using namespace std;

#include<conio.h>

int main()



{

    for( ; ; )	

    cout<<"heloo worlddd\n";

   //no way of stopping



getch();

return 0;

}

                                      ------------------------------------------------

//this program converts the speeds 60kph through 

//130kph (in 10kph increments) to mph.



#include<iostream>

using namespace std;

#include<iomanip>

#include<conio.h>

int main()

{

     //constants for the speeds

     const int start_kph=60,

               end_kph=130,

	      increment=10;

	     

     //contant for the conversion factor

     const double conversion_factor	=0.6214;

     

     //variables

     int kph;

     double mph; 

     

     //set the numeric output formatting

     cout<<fixed<<showpoint<<setprecision(1);

     

     //display the table heading

     cout<<"kph\tmph\n";

     cout<<"-------------------\n";

     

     //display the speeds

     for(kph=start_kph;kph<=end_kph;kph+=increment)

     {

     	//calculates mph

     	mph=kph*conversion_factor;

     	

     	//display the speeds in kph and mph

     	cout<< kph <<"\t"<<mph<<endl;

     }

getch();

return 0;

}

                                      -----------------------------------------------

//chk point 5.7



#include<iostream>

using namespace std;

#include<conio.h>

int main()



{

     int count;

     

     for(count=0;count<50;count++)

     {

     	cout<<"I love to program\n";

     }	

	





getch();

return 0;

}

                                          --------------------------------------

//ckpoint 5.8 (A)

#include<iostream>

using namespace std;

#include<conio.h>

int main()



{

     int count;

     for(count=0;count<6;count++)

     {

     	cout<<(count+count);

     }	

getch();

return 0;

}

                                     --------------------------------------------

//finding output

#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

    for(int value =-5;value<5;value++)

    cout<<value;	

	



getch();

return 0;

}

                                       ----------------------------------------------

//c part



#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

    int x;

     for(x=5; x<=14; x+=3)

      cout<<x<<endl;

     cout<<x<<endl;	

	



getch();

return 0;

}

                                      ----------------------------------------

//chkpoint 5.9



#include<iostream>

using namespace std;

#include<conio.h>

int main()



{

   for(int i=0; i<10; i++)

   {

   	cout<<"Nimra\n";

   }	

    



getch();

return 0;

}

                                    --------------------------------------------

//chk point 5.10



#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

	for(int i=1;i<=49;i+=2)

	{

		cout<<i<<endl;

	}

getch();

return 0;

}

                              ------------------------------------------------------

//5.11 chkpoint



#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

   for(int i=0;i<=100;i+=5)

   {

      cout<<i<<endl;	

   }	



getch();

return 0;

}

                                 ---------------------------------------------

 //write a program that inputs age in yeras and dispalay age in days and months

#include<iostream>

using namespace std;

int main()

{

    int age_Year;

    int age_months;

    int age_days;



    cout<<"give your age in years"<<endl;

    cin>>age_Year;

    age_months=age_Year*12;

    age_days=age_Year*365;



    cout<<"age_months"<<age_months<<endl;

    cout<<"age_days"<<age_days<<endl;



    return 0;

}

                                   ------------------------------------------



/*Write a program that  will prints a text of four lines consisting of characters,integer values,and floating point 

values using the cout statements*/

#include<iostream>

using namespace std;

#include<conio.h>

int main()

{

    string ch ="I am julleiat";

    int date_birth=3;

    float av=3.24;



    cout<<ch<<endl;

    cout<<date_birth<<endl;

    cout<<av<<endl;



    return 0;



}

                                   ------------------------------------------------



/*write a program that inputs radius from user.it calculates its volume and surface area using the formula Area=4pir^2 

and circumference 4/3pir^3 where pi=3.14*/



#include<iostream>

using namespace std;

#include<conio.h>

#include<cmath>

int main()

{

     const float pi=3.14;

     int r;

     float Area;

     float Volume;

     cout<<"Give value of r"<<endl;

     cin>>r;

    //calculation

   

    Area=(4)*pi*(pow(r,2));

    Volume=(4.0/3.0)*pi* (pow(r,3));

    cout<<"Area of the circumference"<<Area<<endl;

    cout<<"Volume of the circumference"<<Volume<<endl;



    return 0;



}

                                       ------------------------------------------------------

/*write a program to find out the area of triangle when the three sides of the triangle is given a,b,c.use appropriate 
statements to input the values of a,b,c from the keyboard.The formula of the triangle
                       Area=(s(s-a)(s-b)(s-c))^1/2 where s=(a+b+c)/2     */
#include<iostream>
using namespace std;
#include<cmath>
#include<iomanip>
int main()
{
    float a,b,c;
    float s;
    double Area;
    cout<<"Give value of a"<<endl;
    cin>>a;
    cout<<"Give value of b"<<endl;
    cin>>b;
    cout<<"Give value of c"<<endl;
    cin>>c;
    //calculation
    s=(a+b+c)/2.0;
    cout<<"The value of s\n"<<endl;
    cout<<s<<endl;
    Area=sqrt(s*((s-a)*(s-b)*(s-c)));
    cout<<"Area of the triangle\n"<<endl;
    cout<<setprecision(5)<<Area<<endl;


    return 0;

}
                           -----------------------------------------------------
/*write a program that inputs a miles from the user and convert miles into kilometer.one mile is equal to
1.609 kilometers*/
#include<iostream>
using namespace std;
int main()
    {
        float miles;
        cout<<"Give miles"<<endl;
        cin>>miles;
        float kilometers;
        kilometers=1.609/miles;
        cout<<"kilometers\n"<<kilometers<<endl;
        return 0;

    }
                            --------------------------------------------------------
//write a program that input 4 numbers and calculates the sum ,average, and product of all numbers
#include<iostream>
using namespace std;
int main()
{
    int a,b,c,d;
    cout<<"Give the value of a,b,c,d"<<endl;
    cin>>a>>b>>c>>d;
    int sum;
    sum=a+b+c+d;
    cout<<"sum"<<sum<<endl;
    float average;
    average=sum/4;
    cout<<"average"<<endl;
    cout<<average<<endl;
    double product;
    product=a*b*c*d;
    cout<<"product value"<<product<<endl;
    return 0;
}
                            ----------------------------------------------------------
//write a program in which a number is asked from the user and displays its square and cube
#include<iostream>
using namespace std;

#include<cmath>
int main()
{
    int number;
    cout<<"give any number"<<endl;
    cin>>number;
    int square;
    int cube;
    square=pow(number,2);
    cube=pow(number,3);

    cout<<"Give value of square of a number\n"<<endl;
    cout<<square<<endl;
    cout<<"Give value of cube of a number\n"<<endl;
    cout<<cube<<endl;


   return 0;


}
                                  ---------------------------------------------------

/*write a program that inputs total pages of a book ,number of pages a person reads in one day and number of days 
a person has read the book.it displays the number of pages that have been read and number of pages remaining*/
#include<iostream>
using namespace std;
int main()
{
    int total_pages, read_pages,read_days;
    int completed_pages,remaining_pages; 
    cout<<"Give the total pages of the book"<<endl;
    cin>>total_pages;
    cout<<"how many pages you read in a day"<<endl;
    cin>>read_pages;
    cout<<"how many days you read book"<<endl;
    cin>>read_days;
    //calculation
    completed_pages=read_pages*read_days;
    remaining_pages=total_pages-completed_pages;

    cout<<"completed pages"<<completed_pages<<endl;
    cout<<"remaining pages"<<remaining_pages<<endl;

    return 0;

}
                              --------------------------------------------------
/*A car can travel 3.5 miles in one liter .write a program that inputs petrol in liters and displays how
much distance the car cover using the available liter*/

#include<iostream>
using namespace std;
int main()
{
    float miles=3.5;
    float liters;
    double distance;

    cout<<"how many liters that a car has"<<endl;
    cin>>liters;
    distance=liters*miles;

    cout<<"the car covered the distance "<<endl;
    cout<<distance;

    return 0;

}
                                ------------------------------------------------
/*write a program that inputs the total number of students and fee per student.It displays the total fee collected
from the class*/
#include<iostream>
using namespace std;
int main()
{
    int total_students;
    int fee_perstudent;
    int total_fee;
    cout<<"total students of the class"<<endl;
    cin>>total_students;
    cout<<"fee per student"<<endl;
    cin>>fee_perstudent;
    total_fee=total_students*fee_perstudent;

    cout<<"total_fee"<<total_fee<<endl;
    return 0;
}
                              --------------------------------------------------------
/*write a program that inputs a temperature from user in Fahrenheit and convert it to celcius by using the formula
       C=5/9(F-32)       */

#include<iostream>
using namespace std;
int main()
{
    float tempF;
    float tempC;
    cout<<"Enter the temp in fahrenheit\n";
    cin>>tempF;

    tempC=(5.0/9)*(tempF-32);

    cout<<"result in celcius\n";
     cout<<tempC;

     return 0;
    

    
}
                  ----------------------------------------------------------------------

/*write a program that inputs 3 _digit number and display digits in separate  three lines...for example if a user 123
the output should display like this
1
2                          important concept
3
*/
#include<iostream>
using namespace std;
int main()
{
    int n,a,b,c;
    cout<<"Give value of n\n";
    cin>>n;

    a=n/100;
    n=n%100;
    b=n/10;
    c=n%10;

    cout<<a<<endl;
    cout<<b<<endl;
    cout<<c<<endl;

    return 0;


}
                         -------------------------------------------------------------------
/*write a program to show the follwing output
          2  3  4  5  6   
          3  5  6  7  8    */
#include<iostream>
using namespace std;
int main()
{
    cout<<" 2  3  4  5  6\n";
    cout<<" 3  5  6  7  8";
    return 0;
}
                       --------------------------------------------------------------------------

/*WAP that calculates the volume of a cube (v) by taking the input from the user having the setprecision of 3 ,always show the decimal point 
formula is V=length*width*height*/

#include<iostream>
using namespace std;
#include<iomanip>
int main()
{
float length,width,height;
double volume;

cout<<"give value of length"<<endl;
cin>>length;

cout<<"give value of width"<<endl;
cin>>width;

cout<<"give value of height"<<endl;
cin>>height;

volume=length*width*height;
cout<<setprecision(3)<<endl;
cout<<"volume of the cube"<<volume<<endl;

return 0;


}
                                    ---------------------------------------------------------
/*WAP that inputs the  x, y  co-ordinates for two points and computes the distance between the two points
      distance=((x2-x1)+(y2-y1))1/2
      */
#include<iostream>
using namespace std;
#include<cmath>
int main()
{
    int x1,x2,y1,y2;
    int distance;

    cout<<"give value of x1 and x2"<<endl;
    cin>>x1>>x2;

    cout<<"give value of y1 and y2"<<endl;
    cin>>y1>>y2;

    distance=sqrt((x2-x1)+(y2-y1));   //we can also use pow function

    cout<<"distance"<<distance<<endl;
    return 0;
} 
                                   --------------------------------------------------------------
//WAP to swap  values of 3 variable by using the fourth variable
#include<iostream>
using namespace std;
int main()
{
    int a,b,c,d;

    cout<<"enter the values of a,b,c"<<endl;
    cin>>a>>b>>c;
    cout<<"old values"<<endl;
    cout<<a<<" "<<b<<" "<<c<<" "<<endl;

    d=a+b+c;
    b=d-(b+c);                           imp concept
    c=d-(b+c);
    a=d-(b+c);

    cout<<"new values"<<endl;
    cout<<a<<" "<<b<<" "<<c<<" "<<endl;
    return 0;
    }
                                        ---------------------------------------------------------
/*WAP that calculates the arc of length of a convex lens by taking radius of arc and angle made by arc.
                   length=radius*angle   */

#include<iostream>
using namespace std;
int main()
{
    float angle;
    int radius;
    double length;

    cout<<"give value of angle"<<endl;
    cin>>angle;

    cout<<"give value of radius "<<endl;
    cin>>radius;

    length=radius*angle;

    cout<<"length os an arc"<<length<<endl;

    return 0;
}
                                       ---------------------------------------------------
//WAP that computes the area of the sector of the circle when theta is the angle between their radiii in radians.

#include<iostream>
using namespace std;
int main()
{
    float radius;
    float theta;
    double area;

    cout<<"give the value of radius"<<endl;
    cin>>radius;

    cout<<"give the value of theta"<<endl;
    cin>>theta;

    area=((radius*radius)*(theta))/2.0;

    cout<<"give the area of the sector"<<endl;
    cout<<area<<endl;

    return 0;
}
                                          --------------------------------------------------

//WAP that reads that reads a positive number and then computes the logarithm of that value to the base 2

#include<iostream>
using namespace std;
#include<cmath>
int main()
{
    float n;
    float x;
    cout<<"give value of n"<<endl;
    cin>>n;

    x=log(n)/log(2.0);

    cout<<"give the value of x"<<endl;
    cout<<x<<endl;

    return 0;
}
                              ------------------------------------------------------------------------
//WAP that enters a letter and display the next two letters
#include<iostream>
using namespace std;
int main()
{
    char any_letter;
    cout<<"give any letter"<<endl;
    cin>>any_letter;

    cout<<"Dispaly next two letters"<<endl;
    cout<<char(any_letter+1)<<endl;
    cout<<char(any_letter+2)<<endl;

    return 0;
}
                      ------------------- ---------------------------------------------------
//WAP that inputs 5 integers through the keyboard and display their sum

#include<iostream>
using namespace std;
int main()
{
    int n1,n2,n3,n4,n5;
    int sum;
    cout<<"enter 5 integers from keyboard"<<endl;
    cin>>n1>>n2>>n3>>n4>>n5;

    sum=n1+n2+n3+n4+n5;

    cout<<"sum"<<sum<<endl;
    return 0;


}
                               ----------------------------------------------------------
//WAP that inputs 5 digit integer through the keyboard and display their sum

#include<iostream>
using namespace std;
int main()
{
    int number,last_digit,next_digit,total;
    cout<<"enter the number whose sum of digits is to be calculated"<<endl;
    cin>>number;

    last_digit=number%10;
    total=last_digit;
    next_digit=(number/10)%10;
    total=total+next_digit;
    next_digit=(number/100)%10;
    total=total+next_digit;
    next_digit=(number/1000)%10;
    total=total+next_digit;
    next_digit=(number/10000)%10;
    total=total+next_digit;
    cout<<"the sum of digits you entered"<<endl;
    cout<<total;
    

    return 0;


}
                           -------------------------------------------------------------------
//WAP that inputs the basic salary and calculates 35% dearness allowance,25% house rent,then dispaly gross salary
#include<iostream>
using namespace std;
int main()
{
    float basic_salary;
    float dearness_allowance;
    float house_rent;
    float gross_salary;

    cout<<"enter the basic salary"<<endl;
    cin>>basic_salary;

    dearness_allowance=basic_salary*0.35;
    house_rent=basic_salary*0.25;
    gross_salary=basic_salary+dearness_allowance+house_rent;

    cout<<"dearness allowance"<<dearness_allowance<<endl;
    cout<<"house rent"<<house_rent<<endl;
    cout<<"gross salary"<<gross_salary<<endl;

    return 0;
}
                              ---------------------------------------------------------------
//WAP that inputs two times in hh:mm:ss foramt ,adds both times  and display the total times
#include<iostream>
using namespace std;
#include<iomanip>
int main()
{
    int h1,h2,h,m1,m2,m,s1,s2,s;
    cout<<"ENter two times in the format hh:mm:ss"<<endl;
    cin>>h1>>m1>>s1>>h2>>m2>>s2;

    s=s1+s2;
    m=m1+m2;
    h=h1+h2;            //doubted program
    

    cout<<setw(2)<<h<<endl;
    cout<<setw(2)<<m<<endl;
    cout<<setw(2)<<s<<endl;

    return 0;
}
                            ----------------------------------------
//WAP that inputs two times in hh:mm:ss foramt ,adds both times  and display the total times
#include<iostream>
using namespace std;
#include<iomanip>
int main()
{
    int h1,h2,h,m1,m2,m,s1,s2,s;
    cout<<"ENter two times in the format hh:mm:ss"<<endl;
    cin>>h1>>m1>>s1>>h2>>m2>>s2;

    s=s1+s2;
    m=m1+m2+(s/60);              //% netralizes the / effect becomes m1+m2+0  doubt
    h=h1+h2+(m/60);
    s=s%60;
    m=m%60;                         //doubted program

    cout<<setw(2)<<h<<endl;
    cout<<setw(2)<<m<<endl;
    cout<<setw(2)<<s<<endl;

    return 0;
}
                                               --------------------------------------------------------

/*WAP that inputs principle amount ,rate of interest,and total time.It calculates the compound interest and displays it.The formula
for compund interest is :p(1+r/100)^t-p where p is the proinciple amount ,r is the rate and t is the total time*/

#include<iostream>
using namespace std;
#include<cmath>
int main()
{
    float P_amount;
    float r_interest;
    float t_time;
    double c_interest;
     long double tc_interest;

    //cout statement
    cout<<"principle amount"<<endl;
    cin>>P_amount;

    cout<<"rate of interest"<<endl;
    cin>>r_interest;

    cout<<"total time"<<endl;
    cin>>t_time;

    //calculation

    c_interest=P_amount*pow((1.0+(r_interest/100)),t_time);
    tc_interest=c_interest-P_amount;

    cout<<"compund interest"<<showpoint<<tc_interest<<endl;

    return 0;
}
                                        --- -----------------------------------------
#include<iostream>
using namespace std;
int main()
{
    int number;

    cout<<"give value of the number"<<endl;
    cin>>number;

    cout<<char(number)<<endl;

    return 0;
}
                                         ------------------------------------------------
/*wite a program that displays the following output
      Number           square        cube
      1                  1             1
      2                  4             8
      3                  9             27
      4                  16            32
      5                  25            125     */

      #include<iostream>
      using namespace std;
      #include<iomanip>
      int main()
      {
        cout<<1<<setw(10)<<1<<setw(10)<<1<<endl;
        cout<<2<<setw(10)<<2*2<<setw(10)<<2*2*2<<endl;
        cout<<3<<setw(10)<<3*3<<setw(11)<<3*3*3<<endl;
        cout<<4<<setw(11)<<4*4<<setw(10)<<4*4*4<<endl;
        cout<<5<<setw(11)<<5*5<<setw(11)<<5*5*5<<endl;

        return 0;
        
      }
                                   ---------------------------------------------------------

//WAP that inputs marks obtained by a student in five subjects.it then calculates a the total marks and display its percentage
#include<iostream>
using namespace std;
int main()
{
    int subj_1,subj_2,subj_3,subj_4,subj_5;
    int total_marks;
    float per;

    cout<<"enter the marks of the student in 5 subjects"<<endl;
    cin>>subj_1>>subj_2>>subj_3>>subj_4>>subj_5;
     
     //calculation
     total_marks=subj_1+subj_2+subj_3+subj_4+subj_5;
     per=(total_marks/1000.0)*100.0;


     cout<<per<<endl;

     return 0;



}
                                    ---------------------------------------------------------
/*write a program that accepts a character and determines whether 
it is a lowercase letter .If the entered character is a lowercase
letter ,display the message "The entered character is lowercase 
letter" otherwise display the message " The entered charcter
is not a lowercase letter*/


#include<iostream>
using namespace std;
#include<conio.h>
int main()

{
      char ch;
      
      cout<<"Give ch"<<endl;
      cin>>ch;
      
      if(ch>='a' && ch<='z' )
      {
      	cout<<"The entered character is a lowercase letter"<<endl;
      }
      else
      {
      	cout<<"The entered character is not a lowercase letter"<<endl;
      }	


getch();
return 0;
}
                                         ----------------------------------------------
/*senior sales person is paid Rs.400 a week and junior
sales person is paid Rs.275 .Write a program that accepts 
as input the sales person status in the character variable 
status .If the status is 's' or 'S' display the salary of 
senior sales person if the status is 'j' 'J' then display 
the salary of junior sales person,otherwise display the error 
message*/

#include<iostream>
using namespace std;
#include<conio.h>
int main()

{
   double senior_week=400.0;
   double junior_week=275.0;
   double senior_salary;
   double junior_salary;
   
   senior_salary=senior_week*4; 
   junior_salary=junior_week*4;
   
   char status;
   
   cout<<"Give status"<<endl;
   cin>>status;
   
   if(status=='s'||status=='S')
   {
      cout<<"senior_salary ="<<senior_salary<<endl;	
   }
   else if(status=='j'||status=='J')
   {
      cout<<"Junior_salary ="<<junior_salary<<endl;	
   }
   else
   {
      cout<<"Error message"<<endl;	
   }	


getch();
return 0;
}
                                           -------------------------------------------
      AUTHOR:NIMRA BASHIR                                  

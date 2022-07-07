# Solo-Project
class HelloWorld {
  static void Main() {
    // set price of 3 meals
    double price1=15.67;
    double price2=12.99;
    double price3=24.54;
    // set tip 
    double tip=0.15;
    // add cost of all meals to get total amount without tip 
    double tot=price3+price2+price1;
    // calculate tip amount
    double tprice=tip*tot;
    // calculate total amount including tip 
    double total=tot+tprice;
    // calculate amount each guest will pay after splitting evenly
    double amount=total/3;
    // display all calculated results
    Console.WriteLine("Total of all 3 meals without tip: "+tot.ToString("C"));
    Console.WriteLine("Total amount of tip: "+tprice.ToString("C"));
    Console.WriteLine("Total amount of bill including tip: "+total.ToString("C"));
    Console.WriteLine("Total amount each guest will pay if they split it evenly: "+amount.ToString("C"));
  }



else if(choice==3)
{
	  // 1cm = 0.032808399 feet
	  // declare variables
  	double centimetres;
    double feet, rate;
			
	  //assign values
	  rate = 0.032808399;
			
	  //ask to input centimetre values
	  Scanner input = new Scanner(System.in);
	  System.out.println("Enter value in Centimetres:");
	  centimetres = input.nextDouble();
			
	  //calculate feet
	  feet =  Math.round((rate * centimetres)*100.0)/100.0;
	
	  //display total
	  System.out.println("Converted value in Feet:"+feet); 
	  
      }

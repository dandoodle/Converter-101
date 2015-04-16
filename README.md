
       else if(choice==3)
       {
       // 1cm = 0.032808399 feet
       // declare variables
       double centimetres;
       double feet, rate;
       
       rate = 0.032808399; //assign values
       
       Scanner input = new Scanner(System.in);                         //ask to input centimetre values
       System.out.println("Enter value in Centimetres:");
       centimetres = input.nextDouble();
       
       feet =  Math.round((rate * centimetres)*100.0)/100.0;           //calculate feet
       
       System.out.println("Converted value in Feet:"+feet);            //display total
       
       }

# NFL-All-Stars-
Demonstration of Java Arrays



/*
* File: My Top 10 NFL AllStars
* Author: Sidney Beatty
* Date: April 16, 2019
* Purpose: This program demonstrates the creation
* and use of Java arrays 
*/

import java.util.Arrays;     
 class MyTop10NFLAllStars {

 static final int HALLAFAME = 15;
 static final int PLAYERSAGES = 15;
    
    // Main method
 public static void main(String args[]){
 System.out.println("Lets see who my Top 10 NFL AllStars are");
  
  // Creating int array for Players Ages
     int[] playersAges = new int[PLAYERSAGES];
     
     // Generate Random ages
 for (int i=0; i<playersAges.length; i++) {
playersAges[i] = (int) (Math.random() * 30)  + 30;
 }
     
     
     
     
     // Creating String array for AllStar Players
     String[] allstarValues = new String[HALLAFAME];
     
         
 allstarValues[5] = " Tom Brady";    
   allstarValues[0] = "Ray Lewis";
     allstarValues[1] = "Ed Reed";
      allstarValues[2] = "Johnathan Odgen";
       allstarValues[8] = " Julio Jones"; 
        allstarValues[12] = " Deion Sanders";  
         allstarValues[4] = "Shannon Sharpe";
          allstarValues[6] = " Hines Ward"; 
           allstarValues[9] = " Troy Polamalu ";
            allstarValues[3] = "Brett Favre";    
             allstarValues[11] = " Ozzie Newsome";
               allstarValues[13] = " Jerry Rice ";
                allstarValues[10] = " Derrelle Revis ";     
                 allstarValues[7] = " Randy Moss";
                  allstarValues[14] = " Randal Cunningham"; 
     
     // Print Results
    System.out.println("\nNFL AllStars");
for (int i=0; i<allstarValues.length; i++) {
 System.out.println(allstarValues[i]);
}
    //Call tthe Array Sort method
Arrays.sort(allstarValues);
System.out.println("******Sorted int array*******");
// Print the sorted array
for (int i=0; i<allstarValues.length; i++) {
System.out.println(allstarValues[i]);
  }  
    
     // Display the results
	System.out.println("List of Players Ages");
	for (int i=0; i<playersAges.length; i++) {
            	System.out.println("");
	System.out.print(playersAges[i] +"\t");
	} 
	}
 }

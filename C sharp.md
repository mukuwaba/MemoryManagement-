// Online C# Editor for free
// Write, Edit and Run your C# code using C# Online Compiler

using System;
using static System.Console;

public class MemoryManagement{
    public static void Main(string[] args){
        
    string FirstFour= "0010";
    string LastBits = "000000000100";
    ////////////////////////////////
    string Binary_0 ="0000";
    string Binary_1 ="0001";
    string Binary_2 ="0010";
    string Binary_3 ="0011";
    string Binary_4 ="0100";
    string Binary_5 ="0101";
    string Binary_6 ="0110";
    string Binary_7 ="0111";
    string Binary_8 ="1000";
    string Binary_9 ="1001";
    string Binary_10 ="1010";
    
    ////////////////////////////////
    
    if (FirstFour == Binary_0){
            
            caseOutcome = 0;
    }//End if
    
    if (FirstFour == Binary_1){
            
            caseOutcome = 1;
    }//End if
    
    if (FirstFour == Binary_2){
            
            caseOutcome = 2;
              
    }//End: if
        if (FirstFour == Binary_3){
            
            caseOutcome = 3;
              
    }//End: if
        if (FirstFour == Binary_4){
            
            caseOutcome = 4;
              
    }//End: if
        if (FirstFour == Binary_5){
            
            caseOutcome = 5;
              
    }//End: if
        if (FirstFour == Binary_6){
            
            caseOutcome = 6;
              
    }//End: if
        if (FirstFour == Binary_7){
            
            caseOutcome = 7;
    }//End: if
    

switch(caseOutcome){
    case 0: 
        Console.WriteLine(Binary_0+"")
    break;
    
    case 1: 
        Console.WriteLine(Binary_1+"")
    break;
    
    case 2: 
        Console.WriteLine(Binary_2+"")
    break;


}

# Switch-case
Switch Case

public class SwitchCase {
 static void main(String[] args) {
     
     System.out.print("Enter a day number: ");
     Scanner sc = new Scanner(System.in);
     int day = sc.nextInt();
        
     System.out.print("The "+day+" day is: ");
     switch(day){
        case 1:
            System.out.print("Monday");
             break;
         case 2:
              System.out.print("Tuesday");
               break;
          case 3:
                System.out.print("Wednesday");
                break;
           case 4:
                 System.out.print("Thursday");
                 break;
           case 5:
                 System.out.println("Friday");
                  break;
            case 6:
                  System.out.print("Saturday");
                  break;
             case 7:
                   System.out.print("Sunday");
                   break;
             default:
                    System.out.print("Invalid day number!");
        }
      sc.close();
              
    }
    
}

Output:

Enter a day number: 6
The 6 day is: Saturday

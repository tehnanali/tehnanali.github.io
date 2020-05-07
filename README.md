# tehnanali.github.io
import.import java.util.regex.*;  
import java.util.Scanner;  
 
public class Main
{    
    public static void main(String[] args)
    {    
        Scanner sc=new Scanner(System.in);  
        while (true)
        {    
            System.out.println("Enter regex pattern:");  
            Pattern pattern = Pattern.compile(sc.nextLine());    
            System.out.println("Enter text:");  
            Matcher matcher = pattern.matcher(sc.nextLine());    
            boolean b1 = matcher.matches();
            System.out.println(b1);
            break;
        }    
    }  
}

# Given-a-string-return-a-string-made-of-the-first-2-chars-if-present-however-include-first-char-o
Q2

import java.util.Scanner;
public class Main
{
  public static void main (String[]args)
  {
    Scanner sc = new Scanner (System.in);
      System.out.println ("Enter String:");
    String A = sc.nextLine ();
      startOZ (A);
  }
  static void startOZ (String a)
  {
    if (a.charAt (0) == 'O' || a.charAt (0) == 'o')
      {
	System.out.print (a.charAt (0));
      }
    if (a.charAt (1) == 'z' || a.charAt (1) == 'Z')
      {
	System.out.print (a.charAt (1));
      }
  }

}
![image](https://user-images.githubusercontent.com/101725933/182032214-565f1903-5ff1-45fc-b1cf-dc39ac296203.png)

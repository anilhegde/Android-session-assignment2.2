import java.util.*;
class assignment22
{
public static void main(String args[])
{
int a=5;
 char[] chars = new char[a];
 for (int i = 0; i < a; i++) {
 chars[i] = '*';
 chars[a - 1 - i] = '*';
 for (int j = 0; j < a; j++) 
  {
    if (j == i || j == (a - 1 - i)) 
      {
        continue;
      }
  chars[j] = ' ';
  }
System.out.println(new String(chars));
}
}
}

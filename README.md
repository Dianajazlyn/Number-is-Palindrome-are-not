import java.util.scanner;
class Palindrome
{
Static boolean isPalindrome(int num)
{
  int rev=0;digit;copyNum=num;
  while(copyNum!=0)
  {
    digit=copyNum%10;
    rev=rev*10+digit;
    copyNum=copyNum/10;
  }
  return num=rev;
}
Public Static void main(String args[])
{
Scanner ip=new Scanner(System.in);
int num=ip.nextInt();
boolean res=isPalindrome(num);
if(res==true)
  System.out.println("Palindrome");
else
  System.out.println("Not Palindrome");
}
}


  

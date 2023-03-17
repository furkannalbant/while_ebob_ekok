# while_ebob_ekok

## code 
```java
  Scanner inp = new Scanner(System.in);
      System.out.println("1. Sayı Giriniz");
      int s1 = inp.nextInt();
      System.out.println("2. Sayıyı giriniz");
      int s2 = inp.nextInt();
      int ebob=0;
      int ekok=0;
      int i = 1;

      while (i<=s1)
      {

          if ((s1%i==0)&&(s2%i==0)){

            ebob=i;

          }
          i++;
      }
      System.out.println("Ebob ="+ebob);
      ekok =(s1*s2)/ebob;
      System.out.println("Ekok ="+ekok);
```
## print 
* 1. Sayı Giriniz
* 18
* 2. Sayıyı giriniz
* 24
* Ebob =6
* ekok=72

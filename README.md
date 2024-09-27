Java Type casting

Converting of data from 1 data type to another data type is called type casting. Type casting supports primitive and reference data type. Casting can of implicit and explicit. Implicit in  primitive data type can be done casting automatically. Meanwhile Explicit casting in  primitive data type should be done by developers. Implicit in  primitive data type happens when we apply a lower data type to higher data type (eg:- byte to int or int to long).Explicit in  primitive data type happens when we apply higher data type to lower data type (eg. int to byte or long to int).

Reference data type (i.e in object casting) is also having implicit and explicit. Implicit in reference data type happens when we assign child class object to parent class object. Explicit in  reference data type when we assign parent class object to child class object.


package com.bini.babu;

public class ImplicitCast {

	public static void main(String[] args) {
      byte b = 100;
      int i=b;
      System.out.println(i);

      long l=i;
      
      char ch = 'A';
      int s =ch;
      System.out.println(s);
	}

}

Output
100
65


here 'int i=b' automatically converts byte to int example of implicit type. When we print 's' variable instead we get the value 'A' we get the integer value to the corresponding character 'A' which is 65 (represents A in the character set).

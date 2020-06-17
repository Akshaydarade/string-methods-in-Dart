# string-methods-in-Dart
//  This is completely illustration for the string properties and methods in Dart programming language
void main(){
  
  //This is program for illustration of string properties and methos on string
  
  
  
 String str1='Adsdfgh';
 String str2=' darade';
  
  // PROPERTIES OF STRING
  
 //interpolation polation of string by + perator
 
  print(str1+str2);
  
//returns a list of codeunits for the given string 
  
  print(str1.codeUnits);
  
//returns the given string is empty or not
  
  print(str1.isEmpty);
  
//returns the  length of string including spaces and tab and newline characters
  
  print(str2.length);
  
  
//METHODS IN STRING
  
  // 1.toLowerCase  return all the string in the lowercase format
  
  print(str1.toLowerCase());
  
  // 2.trim():return the new string by removing the all the white spaces before and                  after the string
  
  print(str2.trim());
  
  //3.compareTO():
  
  print(str1.compareTo(str2));
  
  //4.replaceAll():
  
  print(str1.replaceAll("dsd","ksh"));
  
  //5.substring()
  
  
  print(str1.substring(1,4));
}

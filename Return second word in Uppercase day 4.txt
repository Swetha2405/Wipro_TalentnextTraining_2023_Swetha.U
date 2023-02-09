import java.io.*;
import  java.util.*;
class UserMainCode{

public String secondWordUpperCase(String input1){

String strArray[] = input1.split(" ");        

String stt="LESS";        

if(strArray.length==1) {            

return stt;        

}        

return strArray[1].toUpperCase();   

 }}
class Design7{
public static void main(String args[]){
 int i,j;
for(i=0;i<=8;i++){
       for(j=0;j<=8;j++){
                          if(i==0||i==8)
                                       System.out.print("*");
                          else if( i==1||i==7){
                                                  if(j==4)
                                                       System.out.print(" ");
                                                   
                                                 else
                                                        System.out.print("*");
                                                       }
                           else if(i==2||i==6){ 
                                                   if(j>=3&&j<=5)
                                                         System.out.print(" ");
                                                   else 
                                                          System.out.print("*");
                                                         }
                             else if(i==3||i==5){
                                                    if(j>=2&&j<=6)
                                                           System.out.print(" ");
                                                     else
                                                            System.out.print("*"); 
                                                           }                              
                               else if(i==4){                                  
                                                   if(j>=1&&j<=7)
                                                            System.out.print(" ");
                                                   else
                                                          System.out.print("*");  
                                                       }  
                            }
System.out.println("");
                  }
           }
}      

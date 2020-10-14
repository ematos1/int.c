# int.c
problem set 2

#include <cs50.h>
#include <stdio.h>    
    
int main(void)

{  
   int h;
   {
    h = get_int("h:");
   }
     if(h == 1)
     {
         printf("#\n");
     } 
     else
    if(h == 2)
     {
         printf(" #\n##\n");
     } 
     else
    if(h == 3)
     {
         printf("  #\n ##\n###\n");
     }
     else
    if(h == 4)
     {
         printf("   #\n  ##\n ###\n####\n");
     } 
     else
    if(h == 5)
     {
         printf("    #\n   ##\n  ###\n ####\n#####\n");
     } 
     else
    if(h == 6)
     {
         printf("     #\n    ##\n   ###\n  ####\n #####\n######\n");
     } 
     else
    if(h == 7)
     {
         printf("      #\n     ##\n    ###\n   ####\n  #####\n ######\n#######\n");
     } 
     else
    if(h == 8)
     {
         printf("       #\n      ##\n     ###\n    ####\n   #####\n  ######\n #######\n########\n");
     }  
   
     if (h==1 || h==2 || h==3 || h==4 || h==5 || h==6 || h==7|| h==8) false;
         {
             return h;
         }
         
}

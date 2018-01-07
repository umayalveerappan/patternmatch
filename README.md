public static void main(string args[])
	{
	  String text="veera";
	  String pattern="eer";
	  int count=0;                                                   //tlen=5   plen=3
	  int tlen=text.length();                                             i=2  c=e  p=e             
	  int plen=pattern.length();                                              j=2 , k=0; j<5(2<5)
	  char c,p;                                                                     c=e  t=e 
	  for(int i=0;i<tlen-plen;i++)                                                       j=3,k=1;j<5(3<5)
	   {                                                                                      c=e    k=e
	     c=text.charAt(i);
	     p=pattern.charAt(0);
	     if(c==p)
	       {
	         for(int j=i,k=0;j<i+plen;j++,k++)
	           {
	              c=text.charAt(j);
	              t=pattern.charAt(0);
	            if(c==p)
	                 count++;
	            }
	      }
	 if(result)
	      System.out.println("found");
	    else
	      System.out.println("not found");
	   }
	}   
	      
	      
	      
	       


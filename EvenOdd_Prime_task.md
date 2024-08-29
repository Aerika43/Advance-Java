## Even Odd Number & Prime Number 
```java
private void even_odd_buttonActionPerformed(java.awt.event.ActionEvent evt) {                                                
      int a = Integer.parseInt(num.getText());
      if(a%2==0)
      {
          output_eo.setText("EVEN NUMBER");
      }
      else
      {
          output_eo.setText("ODD NUMBER");
      }
      
    }                                               

    private void jButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                         
       int a = Integer.parseInt(num.getText());
       int b = 0;
       for(int i=1;i<=a;i++)
       {
           if(a%i==0)
           {
               b++;
           }
       }
       if(b==2)
       {
           output_prime.setText("PRIME NUMBER");
       }
//       else if(a==1)
//       {
//           output_prime.setText("Neither PRIME NUMBER Not Composite");
//       }
       else
       {
           output_prime.setText("NOT PRIME NUMBER");
       }
    }
```

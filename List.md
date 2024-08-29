## List
```java
String data = jList1.getSelectedValue().toString();
       
       if(data.equalsIgnoreCase("Iphone"))
       {
           jTextField1.setText("160000");
       } 
       if(data.equalsIgnoreCase("Samsung"))
       {
           jTextField1.setText("210000");
       }
       if(data.equalsIgnoreCase("One plus"))
       {
           jTextField1.setText("60000");
       }
       if(data.equalsIgnoreCase("Vivo"))
       {
           jTextField1.setText("20000");
       }
       if(data.equalsIgnoreCase("Oppo"))
       {
           jTextField1.setText("27000");
       }
    }                                   

    private void jButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        double qty,tot,price;
        
        qty = Integer.parseInt(jComboBox1.getSelectedItem().toString());
        price = Integer.parseInt(jTextField1.getText());
        
        tot = qty * price;
        
        jTextField2.setText(""+tot);
    } 
```

## Combo Box
```java
private void jComboBox1ActionPerformed(java.awt.event.ActionEvent evt) {                                           
        String data = jComboBox1.getSelectedItem().toString();
        
        if(data.equalsIgnoreCase("Cake"))
        {
            jTextField1.setText("100");
        }
        if(data.equalsIgnoreCase("Pastry"))
        {
            jTextField1.setText("70");
        }
        if(data.equalsIgnoreCase("Coffee"))
        {
            jTextField1.setText("150");
        }
        if(data.equalsIgnoreCase("Burger"))
        {
            jTextField1.setText("200");
        }
        if(data.equalsIgnoreCase("Pizza"))
        {
            jTextField1.setText("450");
        }
        if(data.equalsIgnoreCase("Maggie"))
        {
            jTextField1.setText("80");
        }
        if(data.equalsIgnoreCase("Sandwich"))
        {
            jTextField1.setText("120");
        }    
    }                                          

    private void jButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        double qty,tot,gst,gross,price;
        
        qty = Integer.parseInt(jComboBox2.getSelectedItem().toString());
        price = Integer.parseInt(jTextField1.getText());
        
        tot = qty * price;
        gst = tot * 0.05;
        gross = tot + gst;
        
        jTextField3.setText(""+tot);
        jTextField4.setText(""+gst);
        jTextField5.setText(""+gross);
    }                                        
```

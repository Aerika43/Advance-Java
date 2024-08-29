## Check Box
```java
private void jButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                         
            String s = "";
            if(jCheckBox1.isSelected())
            {
                s = s + jCheckBox1.getText() + " ";
            }
            if(jCheckBox2.isSelected())
            {
                s = s + jCheckBox2.getText() + " ";
            }
            if(jCheckBox3.isSelected())
            {
                s = s + jCheckBox3.getText() + " ";
            }
            if(jCheckBox4.isSelected())
            {
                s = s + jCheckBox4.getText() + " ";
            }
            
            jLabel2.setText("Hobbies are : "+s);      
    } 
```

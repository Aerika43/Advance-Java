## Marksheet
### Textfield Label Button
```java
private void marks_buttonActionPerformed(java.awt.event.ActionEvent evt) {                                             
        int a = Integer.parseInt(english.getText());
        int b = Integer.parseInt(maths.getText());
        int c = Integer.parseInt(chemistry.getText());
        int d = Integer.parseInt(physics.getText());
        int e = Integer.parseInt(computersci.getText());
        
        int total = a+b+c+d+e;
        obtainedmarks.setText("OBTAINED MARKS : "+total);
         int p = total/6;
        percentage.setText("PERCENTAGE : "+p+"%");
        if(p>=90)
        {
            grade.setText("GRADE : A+");
        }
        else if(p>=80)
        {
            grade.setText("GRADE : A");
        }
        else if(p>=70)
        {
            grade.setText("GRADE : B");
        }   
        else if(p>=60)
        {
            grade.setText("GRADE : C");
        }
        else if(p>=50)
        {
            grade.setText("GRADE : D");
        }
        else
        {
            grade.setText("GRADE : Fail");
        }
    }
```

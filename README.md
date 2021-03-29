# ComputeMethods
ComputeMethods
package sample;

import javax.swing.JOptionPane;

public class ComputeMethods {
    public static void main(String [] args) {
        String a;
        double F,K,R;
        int c ;

        a = JOptionPane.showInputDialog("Masukan Suhu Dalam Celcius");
        c = Integer.parseInt(a);

        F = (c * 9 + 32);
        K = (c + 273);
        R = (c * 4);

        JOptionPane.showMessageDialog(null, "suhu Farenheit"+ F);
        JOptionPane.showMessageDialog(null, "Suhu Kelvin" + K);
        JOptionPane.showMessageDialog(null, "Suhu Reamur" + R);

    }

}

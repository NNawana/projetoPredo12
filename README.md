
import javax.swing.JOptionPane;

public class projetoPredo12 {
    /** 
     
     */
    public static void main(String[] args) {
        String firstNumber = JOptionPane.showInputDialog("Insira o primeiro numero inteiro");
        String secondNumber = JOptionPane.showInputDialog("Insira o segundo numero inteiro");

        int number1 = Integer.parseInt(firstNumber);
        int number2 = Integer.parseInt(secondNumber);

        int sum = number1 + number2;

        JOptionPane.showMessageDialog(null, "The sum is " + sum, "Sum of Two Integers", JOptionPane.PLAIN_MESSAGE);
     }
}

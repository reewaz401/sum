import javax.swing.JOptionPane;
class show{
	private static final int PLAIN_MESSAGE = 0;

	public static void main(String[] args) {
		String fn = JOptionPane.showInputDialog("Enter your first number");
		String sn = JOptionPane.showInputDialog("Enter second number");
		int num1 = Integer.parseInt(fn);
	int num2=Integer.parseInt(sn);
	int sum=num1+num2;
	JOptionPane.showMessageDialog(null,"the sum is"+sum,"the addition",PLAIN_MESSAGE);
	}

}

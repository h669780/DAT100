package Oblig_innlevering1;
import static javax.swing.JOptionPane.*;
import static java.lang.Integer.parseInt;

public class OppgaveO1_B4_uke35 {
	
	public static void main(String[] args) {
		
		String inp_brutto = showInputDialog("Skriv inn bruttoinntekt: ");
		double ib = parseInt(inp_brutto);
		if (ib >= 164101) {
			
			if (ib >= 230951) {
				
				if (ib >= 580651) {
					
					if (ib >= 934051) {
						double trinnskatt = ib * 0.1452;
						System.out.print("Trinnskatten er: " + trinnskatt);
					}
					else {
					double trinnskatt = ib * 0.1152;
					System.out.print("Trinnskatten er: " + trinnskatt);
					}
				}
				else {
				double trinnskatt = ib * 0.0241;
				System.out.print("Trinnskatten er: " + trinnskatt);
				}
			}
			else {
			double trinnskatt = ib * 0.0093;
			System.out.print("Trinnskatten er: " + trinnskatt);
			}
		}
		else {
			System.out.print("Nivå 0 trinnskatt(skattesum lik 0");
		}
		
	}

}

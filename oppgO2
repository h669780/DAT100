package Oblig_innlevering1;

import static javax.swing.JOptionPane.*;
import static java.lang.Integer.parseInt;

public class OppgaveO2_B5_uke35 {
	
	public static void main(String[] args) {
		int count = 0;
		while (count < 11) {
		//oppg b5b: repeterer whileløkken 10 ganger
			count += 1;
			String poengsum = showInputDialog("Skriv inn poengsum(0-100): ");
			int psum = parseInt(poengsum);
			
			if (psum > 89 && psum < 101) {
				System.out.println("Karakter A!");
			}
			if (psum > 79 && psum < 90) {
				System.out.println("Karakter B!");
			}
			if (psum > 59 && psum < 80) {
				System.out.println("Karakter C!");
			}
			if (psum > 49 && psum < 60) {
				System.out.println("Karakter D!");
			}
			if (psum > 39 && psum < 50) {
				System.out.println("Karakter E!");
			}
			if (psum > 0 && psum < 40) {
				System.out.println("Karakter F!");
			}
			if (psum > 100 || psum < 0) {
				System.out.println("*Feilmelding*, prøv igjen");
				//oppg b5c: fjerner ett forsøk per feilmelding:
				count -= 1;
			}
			
		}
		
	}

}

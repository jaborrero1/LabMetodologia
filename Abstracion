package helper;

public class StringHelper {
	
	//AACD => CD     AEF => EF    CDAA => CDAA
	public String eliminarAenLasPrimeras2Posiciones(String str) {
		if(str.length()<=2) {
			return str.replaceAll("A", "");
		}
		
		String primeros2Caract = str.substring(0, 2);
		String stringMenosPrimeros2Carac = str.substring(2);
		
		return primeros2Caract.replace("A", "") + stringMenosPrimeros2Carac;
	}
	
	//ABCD => FALSE    ABAB => TRUE    A=> FALSE   AB => TRUE
	public boolean primerosYultimos2CaracIguales(String str){
		if(str.length()<=1) {
			return false;
		}
		
		if(str.length()==2) {
			return true;
		}
		
		String primeros2Carac = str.substring(0, 2);
		String ultimos2Carac = str.substring(str.length() -2);
		
		return primeros2Carac.equals(ultimos2Carac);
	}
	
}

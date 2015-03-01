# Projet-IT
package com.itparis.b2.gestionref.graphix;

public class Coordonnées {

		private String Adresse;
		private int CodePostal;
		private String Ville;
		private String Pays;
		private String Email;
		private String SiteWeb;
		private int Portable;
		private int Fax;
		
		public Coordonnées(String Adresse, int CodePostal, String Ville, String Pays, String Email, String SitWeb, int Portable, int Fax, String SiteWeb) {
		this.Adresse=Adresse;
		this.CodePostal=CodePostal;
		this.Ville=Ville;
		this.Pays=Pays;
		this.Email=Email;
		this.SiteWeb=SiteWeb;
		this.Portable=Portable;
		this.Fax=Fax;
		}
		public String getAdresse() {
			return Adresse;
		}
		public void setAdresse(String adresse) {
			Adresse = adresse;
		}
		public int getCodePostal() {
			return CodePostal;
		}
		public void setCodePostal(int codePostal) {
			CodePostal = codePostal;
		}
		public String getVille() {
			return Ville;
		}
		public void setVille(String ville) {
			Ville = ville;
		}
		public String getPays() {
			return Pays;
		}
		public void setPays(String pays) {
			Pays = pays;
		}
		public String getEmail() {
			return Email;
		}
		public void setEmail(String email) {
			Email = email;
		}
		public String getSiteWeb() {
			return SiteWeb;
		}
		public void setSiteWeb(String siteWeb) {
			SiteWeb = siteWeb;
		}
		public int getPortable() {
			return Portable;
		}
		public void setPortable(int portable) {
			Portable = portable;
		}
		public int getFax() {
			return Fax;
		}
		public void setFax(int fax) {
			Fax = fax;
		}
		
		public void afficher(){
		
			System.out.println("Adresse : "+Adresse+" CodePostal : "+CodePostal+" Ville : "+Ville+");
			
		}
		
	


}

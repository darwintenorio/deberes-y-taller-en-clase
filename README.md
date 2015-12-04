# deberes-y-taller-en-clase
java luna ejercicios en clases
//ejercicio del comportamiento de un tlevisor
public class Televisor
{

	
		private int Volumen_actual;
		private int canal_actual;
		private boolean encendido;
		
		//contructor
		public Televisor(){
			public Televisor(int VolumenParam,int CanalParam) {
			}
			this.Volumen_actual = VolumenParam;
			this.canal_actual = CanalParam;
			
			public  void EstablecerVolumen(int volumen)
			{
				canal_actual = volumen;
				
			public  void EstablecerCanal(int canal)
			{
				canal_actual = canal;
				
				public int obtenerVolumen(){
				return Volumen_actual;
						
				public int obtenercanal(){
				return canal_actual;
				
			public void encender(){	
				encendido=true;
				
				public void apagado(){	
				encendido=false;
				
				public void SubirVolumen();
				if (encendido && Volumen_actual<=100)
					Volumen_actual++;
				
				public void BajarVolumen();
				if (encendido && Volumen_actual<=0)
					Volumen_actual--;
				}
				public void CambiarCanalArriba();
				if (canal_actual<=50)
					Volumen_actual++;
					
					public void CambiarCanalAbajo();
					if (canal_actual<=50)
						Volumen_actual--;
					
				{
				}
				
				}
					//impriimei
					public Strimg Tosstring()}
				return "canal actual;"+canal_actual+"volumen_actual"+Volumen_actual;
			
		}
		
	}

}
// voil

public class voild {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
Televisor TV1;
TV1 =new Televisor();
TV1.EstablecerVolumen(100);
TV1.EstablecerCanal(8);
	}

}

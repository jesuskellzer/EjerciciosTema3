# EjerciciosTema3
Ejercicios de tema 3

import java.util.*;

public class Main {
    public static void main(String[] args) {
      Coche miCoche = new Coche();
      miCoche.ColocarPuertas();
      miCoche.ColocarPuertas();
      miCoche.ColocarPuertas();
      miCoche.ColocarPuertas();
      System.out.println("Mi Coche tiene " + miCoche.puertas + " puertas");
  }
}

class Coche {
  public int puertas = 0;
  
  
  public void ColocarPuertas(){
    this.puertas++;
  }
}


import java.util.*;

public class Main {
    public static void main(String[] args) {
      int param1 = 30;
      int param2 = 50;
      int param3 = 40;
      
      var resultado = suma(param1, param2, param3);
      
      suma(param1, param2, param3);
      System.out.println(resultado);
  }
    public static int suma(int a, int b, int c) {
      return a + b + c;
      
    }
}

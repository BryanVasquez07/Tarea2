# Tarea2
tarea modulo 2
mport java.util.ArrayList;
import java.util.List;

public class Recursos {

    public String obtenerMensajePOO() {
        return "Programación Orientada a Objetos 2021";
    }

    public String verificarEdad(int edad) {
        if (edad >= 22) {
            return "Mayor de edad";
        } else {
            return "Menor de edad";
        }
    }
public int multiplicar(int a, int b) {
        return a * b;
    }

    public List<Integer> generarListaNumeros(int x) {
        List<Integer> numeros = new ArrayList<>();
        for (int i = 1; i <= x; i++) {
            numeros.add(i);
        }
        return numeros;
    }
public static void main(String[] args) {
        Recursos recursos = new Recursos();

        System.out.println(recursos.obtenerMensajePOO());

        System.out.println(recursos.verificarEdad(20));
        System.out.println(recursos.verificarEdad(21));
        int resultadoMultiplicacion = recursos.multiplicar(4, 5);
        System.out.println("Resultado de la multiplicación: " + resultadoMultiplicacion);
        
        List<Integer> listaNumeros = recursos.generarListaNumeros(10);
        System.out.println("Lista de números: " + listaNumeros);
    }
}


    

    

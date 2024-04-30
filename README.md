# projeto-de-funcao
conversao de temperaturas

package exercicios;

public class ConversorDeTemperatura {

    public static void main(String[] args) {
        double temperaturaCelsius = 25.0; // Valor da temperatura em Celsius

        exibirTemperaturasConvertidas(temperaturaCelsius);
    }

    public static void exibirTemperaturasConvertidas(double celsius) {
        double fahrenheit = celsius * 1.8 + 32;
        double kelvin = celsius + 273.15;
        double reaumur = celsius * 0.8;
        double rankine = celsius * 1.8 + 32 + 459.67;

        System.out.println("Temperatura em Fahrenheit: " + fahrenheit);
        System.out.println("Temperatura em Kelvin: " + kelvin);
        System.out.println("Temperatura em Réaumur: " + reaumur);
        System.out.println("Temperatura em Rankine: " + rankine);
    }
}

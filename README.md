package pl.samouczekprogramisty.kursjava;

public class TemperatureCheck {
    public static void main(String[] args) {
    }

    private static java.lang.StringBuilder Baca = ;                                //
    static void main("String[] Baca args.");

    {
        int positiveTemperature = 50;                                     //przedział odczytywania temeperatur przez program
        int negativeTemperature = -50;
        isTemperaturePositive(positiveTemperature);
        isTemperaturePositive(negativeTemperature);
    }

    private static boolean isTemperaturePositive(double temperature) {      //
        boolean isPositive = temperature > 0;                                     //warunek temperatura dodatnia jest większa od 0 stopni bez zwracania
        if (isPositive) {
            System.out.println("Temperatura " + temperature + " Jest dodatnia.");        //jeżeli spełnia ten warunek to jest dodatnia
        } else {
            System.out.println("Temperatura " + temperature + "Nie jest dodatnia.");     //nie spełnia tego warunku nie jest dodatnia(0 bądź ujemna)
        };

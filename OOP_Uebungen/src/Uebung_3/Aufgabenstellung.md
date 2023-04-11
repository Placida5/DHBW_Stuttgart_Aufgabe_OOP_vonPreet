# DHBW_Stuttgart_Aufgabe_OOP
Objektorientierten Programmierung

Uebung_3

Gegeben ist folgender Code, welcher nicht kompiliert werden kann. Welche
Fehler sind im Code?

public abstract class Car {
    public void drive(){
        
        System.out.println("BRRRRUUUUMMM");
    }
}


public class Main {

    public static void main(String[] args){
        Car myCar = new Car();
            myCar.drive();
    }
}


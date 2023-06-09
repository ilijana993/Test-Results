# Test-Results
Unit test:
import Calculator

def test_addition(self){
x = 2;
y = 3;
expected_result = 5;

actual_result = Calculator(x, y);

if(expected_result == actual_result):
Sistem.out.println ("Test succeeded.");
else:
Sistem.out.println ("Test failed for values" + x + " and " + y);
}

Greške:
Calculator- 1 – neimenovan paket, code smell=minimalan 
Calculator – 4 – Korisne klase ne bi trebalo da imaju javne konstruktore. Code smell=maksimalno značajan 
Calculator - 18 - Imena metoda treba da budu u skladu sa konvencijom o imenovanju ( umesto „ToString“ treba da piše „toString“). Code smell=minimalan 
Calculator – 24 - Imena metoda treba da budu u skladu sa konvencijom o imenovanju ( umesto „Run“ treba da piše „run“). Code smell=minimalan 
Calculator – 70 - Lokalne promenljive ne treba deklarisati, a zatim ih odmah vratiti ili izbaciti (treba da piše „return Float.toString(finalResult)“) . Code smell=minimalan 
Calculator – 73 - Imena metoda treba da budu u skladu sa konvencijom o imenovanju ( umesto „Calculate“ treba da piše „calculate“). Code smell=minimalan 
Calculator – 182 – suvišna naredba („return“)





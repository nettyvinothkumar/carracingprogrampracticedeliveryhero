# carracingprogrampracticedeliveryhero
carracingprogrampracticedeliveryhero

Write a small program to accept list of car names , and car names should
be more than 4 characters then print else print "Invalid Car Names, 
Car name should be more than 4 characters"


public class CarNamePrint {
public static void main(String[] args) {
List<String> carName = List.of("Toyota Camry","Hond","Ford","BMW3","Audi","Kia","Ferrari");
for (String car : carName){
if(car.length()<=4){
System.out.println(car);
}
else {
System.out.println(car + " - Invalid Car Names");
}
}
}
}

Toyota Camry - Invalid Car Names
Hond
Ford
BMW3
Audi
Kia
Ferrari - Invalid Car Names
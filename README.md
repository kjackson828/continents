# continents
Codecademy quiz on switch statements

public class Continents {
  //Program prints Continent, Country and City based on value of 'continent' variable
	public static void main(String[] args) {
	int continent = 4;
	switch (continent){
    case 1: continent = 1;
      System.out.println("North America: Mexico City, Mexico");
      break;
    case 2 : continent = 2;
      System.out.println("South America: Sao Paulo, Brazil");
      break;
    case 3: continent = 3;
      System.out.println("Europe: Moscow, Russia");
      break;
    case 4: continent = 4; 
      System.out.println("Africa: Lagos, Nigeria");
      break;
  case 5: continent = 5; 
      System.out.println("Asia: Shanghai, China");
      break;
    case 6: continent = 6;
      System.out.println("Australia: Sydney, Australia");
      break;
    case 7: continent = 7;
      System.out.println("Antarctica: McMurdo Station, US");
      break;
    default: System.out.println("Undefined continent !");
      break;
  }
	}
}

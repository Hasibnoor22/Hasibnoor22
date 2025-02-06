## Hi there 👋 This is an interesting java code on cars(:


 public class Car {//Start of the class


		//class area
		//class level variable or non-static variable
		String model;
		String style;
		int year = 2022;
		int wheel = 12;
		
		
		public static void main(String[] args) {//Start of the main method
			//How to create an object of a class
			Car benz = new Car(); //WE just created a new object of a class
			// new Car(); is the object of class
			// benz is the object reference variable
			Car bmw = new Car();
			//When we create object of a class a copy of non-static member
			//of the class will be given to the object.
		
			//Initialize the class level variable
			benz.year = 2022;
			benz.wheel = 18;
			benz.model = "E550";
			benz.style = " Benz E550 Sport Coupe";
			
			
			bmw.model = "M8";
			bmw.style = "BMW M8 Convirtable Sport";
			bmw.year = 2020;
			bmw.wheel = 16;
			
			//bmw = benz;    we can assign the values of benz into bmw
			System.out.println(benz.model + " and we have " + bmw.model);
			System.out.println(benz.year + " and we have " + bmw.year);
			System.out.println(benz.wheel + " and we have " + bmw.wheel);
			System.out.println(benz.style + " and we have " + bmw.style);


	}//End of the main method

}//End of the class 

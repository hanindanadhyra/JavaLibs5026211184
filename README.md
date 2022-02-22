# JavaLibs5026211184import javax.swing.*;

public class JavaLibs5026211184 {
	public static void main(String[] args) {

	//Welcome
	String welcome = JOptionPane.showMessageDialog(null, "Welcome! Get ready, we will ask some questions especially about your movies taste!");
	
	//1 Name
	String name = JOptionPane.showInputDialog("Hello! Please insert your name!");
	JOptionPane.showMessageDialog(null, "Hi, "+name+"! Hope you have a good day today!");

	//2 Age
	String age = JOptionPane.showInputDialog("How old are you?");
	int ageConvert=Integer.parseInt(age);
	JOptionPane.showMessageDialog(null, "Alright, you are "+age+".");

	//3 Gender
	String gender = JOptionPane.showInputDialog("What is your gender?");
	JOptionPane.showMessageDialog(null, "So you're a "+gender+".");

	//4 Country
	String country = JOptionPane.showInputDialog("Where do you come from?");
	JOptionPane.showMessageDialog(null, "Oh! You're from "+country+".");

	//5 Genre
	String genre = JOptionPane.showInputDialog("What movie genres do you prefer to watch?");
	
	//6 Favourite
	String favourite = JOptionPane.showInputDialog("What is your favourite movie?");

	//7 Language
	String language = JOptionPane.showInputDialog("What languages that you prefer to hear on a movie?");
	
	//8 Series
	String series = JOptionPane.showInputDialog("Do you like to watch a movie series? |1 = Yes 2 = No|");
	int seriesConvert=integer.parseInt(series);
	if (seriesConvert == 1 ) {
		JOptionPane.showMessageDialog(null, "I see that you like to watch a series.");
	}else if (seriesConvert == 2 ) {
		JOptionPane.showMessageDialog(null, "It's okay if you don't like to watch a series!");
	}
	
	//9 Time
	String time = JOptionPane.showInputDialog("How many hours do you spend to watch a movie in a week?");

	//10 Website
	String website = JOptionPane.showInputDialog("What website that you've been used to watch a movie?");

	//end
	JOptionPane.showMessageDialog(null, "Yash!! You already pass all of the questions! Thank you so much, "+name+", for participating!")

## Nama		:Febri Aditiya
## Nim		:312010212
## Kelas	:TI.20.A2
## Dosen	:Wahyu Hadikristanto,S.Kom.,M.Kom

			 “Ujian Tengah Semester”



	/*
 	* To change this license header, choose License Headers in Project Properties.
 	* To change this template file, choose Tools | Templates
 	* and open the template in the editor.
 	*/
	package Biodata;
	import java.util.Scanner ;
	/**
 	*
 	* @author febri aditiya
 	*/
	public class Biodata {
	public static void main (String args [])
	{
	String nama = " " ;
	String nim = " " ;
	int nilai = 0 ;

	Scanner masuk = new Scanner (System.in);
    	System.out.print("Nama  : ");
    	nama = masuk.nextLine();
    
    	System.out.print("Nim   : ");
    	nim = masuk.nextLine();
    
    	System.out.print("nilai :");
    	nilai = masuk.nextInt();


    	System.out.println("Nama  : " + nama);
    	System.out.println("Nim   : " + nim);
    	System.out.println("Nilai : " + nilai);

	// proses if else
	if (nilai >= 80 && nilai <=100){
       		System.out.println("A");
	}else if (nilai >= 70 && nilai <=79){
     		System.out.println("B");
	}else if (nilai >= 60 && nilai <=69){
     		System.out.println("C");
	}else if (nilai >= 50 && nilai <=59){
     		System.out.println("D");
	}else if (nilai >= 0 && nilai <=49){
     		System.out.println("E");
	}

	System.out.println("-----------------------");
	System.out.println("-----------------------");
	}
    
	}        

	Output:
	Nama  : Febri Aditiya
	Nim   : 312010212
	Nilai : 90
	A
	-----------------------
	-----------------------
	BUILD SUCCESSFUL (total time: 1 minute 46 seconds)

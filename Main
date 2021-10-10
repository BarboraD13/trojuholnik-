package com.company;
import java.util.Scanner;
public class Main {

    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        System.out.println("Zadajte výšku: ");
        int vyska = s.nextInt();

        for (int i = 0; i <= vyska; i++) {
            for (int j = 0; j < i; j++) {
                System.out.print("*");
            }
            System.out.println("");
        }
        System.out.println("");
        for (int a = 1; a <= vyska; a++){
            for (int j = 1; j <= vyska - a; j++){
                System.out.print(" ");
            }
            for (int y = 0; y < a; y++){
                System.out.print("*");
            }
            System.out.println();
        }
        System.out.println("");
        for (int b = 0; b <= vyska; b++){
            for (int j = 0; j < vyska - b; j++){
                System.out.print("*");
            }
            System.out.println();
        }
        for (int c = 1; c <= vyska; c++){
            for (int j = 1; j <= c - 1; j++){
                System.out.print(" ");
            }
            for (int y = 0; y <= vyska - c; y++){
                System.out.print("*");
            }
            System.out.println();
        }




    }
}

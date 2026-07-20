import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int income = sc.nextInt();
        int tax;

        if (income <= 10000) {
            tax = (income * 5) / 100;
        } else if (income <= 50000) {
            tax = (income * 10) / 100;
        } else {
            tax = (income * 20) / 100;
        }

        System.out.println(tax);
    }
}

# sum-of-value
package com.company;

import jdk.swing.interop.SwingInterOpUtils;

import java.util.Scanner;

class JAVA
{
    public static void main (String args[])
    {
        int arr[]= {1,5,8,9};
        int sum=0;
        for (int i = 0; i < arr.length; i++)
        {
        sum += arr[i];
        }
        System.out.println("sum =" + sum);
    }
}

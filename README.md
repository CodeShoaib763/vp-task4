# vp-task4
 using System;

class DataTypeMinMax
{
    static void Main()
    {
    
        int intMin = int.MinValue;
        int intMax = int.MaxValue;
        Console.WriteLine("Integer Min: " + intMin);
        Console.WriteLine("Integer Max: " + intMax);

        
        long longMin = long.MinValue;
        long longMax = long.MaxValue;
        Console.WriteLine("Long Min: " + longMin);
        Console.WriteLine("Long Max: " + longMax);

    
        double doubleMin = double.MinValue;
        double doubleMax = double.MaxValue;
        Console.WriteLine("Double Min: " + doubleMin);
        Console.WriteLine("Double Max: " + doubleMax);

        
        string str1 = "Apple";
        string str2 = "Banana";
        string minStr = string.Compare(str1, str2) < 0 ? str1 : str2;
        string maxStr = string.Compare(str1, str2) > 0 ? str1 : str2;
        Console.WriteLine("String Min (alphabetically): " + minStr);
        Console.WriteLine("String Max (alphabetically): " + maxStr);
    }
}


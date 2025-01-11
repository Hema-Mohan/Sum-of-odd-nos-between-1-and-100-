# Sum-of-odd-nos-between-1-and-100-
Public class SumOfOddNumbers {
    Public static void main(String[] args) {
        int sum = 0;
        for (int i = 1; i <= 100; i++) {
            if (i % 2 != 0) { 
                sum += i;
            }
        }

        System.out.println("The sum of the first 100 odd numbers is: " + sum);
    }
}

OUTPUT:

The sum of the first 100 odd numbers is: 10000

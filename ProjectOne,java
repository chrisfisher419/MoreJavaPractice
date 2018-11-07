public class ProjectOne {
    public static void main(String[] args){
        printMegaBytesAndKiloByte(1028);
        bark(true, 5);
        leapYear(1700);
    }
    public static void printMegaBytesAndKiloByte(int kiloBytes) {
        int megaBytes = kiloBytes / 1024;
        int remain = kiloBytes % 1024;
        String output = String.format("%d KB = %d MB and %d KB", kiloBytes, megaBytes, remain);
        System.out.println(output);
        if (kiloBytes < 1) {
            System.out.println("Invalid value");
        }
    }
    public static boolean bark(boolean barking, int hourOfDay){
        if (hourOfDay > 23 || hourOfDay < 0){
            System.out.println("false");
            return false;
        }
        if ((hourOfDay < 8 && hourOfDay > 0) || (hourOfDay > 22 && hourOfDay < 23)){
            System.out.println("true");
            return true;
        }
        System.out.println("false");
        return false;
    }
    public static void leapYear(int year){
        if (year % 4 == 0){
            if (year % 400 != 0 && year % 100 == 0){
                System.out.println("false");
            }
            else{
                System.out.println("true");
            }
        }
        else{
            System.out.println("false");
        }
    }

}


# PHAMTHANHSANG_107366
public class Main {
    public static void main(String[] args) {
        // Khai báo mảng hai chiều
        int a[][] = {{1, 3}, {6, 5, 9}, {4, 6}};
        
        // Duyệt mảng hai chiều và in ra các phần tử
        for (int i = 0; i < a.length; i++) { // Duyệt qua các mảng con
            for (int j = 0; j < a[i].length; j++) { // Duyệt qua từng phần tử của mảng con
                System.out.print(a[i][j] + " "); // In phần tử
            }
            System.out.println(); // Xuống dòng sau khi hiển thị các phần tử trong một mảng con
        }
    }
}


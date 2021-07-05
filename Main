package life;

import java.util.Random;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int game_size = scanner.nextInt();
        int seed = scanner.nextInt();
        Random random = new Random(seed);
        char[][] game_board = new char[game_size][game_size];
        
        for (int i = 0 ; i < game_size ; i++){
            for (int j = 0 ; j < game_size ; j++){
                game_board[i][j] = ' ';
                if (random.nextBoolean()){
                    game_board[i][j] = 'O';
                }
                System.out.print(game_board[i][j]);
            }
            System.out.println();
        }
    }
}

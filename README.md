# Chess Piece Detection | OpenCV 
This project involves loading multiple images of chess boards and utilizing the matchTemplate method of OpenCV to detect the pieces present on each board. As a result of this process, the output includes a comprehensive list of the detected chess piece names.

<p align="center">
    <img src="dist/board.jpg" />
    <img src="dist/board (9).jpg" />
   
</p>


|                Piece                 |      Name      | Short Name |                   Piece                    |      Name      | Short Name |
| :----------------------------------: | :------------: | :--------: | :----------------------------------------: | :------------: | :--------: |
|  ![King (White)](chess_piece/K.png)  |  King (White)  |     K      |  ![King (black)](chess_piece/k_black.png)  |  King (black)  |     k      |
| ![Queen (white)](chess_piece/Q.png)  | Queen (White)  |     Q      | ![Queen (black)](chess_piece/q_black.png)  | Queen (black)  |     q      |
|  ![Rook (White)](chess_piece/R.png)  |  Rook (White)  |     R      |  ![Rook (black)](chess_piece/r_black.png)  |  Rook (black)  |     r      |
| ![Bishop (white)](chess_piece/B.png) | Bishop (White) |     B      | ![Bishop (black)](chess_piece/b_black.png) | Bishop (black) |     b      |
| ![Knight (White)](chess_piece/N.png) | Knight (White) |     N      | ![Knight (black)](chess_piece/n_black.png) | Knight (black) |     n      |
|  ![Pawn (White)](chess_piece/P.png)  |  Pawn (White)  |     P      |  ![Pawn (black)](chess_piece/p_black.png)  |  Pawn (black)  |     p      |



## Requirements

- Python 3.x
- OpenCV
- Numpy

## Usage

To get started, first clone the repository and install the necessary dependencies by running the following command:

```bash
pip install opencv-python numpy
```

Next, place the chess board image files in the `test/` directory and the chess piece image files in the `chess_piece/` directory.


** Running in Terminal**

To run the script in the terminal, use the following command:

```bash
python main.py
```

## Configuration

The following configurations can be adjusted according to the user's preference:

- `SHOW_IMAGE`: If set to `True`, the image with detected pieces will be displayed. Default is `True`.
- `EXPORT_IMAGE`: If set to `True`, the image with detected pieces will be saved to the `dist/` directory. Default is `True`.
- `chessPieceThreshold`: The threshold values for each chess piece can be adjusted according to the image quality. The default values are provided in the script.
- `CHESS_BOARD_OUTPUT_DIR`: The directory where the output images will be saved. Default is `dist/`.



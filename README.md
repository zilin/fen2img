# Fen2img
> A tool to generate chess board image from a Forsyth–Edwards Notation(FEN) string.


## Install

`pip install fen2img`

## How to use

here is an example:

```python
fen2img('rnbqkbnr/pppppppp/8/8/8/8/PPPPPPPP/RNBQKBNR', theme='brown', piece_style='merida')
```




![png](docs/images/output_4_0.png)



## Supported themes:

|<!-- -->|<!-- -->|<!-- -->|
|:------:|:------:|:------:|
|beyer <img src="boards/beyer.svg" width="200">|blue <img src="boards/blue.svg" width="200">|brown <img src="boards/brown.svg" width="200">|
|chesscom <img src="boards/chesscom.svg" width="200">|falken <img src="boards/falken.svg" width="200">|green <img src="boards/green.svg" width="200">|
|informator <img src="boards/informator.svg" width="200">|sportverlag <img src="boards/sportverlag.svg" width="200">|zeit <img src="boards/zeit.svg" width="200">|


## Supported piece styles:

|<!-- -->|<!-- -->|<!-- -->|<!-- -->|<!-- -->|<!-- -->|<!-- -->|<!-- -->|<!-- -->|<!-- -->|<!-- -->|<!-- -->|<!-- -->|
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|merida|<img src="pieces/merida/bR.png" width=45>|<img src="pieces/merida/bN.png" width=45>|<img src="pieces/merida/bB.png" width=45>|<img src="pieces/merida/bQ.png" width=45>|<img src="pieces/merida/bK.png" width=45>|<img src="pieces/merida/bP.png" width=45>|<img src="pieces/merida/wR.png" width=45>|<img src="pieces/merida/wN.png" width=45>|<img src="pieces/merida/wB.png" width=45>|<img src="pieces/merida/wQ.png" width=45>|<img src="pieces/merida/wK.png" width=45>|<img src="pieces/merida/wP.png" width=45>|
|alpha|<img src="pieces/alpha/bR.png" width=45>|<img src="pieces/alpha/bN.png" width=45>|<img src="pieces/alpha/bB.png" width=45>|<img src="pieces/alpha/bQ.png" width=45>|<img src="pieces/alpha/bK.png" width=45>|<img src="pieces/alpha/bP.png" width=45>|<img src="pieces/alpha/wR.png" width=45>|<img src="pieces/alpha/wN.png" width=45>|<img src="pieces/alpha/wB.png" width=45>|<img src="pieces/alpha/wQ.png" width=45>|<img src="pieces/alpha/wK.png" width=45>|<img src="pieces/alpha/wP.png" width=45>|
|beyer|<img src="pieces/beyer/bR.png" width=45>|<img src="pieces/beyer/bN.png" width=45>|<img src="pieces/beyer/bB.png" width=45>|<img src="pieces/beyer/bQ.png" width=45>|<img src="pieces/beyer/bK.png" width=45>|<img src="pieces/beyer/bP.png" width=45>|<img src="pieces/beyer/wR.png" width=45>|<img src="pieces/beyer/wN.png" width=45>|<img src="pieces/beyer/wB.png" width=45>|<img src="pieces/beyer/wQ.png" width=45>|<img src="pieces/beyer/wK.png" width=45>|<img src="pieces/beyer/wP.png" width=45>|
|case|<img src="pieces/case/bR.png" width=45>|<img src="pieces/case/bN.png" width=45>|<img src="pieces/case/bB.png" width=45>|<img src="pieces/case/bQ.png" width=45>|<img src="pieces/case/bK.png" width=45>|<img src="pieces/case/bP.png" width=45>|<img src="pieces/case/wR.png" width=45>|<img src="pieces/case/wN.png" width=45>|<img src="pieces/case/wB.png" width=45>|<img src="pieces/case/wQ.png" width=45>|<img src="pieces/case/wK.png" width=45>|<img src="pieces/case/wP.png" width=45>|
|chesscom|<img src="pieces/chesscom/bR.png" width=45>|<img src="pieces/chesscom/bN.png" width=45>|<img src="pieces/chesscom/bB.png" width=45>|<img src="pieces/chesscom/bQ.png" width=45>|<img src="pieces/chesscom/bK.png" width=45>|<img src="pieces/chesscom/bP.png" width=45>|<img src="pieces/chesscom/wR.png" width=45>|<img src="pieces/chesscom/wN.png" width=45>|<img src="pieces/chesscom/wB.png" width=45>|<img src="pieces/chesscom/wQ.png" width=45>|<img src="pieces/chesscom/wK.png" width=45>|<img src="pieces/chesscom/wP.png" width=45>|
|condal|<img src="pieces/condal/bR.png" width=45>|<img src="pieces/condal/bN.png" width=45>|<img src="pieces/condal/bB.png" width=45>|<img src="pieces/condal/bQ.png" width=45>|<img src="pieces/condal/bK.png" width=45>|<img src="pieces/condal/bP.png" width=45>|<img src="pieces/condal/wR.png" width=45>|<img src="pieces/condal/wN.png" width=45>|<img src="pieces/condal/wB.png" width=45>|<img src="pieces/condal/wQ.png" width=45>|<img src="pieces/condal/wK.png" width=45>|<img src="pieces/condal/wP.png" width=45>|
|leipzig|<img src="pieces/leipzig/bR.png" width=45>|<img src="pieces/leipzig/bN.png" width=45>|<img src="pieces/leipzig/bB.png" width=45>|<img src="pieces/leipzig/bQ.png" width=45>|<img src="pieces/leipzig/bK.png" width=45>|<img src="pieces/leipzig/bP.png" width=45>|<img src="pieces/leipzig/wR.png" width=45>|<img src="pieces/leipzig/wN.png" width=45>|<img src="pieces/leipzig/wB.png" width=45>|<img src="pieces/leipzig/wQ.png" width=45>|<img src="pieces/leipzig/wK.png" width=45>|<img src="pieces/leipzig/wP.png" width=45>|
|maya|<img src="pieces/maya/bR.png" width=45>|<img src="pieces/maya/bN.png" width=45>|<img src="pieces/maya/bB.png" width=45>|<img src="pieces/maya/bQ.png" width=45>|<img src="pieces/maya/bK.png" width=45>|<img src="pieces/maya/bP.png" width=45>|<img src="pieces/maya/wR.png" width=45>|<img src="pieces/maya/wN.png" width=45>|<img src="pieces/maya/wB.png" width=45>|<img src="pieces/maya/wQ.png" width=45>|<img src="pieces/maya/wK.png" width=45>|<img src="pieces/maya/wP.png" width=45>|
uscf|<img src="pieces/uscf/bR.png" width=45>|<img src="pieces/uscf/bN.png" width=45>|<img src="pieces/uscf/bB.png" width=45>|<img src="pieces/uscf/bQ.png" width=45>|<img src="pieces/uscf/bK.png" width=45>|<img src="pieces/uscf/bP.png" width=45>|<img src="pieces/uscf/wR.png" width=45>|<img src="pieces/uscf/wN.png" width=45>|<img src="pieces/uscf/wB.png" width=45>|<img src="pieces/uscf/wQ.png" width=45>|<img src="pieces/uscf/wK.png" width=45>|<img src="pieces/uscf/wP.png" width=45>|
|alpha|<img src="pieces/alpha/bR.png" width=45>|<img src="pieces/alpha/bN.png" width=45>|<img src="pieces/alpha/bB.png" width=45>|<img src="pieces/alpha/bQ.png" width=45>|<img src="pieces/alpha/bK.png" width=45>|<img src="pieces/alpha/bP.png" width=45>|<img src="pieces/alpha/wR.png" width=45>|<img src="pieces/alpha/wN.png" width=45>|<img src="pieces/alpha/wB.png" width=45>|<img src="pieces/alpha/wQ.png" width=45>|<img src="pieces/alpha/wK.png" width=45>|<img src="pieces/alpha/wP.png" width=45>|
|wikipedia|<img src="pieces/wikipedia/bR.png" width=45>|<img src="pieces/wikipedia/bN.png" width=45>|<img src="pieces/wikipedia/bB.png" width=45>|<img src="pieces/wikipedia/bQ.png" width=45>|<img src="pieces/wikipedia/bK.png" width=45>|<img src="pieces/wikipedia/bP.png" width=45>|<img src="pieces/wikipedia/wR.png" width=45>|<img src="pieces/wikipedia/wN.png" width=45>|<img src="pieces/wikipedia/wB.png" width=45>|<img src="pieces/wikipedia/wQ.png" width=45>|<img src="pieces/wikipedia/wK.png" width=45>|<img src="pieces/wikipedia/wP.png" width=45>|

*** The image files for above themes and piece styles are copied from [PgnViewer](https://github.com/mliebelt/PgnViewerJS).

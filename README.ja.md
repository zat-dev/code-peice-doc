# CodePieceとは

Pythonの PlayGroundです。
WASM(Pyodide)を使っており、ブラウザ内でPythonが動いています

* pip installでパッケージを入れられます
* iframeでブログ等に埋め込むことが可能です

# FAQ
* Q: パッケージインストールに失敗する
* A: パッケージはPyPIにwheelがあるものか、Cを使う場合はWASMコンパイルして[Pyodide](https://github.com/pyodide/pyodide/tree/main/packages)に登録される必要があります

* Q: バグの報告について
* A: このリポジトリのissueにお願いします

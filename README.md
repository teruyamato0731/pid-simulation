# pid-simulation
PythonでPID制御のシミュレーションを行う。
[Jupyterを使いたい]で開発環境の構築を解説している。
また[PID制御]でPID制御の式を解説している。

[Jupyterを使いたい]: https://zenn.dev/teruyamato0731/scraps/1eda18b453e5f9
[PID制御]: https://zenn.dev/teruyamato0731/scraps/66339a544c0019

## 使い方
1. `git clone https://github.com/teruyamato0731/pid-simulation.git`
1. VS Codeでcloneしたリポジトリを開く。
1. [devcontainer拡張機能]の「Reopen in Container」でDockerコンテナを起動。
1. Jupyter拡張機能を使えば、VS Code内で`.ipynb`の編集・実行が行える。
1. コンテナ内でターミナルを開き、`jupyter server list`で表示されるリンクをブラウザで開くと、JupyterLabが確認できる。

[devcontainer拡張機能]: https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers

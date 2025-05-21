# ipynb-devcontainer-template

VS Code の Dev Container で `.ipynb`（Jupyter Notebook）を使いたいときのテンプレートです。  
Python 環境が自動で構築され、`nbstripout` により出力セルを除いて Git 管理できます。

## 🚀 使い方
1. このリポジトリをクローンし、VS Code で開く
2. コマンドパレットから「Reopen in Container」を実行
3. `src/hello.ipynb` を開く
4. 右上の `カーネルの選択` をクリック → `Jupyter Kernel...` → `python-devcontainer` を選択
5. セルを実行・編集
6. Git にコミットすると、出力セルは自動で除去されます（nbstripout による）

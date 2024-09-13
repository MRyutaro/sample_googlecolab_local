# sample_googlecolab_local
Google Colabのローカルランタイムを試す

1. `python -m venv .venv`
2. `pip install -r requirements.txt`
3. `jupyter notebook --NotebookApp.allow_origin='https://colab.research.google.com' --port=8888 --NotebookApp.port_retries=0 --NotebookApp.iopub_data_rate_limit 10000000`
4. ターミナルに表示されたリンクをコピー
5. Google Colabを開いて新しいノートブックを作成し、`ローカルランタイムに接続`を押す
6. コピーしたURLを貼り付け

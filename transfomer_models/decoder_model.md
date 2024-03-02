# デコーダーモデル

デコーダーモデルは、トランスフォーマーモデルのデコーダーのみを使用します。各段階で、特定の単語に対して、注意層は文中でそれより前に位置する単語にのみアクセスできます。これらのモデルはしばしば自己回帰モデルと呼ばれます。事前に訓練されたデコーダーモデルは通常、文中の次の単語を予測することに関連しています。これらのモデルは、テキスト生成を含むタスクに最適です。このモデルファミリーの代表例には、CTRL、GPT、GPT-2、TransformerXLなどがあります。
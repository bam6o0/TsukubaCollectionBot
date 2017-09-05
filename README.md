# つくコレさん

つくばコレクション2017の候補者のツイッターデータを処理してツイートするBot

アカウント [@tc_statistics](https://twitter.com/tc_statistics?s=09)

## Description

### status

Twitter REST APIでフォロワー数・ツイート数・お気に入り数を取得

### graf_generator

データの追加・グラフの線画＋保存

### get_date

データのみの更新
graf_generatorの呼び出し
（データの取得、追加、線画）

### main_tweet

生成されたグラフ画像のツイート（生成されている画像をタグ付きで投稿、最大４枚）

## Usage

1. Set up auth

 add `config.py`

```python
CONSUMER_KEY = "****************************"
CONSUMER_SECRET = "****************************"
ACCESS_TOKEN = "****************************"
ACCESS_TOKEN_SECRET = "****************************"
```

2. Data update

```python
python3 get_data.py
```

3. tweet

```
python3 main_tweet.py
```

## Contribution

1. Fork
2. Create a feature branch
3. Commit your changes
4. Rebase your local changes against the master branch
5. Create new Pull Request

## Licence

[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)

## Author

[takato](https://github.com/bam6o0)


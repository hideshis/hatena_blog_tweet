# hatena_blog_tweet
はてなブログの最新記事10件から1件を無作為に選択し、そのURLをツイートする

## 利用しているAPI
* [はてなブログAtomPub](http://developer.hatena.ne.jp/ja/documents/blog/apis/atom)
* [Twitter API](https://developer.twitter.com/en/products/twitter-api)

## 実行
```execution.sh
pip3 install requests
pip3 install tweepy
python3 hatena_blog_tweet.py
```


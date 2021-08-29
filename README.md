# linebot-aws-work

- AWSのlambdaを利用したlinebotサーバレスアプリケーションの技術検証
- amazon recognitionを利用した表情分析機能検証

## 使用言語
python

## 利用手順

### 前提条件:
- aws-cli/sam-cliがインストール済みであること
- Line developersでアカウントを作成済みであること
    - LineChannelAccessTokenを取得済みであること
    - LineChannelSecretを取得済みであること
1. sam-cliを使ってAWSのLambdaにbuildする

```
$ sam build --use-container -t template.json
```


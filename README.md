# bingo_hub

## スマホで遊べる簡易ビンゴゲーム仕様案
```
1. ゲームマスターがゲーム作成 (Home.vue)
2. IDがふられる
3. URL/IDのQRコードが作られる (Admin.vue -> QRCode.vue)
4. 参加者がスマホでURLを読み込む
5. URL+IDのページで参加名を入力し登録 (User.vue)
6. 参加者ID(ゲームID+参加者番号)にビンゴカードが作られる
8. 参加者のスマホにビンゴカードが表示される (User.vue -> Bingo.vue, Admin.vue -> Bingo.vue)
8. 参加者が揃ったらゲームマスターがゲーム開始ボタンを押す (Admin.vue)
9. ビンゴゲーム開始 (User.vue -> (Bingo.vue, History.vue) Admin.vue -> (Bingo.vue, History.vue, UserList.vue))
10. ビンゴが揃ったら順位を表示 (User.vue -> (Bingo.vue, History.vue, Ranking.vue) Admin.vue -> (Bingo.vue, History.vue, Ranking.vue)
11. 終了 IDがなくなる (Admin.vue)

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

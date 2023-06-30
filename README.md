# rails x paralell_tests x github actions を動かしてみる

## TODO

- [ ] rspec追加
- [ ] 1件テストができるようにする
- [ ] 1000件くらいのテストをできるようにする
- [ ] github actions
- [ ] paralell_tests を追加して、並列テストをできるようにする
- [ ] github actions で親jobから、子jobに対してテストを分散実行できるようにする

## setup

```
cd ./backend/
./bin/rails s
```

http://localhost:3000/
にアクセスすると、サイトが見れる

# README

## Usage

### Heroku
- 後台入口：https://restaurant-forum-1.herokuapp.com/admin/
- 可使用 root@example.com 登入，密碼 12345678

### Git Clone 步驟

```
$ git clone https://github.com/ALPHACamp/web-online-restaurant-forum.git
$ bundle install
$ rails db:migrate
$ rails dev:fake
```

## User stories

#### Phase 1
- 網站管理者可以登入網站後台
- 網站管理者可以在後台新增／瀏覽／編輯／刪除餐廳的基本資料
- 網站管理者可以在後台上傳餐廳照片
- 瀏覽餐廳資料時，會有分頁功能，頁只顯示 10 筆資料

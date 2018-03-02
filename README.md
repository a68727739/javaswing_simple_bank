```
用javaswing搭配sqlite做的簡單銀行系統
開發時使用neatbean可使用neatbean匯入專案
資料庫管理工具可使用 DB.Browser.for.SQLite 
下載專案後需要調整電腦資料庫檔實體路徑  javaconnect.java  中的
Connection conn=DriverManager.getConnection("jdbc:sqlite:D:\\project\\java\\javaswing_simple_bank\\bank.sqlite");
```
```
登入畫面
```
![image](https://github.com/a68727739/javaswing_simple_bank/blob/master/DEMO/login.png)
```
建立帳戶
```
![image](https://github.com/a68727739/javaswing_simple_bank/blob/master/DEMO/create_acccount.png)
```
建立成功
```
![image](https://github.com/a68727739/javaswing_simple_bank/blob/master/DEMO/create_account_ok.png)
```
使用剛剛新增的帳戶登入
```
![image](https://github.com/a68727739/javaswing_simple_bank/blob/master/DEMO/login02.png)
```
登入等待畫面
```
![image](https://github.com/a68727739/javaswing_simple_bank/blob/master/DEMO/login3.png)
```
輸入帳戶並點即右邊的眼睛按鈕(搜尋該帳戶資料)
```
![image](https://github.com/a68727739/javaswing_simple_bank/blob/master/DEMO/search_name.png)

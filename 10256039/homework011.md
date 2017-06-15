# 作業 011

1. 請用「自己的話」舉例說明什麼叫做「Duck Typing」
    - 利用某類別是否具備某個方法來判斷是否為同一個物件
    - 會呱呱叫的就認為他是一隻鴨子
    - 假設 class a 跟 b 都有 m 這個方法就認為他是同一個類別
    
2. 請用「自己的話」舉例說明實體方法(instance method) 跟類別方法(class method) 的差別。
    - 要呼叫實體方法必須先實作那個類別，類別方法則可以使用類別直接呼叫

3. 在 Ruby 引入模組有兩種方式：include 跟 extend，請舉例並說明這兩個方法的差別？
    - include 讓 model 的方法變成實體方法
    - extend 讓 model 的方法變成類別方法
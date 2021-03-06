## 使用變數 ##

下面這段程式碼，會將 `6+7` 的運算結果，以 `n` 表示：
```
n = 6+7
```
所以當你執行 `print n` 時，螢幕上就會印出 `13`。`=` 這個運算符號代表 _將 `=` 右邊的結果，儲存至左邊的變數_。

你也可以一次指定多個變數的值：
```
m, n = 5, 6
```
這樣一來，`m` 的值就是 `5` 而 `n` 則為 `6`。

當然，你也可以對變數進行運算：
```
n = 6 + 7
print n + 5
```
這段程式碼執行的結果，會在螢幕上輸出 `18`。

> | 與某些程式語言（如：C/C++, Java 等）不同的是，在 Python 中使用變數不需要事先宣告，或是指定資料型態。然而，如果在還沒指定資料前就使用變數--比方說將它印在螢幕上--就會發生錯誤。 |
|:----------------------------------------------------------------------------------------------------|


## 變數的命名限制 ##

變數的名稱只能以英文字母（`A`-`Z`, `a`-`z`）、數字（`0`-`9`）以及底線（`_`）所組成，英文字母\*大小寫有別**（case-sensitive）。要注意的是，變數名稱不得以數字開頭。**

比方說 `_myVar`, `NumberY` 都是合法的變數名稱；而 `abcd` 與 `Abcd` 則會視為兩個不同的變數；`6abc` 則是不能使用的變數名稱。

## 讀取使用者輸入 ##

如果程式中有需要讀取使用者所輸入的資料，可以使用 Python 內建的 `input` 函式：
```
x = input('Please input a number:')
```
執行這段程式碼時，程式會要求你輸入一個數字，而這個數字將會儲存至 `x` 變數。


---


## 下一步 ##

Python 不只可以處理數值資料，上面的例子提到使用 `input` 函式，裡面有一段以單引號（'）所包起來的文字部份，這樣的資料在 Python 程式中稱為「字串」（string）。接下來，我們可以在[處理字串資料](String.md)的章節瞭解如何在 Python 程式中處理字串資料。
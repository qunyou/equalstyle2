# Equalstyle


----
## 特色說明
* 未定義 wrap 或 container 的寬度，可與 Bootstrap、Material Design 等 css Framework 併用。
* 版面重新分割欄位數，只需要改外層的數字，不需要每個欄位都修改。


例如 bootstrapb 分割四欄：

    .row
        .col-md-3
        .col-md-3
        .col-md-3
        .col-md-3

如果修改為兩欄：

    .row
        .col-md-6
        .col-md-6
        .col-md-6
        .col-md-6

若使用 Equalstyle，分割四欄：

    .eqs4
        .column
        .column
        .column
        .column

如果修改為兩欄：

    .eqs2
        .column
        .column
        .column
        .column

Responsive
> 一般畫面四欄，手機一欄，平板兩欄

    .eqs4.enlarge-xs.enlarge2-sm
        .column
        .column
        .column
        .column

----
## Demo
[Equalstyle](http://equalstyle.onepoint.com.tw)
AUTO.js - 简谱代码化
====
#### 用于AUTO.JS自动点击，以便快速通过输入简谱，生成自动点击的代码，以在SKY·光遇运行。

#### Get Started

1. 注册`GITHUB`，点击`Start`。
2. 打开电脑的`EXCEL`。
3. 新键一个`宏命令`
4. 输入以下代码：
    ```javascript
    Sub 代码化()
    Dim i As Integer
    With Range("A1:G100")
    For i = 1 To .Cells.Count
    If WorksheetFunction.CountIf(.Cells(i), "C5") = 1 Then
    .Cells(i) = "C5();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "D5") = 1 Then
    .Cells(i) = "D5();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "E5") = 1 Then
    .Cells(i) = "E5();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "F5") = 1 Then
    .Cells(i) = "F5();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "G5") = 1 Then
    .Cells(i) = "G5();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "A5") = 1 Then
    .Cells(i) = "A5();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "B5") = 1 Then
    .Cells(i) = "B5();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "C6") = 1 Then
    .Cells(i) = "C6();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "D6") = 1 Then
    .Cells(i) = "D6();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "E6") = 1 Then
    .Cells(i) = "E6();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "F6") = 1 Then
    .Cells(i) = "F6();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "G6") = 1 Then
    .Cells(i) = "G6();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "A6") = 1 Then
    .Cells(i) = "A6();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "B6") = 1 Then
    .Cells(i) = "B6();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "C7") = 1 Then
    .Cells(i) = "C7();"
    End  If
    Next i
     End With
    End Sub
    Sub 节奏化4分()
    Dim i As Integer
    With Range("A1:G100")
    For i = 1 To .Cells.Count
    If WorksheetFunction.CountIf(.Cells(i), "C5();") = 1 Then
    .Cells(i) = "C5();R4();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "D5();") = 1 Then
    .Cells(i) = "D5();R4();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "E5();") = 1 Then
    .Cells(i) = "E5();R4();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "F5();") = 1 Then
    .Cells(i) = "F5();R4();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "G5();") = 1 Then
    .Cells(i) = "G5();R4();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "A5();") = 1 Then
    .Cells(i) = "A5();R4();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "B5();") = 1 Then
    .Cells(i) = "B5();R4();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "C6();") = 1 Then
    .Cells(i) = "C6();R4();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "D6();") = 1 Then
    .Cells(i) = "D6();R4();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "E6();") = 1 Then
    .Cells(i) = "E6();R4();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "F6();") = 1 Then
    .Cells(i) = "F6();R4();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "G6();") = 1 Then
    .Cells(i) = "G6();R4();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "A6();") = 1 Then
    .Cells(i) = "A6();R4();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "B6();") = 1 Then
    .Cells(i) = "B6();R4();"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "C7();") = 1 Then
    .Cells(i) = "C7();R4();"
    End  If
    Next i
     End With
    End Sub
    Sub 标准化()
    Dim i As Integer
    With Range("A1:G100")
    For i = 1 To .Cells.Count

    If WorksheetFunction.CountIf(.Cells(i), "【1】") = 1 Then
    .Cells(i) = "C5"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "【2】") = 1 Then
    .Cells(i) = "D5"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "【3】") = 1 Then
    .Cells(i) = "E5"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "【4】") = 1 Then
    .Cells(i) = "F5"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "【5】") = 1 Then
    .Cells(i) = "G5"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "【6】") = 1 Then
    .Cells(i) = "A5"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "【7】") = 1 Then
    .Cells(i) = "B5"
    End  If

    If WorksheetFunction.CountIf(.Cells(i), "1") = 1 Then
    .Cells(i) = "C6"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "2") = 1 Then
    .Cells(i) = "D6"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "3") = 1 Then
    .Cells(i) = "E6"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "4") = 1 Then
    .Cells(i) = "F6"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "5") = 1 Then
    .Cells(i) = "G6"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "6") = 1 Then
    .Cells(i) = "A6"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "7") = 1 Then
    .Cells(i) = "B6"
    End  If
    If WorksheetFunction.CountIf(.Cells(i), "[1]") = 1 Then
    .Cells(i) = "C7"

    End  If
    Next i
     End With
    End Sub

    ```
    
5. 在`记事本`上写上`简谱`，每一段一个数字。
6. 将其复制到`EXCEL`，运行宏命令。以标准化→代码化→节奏化为顺序。
7. 将其复制，导入到模板。

# 第1次作業-作業-HW1
>
>學號：112111130
><br />
>姓名：廖昱婷
><br />
>作業撰寫時間：180 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2023/09/22
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x] 說明內容
- [x] 個人認為完成作業須具備觀念

## 說明程式與內容

開始寫說明，該說明需說明想法，
並於之後再對上述想法的每一部分將程式進一步進行展現，
若需引用程式區則使用下面方法，
若為.cs檔內程式除了於敘述中需註明檔案名稱外，
還需使用語法` ```語言種類 程式碼 ``` `，其中語言種類若是要用python則使用py，java則使用java，C/C++則使用cpp，
下段程式碼為語言種類選擇csharp使用後結果：

```csharp
public partial class _Default : System.Web.UI.Page
{
    protected void Page_Load(object sender, EventArgs e)
    {
        Response.Write("這是我的第一次 ASP.NET 作業！");
    }
}

若要於內文中標示部分網頁檔，則使用以下標籤` ```html 程式碼 ``` `，
下段程式碼則為使用後結果：

```<%@ Page Language="C#" AutoEventWireup="true" CodeFile="Default.aspx.cs" Inherits="_Default" %>

<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title>HW1 測試頁面</title>
</head>
<body>
    <form id="form1" runat="server">
        <div>
            <asp:Label ID="Label1" runat="server" Text="Hello ASP.NET!"></asp:Label>
        </div>
    </form>
</body>
</html>
```
更多markdown方法可參閱[https://ithelp.ithome.com.tw/articles/10203758](https://ithelp.ithome.com.tw/articles/10203758)



請在撰寫"說明程式與內容"該塊內容，請把原該塊內上述敘述刪除，該塊上述內容只是用來指引該怎麼撰寫內容。

1. 請實作同名稱檔案並將程式碼實作並印出其結果，其內容為Topic 1 投影片的第12~13頁。
Ans:
1. 透過 Default.aspx 作為前端網頁，提供 HTML 結構，並能嵌入伺服器控制項。  
2. 在 Default.aspx.cs 撰寫 C# 程式碼，負責處理頁面載入時的事件 (Page_Load)。  
3. 當網頁被執行時，伺服器會先載入 C# 程式，再將結果輸出到網頁中，最後在瀏覽器上顯示文字。  

執行結果：  
- 當我在 Visual Studio 執行專案並開啟瀏覽器時，網頁會顯示「這是我的第一次 ASP.NET 作業！」的文字。  
- 這代表我的程式成功運作，後端 C# 程式碼有正確連結到網頁前端。 
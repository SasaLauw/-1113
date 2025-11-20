第10週 2025/11/13

-新增一個視窗類別 （MyDocumentViewer)。
-由主視窗來建立新的子視窗，並顯示出來。
•.Show() 
•.ShowDialog()
-(Windows Presentation Foundation）中的「文件類別」主要指的是用於處理和呈現文件內容的類別，特別是位於System.Windows.Documents 命名空間下的一系列類別。WPF 將文件分成兩大類，分別是為了不同的使用情境而設計：I
•RichTextBox
•ToggleButton


這些控制項用於在 WPF 應用程式中顯示FlowDocument 或 FixedDocument：
FlowDocumentReader：提供多種檢視模式（滾動、分頁、雙頁），且包含內建的UI供使用者切換模式、放大/縮小等。
FlowDocumentScrollViewer：簡單的滾動檢視，類似網真瀏覽器。
FlowDocumentPageViewer：以單頁固定大小的模式顯示內容。
RichTextBox：一個可編輯的控制項，其內容以 FlowDocument的形式儲存。

固定文件（FixedDocument）通常用於創建 XPS （XML Paper Specification）文件，確保列印輸出的精確性。
• FixedDocument：固定文件的根容器，包含 PageContent 元素。
• PpgeContent：代表文檔中的一真•包含一個 FixedPage 元素•
• FixedPage：實際繪製內容的容器，內容元素使用絕對座標定位。
• 比較Rich TextBox, TextBlock, TextBox, Label的差異
• ToggleButton 最主要的特點是它擁有一個持久的、可以切換（Toggle）的狀態．不像標準的 Button 那樣•按下後就只是觸發一次 Click 事件然後返回原始狀態。
• WPF Command:WPF 的命令系統是一個強大的設計模式，旨在為應用程式中的動作.

EWK
===
product 產品單元 說明
========================
- 側邊欄項目需記憶位置，內容部分可用AJAX 動態載入達到側邊欄記憶位置的功能。
 - 只需在該項目加入 class "active"。例如：

	   		$(function(){
				$("#prodClassItem1").addClass('active');// 此為大分類 例如：New Arrival、Special Promotion...等
			})
			
		或
	
		    $(function(){
				$("#prodClassItem1").addClass('active');// 此為大分類 例如：New Arrival、Special Promotion...等
				$(".js-ProdSubItem3").addClass('active');// 此為小分類 例如：VOLKSWAGEN、AUDI、CHEVROLET...等
			})
		

- 套程式時，可用 "[product.php]"、"[product_inner.php]"、"[product_soldOut.php]" 這些檔案。
- 檔名包含"C1"或"C1_1"系因示範側邊欄記憶位置而產生的。


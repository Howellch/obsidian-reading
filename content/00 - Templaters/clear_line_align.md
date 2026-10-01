<%*
const selection = tp.file.selection();
if (selection) {
  // 去除每行開頭的 Tab 和空格，保留其餘內容
  const cleanSelection = selection.replace(/^\s+/gm, '');
  
  // 將清理後的內容返回
  tR += cleanSelection;
}
%>
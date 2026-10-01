<%*
const selection = tp.file.selection();
if (selection) {
  const cleanSelection = selection.replace(/<span class='[^']*'>|<\/span>|<mark class='[^']*'>|<\/mark>/g, '');
  tR += cleanSelection;
}
%>
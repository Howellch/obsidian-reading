<%*
const selection = tp.file.selection();
if (selection) {
  const cleanSelection = selection.replace(/<mark class='[^']*'>|<\/mark>/g, '');
  tR += `<mark class='note-mark-blue'>${cleanSelection}</mark>`;
}
%>
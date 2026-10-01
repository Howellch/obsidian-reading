<%*
const selection = tp.file.selection();
if (selection) {
  const cleanSelection = selection.replace(/<span class='[^']*'>|<\/span>/g, '');
  tR += `<span class='note-blue-bg'>${cleanSelection}</span>`;
}
%>
---
# An instance of the Blank widget.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/
widget: blank

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 15

title: Similarity Check
subtitle:

design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '1'
---

Drag this link to your bookmarks bar to install: [hi](javascript:alert('');)

<div>
  <a href="javascript:alert('');">hello</a>
</div>




Drag this link to your bookmarks bar to install: [hi](javascript:if(typeof(searches)=='undefined'){var searches=0;};(function(){var count=0,text,regexp;text=prompt('Search regex:','');if(text==null||text.length==0)return;try{regexp=new RegExp(text,'i');}catch(er){alert('Unable to create regular expression using text \''+text+'\'.\n\n'+er);return;}function searchWithinNode(node,re){var pos,skip,acronym,middlebit,endbit,middleclone;skip=0;if(node.nodeType==3){pos=node.data.search(re);if(pos>=0){acronym=document.createElement('ACRONYM');acronym.title='Search '+(searches+1)+': '+re.toString();acronym.style.backgroundColor=backColor;acronym.style.borderTop='1px solid '+borderColor;acronym.style.borderBottom='1px solid '+borderColor;acronym.style.fontWeight='bold';acronym.style.color=borderColor;middlebit=node.splitText(pos);endbit=middlebit.splitText(RegExp.lastMatch.length);middleclone=middlebit.cloneNode(true);acronym.appendChild(middleclone);middlebit.parentNode.replaceChild(acronym,middlebit);count++;skip=1;}}else if(node.nodeType==1&&node.childNodes&&node.tagName.toUpperCase()!='SCRIPT'&&node.tagName.toUpperCase!='STYLE')for(var child=0;child<node.childNodes.length;++child)child=child+searchWithinNode(node.childNodes[child],re);return skip;}var borderColor='#'+(searches+8).toString(2).substr(-3).replace(/0/g,'3').replace(/1/g,'6');var backColor=borderColor .replace(/3/g,'c').replace(/6/g,'f');if(searches%2516/8>=1){var tempColor=borderColor;borderColor=backColor;backColor=tempColor;}searchWithinNode(document.body,regexp);window.status='Found '+count+' match'+(count==1?'':'es')+' for '+regexp+'.';if(count>0)searches++;})();)

<div>
  <a href="javascript:(function(){var newSS, styles='* { background: white ! important; color: black !important } :link, :link * { color: #0000EE !important } :visited, :visited * { color: #551A8B !important }'; if(document.createStyleSheet) { document.createStyleSheet("javascript:'"+styles+"'"); } else { newSS=document.createElement('link'); newSS.rel='stylesheet'; newSS.href='data:text/css,'+escape(styles); document.getElementsByTagName("head")[0].appendChild(newSS); } })();">hello</a>
</div>

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
  <a href="javascript%3A(function()%7Bvar%20newSS%2C%20styles%3D%27*%20%7B%20background%3A%20white%20!%20important%3B%20color%3A%20black%20!important%20%7D%20%3Alink%2C%20%3Alink%20*%20%7B%20color%3A%20%230000EE%2520!important%2520%7D%2520%3Avisited%2C%2520%3Avisited%2520*%2520%7B%2520color%3A%2520%23551A8B%2520!important%2520%7D%27%3B%2520if(document.createStyleSheet)%2520%7B%2520document.createStyleSheet(%2522javascript%3A%27%2522%2Bstyles%2B%2522%27%2522)%3B%2520%7D%2520else%2520%7B%2520newSS%3Ddocument.createElement(%27link%27)%3B%2520newSS.rel%3D%27stylesheet%27%3B%2520newSS.href%3D%27data%3Atext%2Fcss%2C%27%2Bescape(styles)%3B%2520document.getElementsByTagName(%2522head%2522)%5B0%5D.appendChild(newSS)%3B%2520%7D%2520%7D)()%3B">hello</a>
</div>

# bookmarklets

Just right click the link and bookmark it or drag it to your bookmark bar and click it whenever you read one of Napolitano's "What if" pieces:

[De-Napolitano]



[De-Napolitano]: javascript:function%20walk(element){if(!element)element=document.body;var%20nodes=element.childNodes;for(var%20n=0;n<nodes.length;n++){if(nodes[n].nodeType==Node.TEXT_NODE){var%20t=nodes[n].textContent.replace(/What%20if\s+\S/g,function(x){return%20x.slice(-1).toUpperCase();});nodes[n].textContent=t.replace(/\?/g,'.');}else{walk(nodes[n]);}}}walk();


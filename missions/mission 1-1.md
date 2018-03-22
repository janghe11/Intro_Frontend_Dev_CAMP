**1.  Error: Stray start tag html.**

     From line 4, column 7; to line 4, column 12

     o">↩<head><html>
  * **Answer** : ```<head>```


**2. Warning: The charset attribute on the script element is obsolete.**

     From line 29, column 5; to line 29, column 131

     " />↩↩    <script charset="UTF-8" class="daum_roughmap_loader_script" src="https://spi.maps.daum.net/imap/map_js_init/roughmapLoader.js"></scri
  * **Answer** : ```<script class="daum_roughmap_loader_script" src="https://spi.maps.daum.net/imap/map_js_init/roughmapLoader.js">```

**3. Warning: The type attribute is unnecessary for JavaScript resources.**

     From line 32, column 1; to line 32, column 86
     
     pt>↩    ↩↩<script src="/static/js/kakaobankWeb-lib-1521081376857.min.js" type="text/javascript"></scri
  * **Answer** : ```<script src="/static/js/kakaobankWeb-lib-1521081376857.min.js"></scri```

**4. Warning: The type attribute is unnecessary for JavaScript resources.**

     From line 36, column 1; to line 36, column 92

     /script>↩↩<script src="/static/js/kakaobankWeb-resources-1521081376857.min.js" type="text/javascript"></scri
  * **Answer** : ```<script src="/static/js/kakaobankWeb-resources-1521081376857.min.js">```

**5. Error: Stray end tag head.**

     From line 44, column 8; to line 44, column 14

     >↩↩</html></head>↩↩<bod
  * **Answer** : ```</head>```

**6. Error: Stray end tag head.**

     From line 44, column 8; to line 44, column 14

     >↩↩</html></head>↩↩<bod
 * **Answer** : ```</head>```

**7. Error: Start tag body seen but an element of the same type was already open.**

     From line 46, column 1; to line 46, column 105

     ></head>↩↩<body data-browser="unknown" data-os="unknown" data-browser-major="Unknown" data-browser-minor="Unknown">↩<div 
 * **Answer** : 이전 html과 head 태그의 오류로 인해 발생한 것으로 추정.

**8. Fatal Error: Cannot recover after last error. Any further errors will be ignored.**

     From line 46, column 1; to line 46, column 105

     ></head>↩↩<body data-browser="unknown" data-os="unknown" data-browser-major="Unknown" data-browser-minor="Unknown">↩<div 
 * **Answer** : ```<body>```
&nbsp;
 * **결론 : `<head></head>` 태그 안의 `<html></html>`태그로 인한 오류이며, 제거해주면 된다.**
# page-translator
Translate whole webpages with little helper page. 

<script type="text/javascript" src="http://code.jquery.com/jquery-1.4.3.min.js" ></script>
<script type="text/javascript">
    $(document).ready(function(){
        $("#url").keyup(function(){
            window.openURL("https://translate.google.com/translate?u=" + this);
        });
    })
</script>

<form action="https://bmline.de" target="_blank"  method="get">
    URL (should be translated): <br />
    <input type="text" id="url" name="url" maxlength="2000" style="width: 300px;"/>
    <br />
    <br />
  <input type="submit" value="Got to Translate"  />
</form>

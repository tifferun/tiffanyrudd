will need to build out in JS opening a new window browser when each case portfolio is clicked. This is some sample code to look over from the following link: 

https://stackoverflow.com/questions/9399354/how-to-open-a-new-window-and-insert-html-into-it-using-jquery

<script>
function nWin() {
  var w = window.open();
  var html = $("#toNewWindow").html();

    $(w.document.body).html(html);
}

$(function() {
    $("a#print").click(nWin);
});​
</script>

<div id="toNewWindow">
    <p>Your content here</p>
</div>

<a href="javascript:;" id="print">Open</a>​

TYPE Text: additional java script info to add...
https://blog.bitsrc.io/11-javascript-animation-libraries-for-2018-9d7ac93a2c59

picture: wheat field at sunset: https://www.google.com/search?q=wheat+field+sunset&rlz=1C1CHBF_enUS815US816&source=lnms&tbm=isch&sa=X&ved=0ahUKEwiHvfeby57eAhUEHTQIHbzWD6kQ_AUIDigB&biw=1466&bih=654#imgrc=TqXgqOjAgB_H0M:


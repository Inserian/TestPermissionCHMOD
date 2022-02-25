<script language="JavaScript">
function calculator(user, number){
// Owner
if (user == "owner" && number == "4"){var box = eval("document.chmod.owner4")}
if (user == "owner" && number == "2"){var box = eval("document.chmod.owner2")}
if (user == "owner" && number == "1"){var box = eval("document.chmod.owner1")}
// Group
if (user == "group" && number == "4"){var box = eval("document.chmod.group4")}
if (user == "group" && number == "2"){var box = eval("document.chmod.group2")}
if (user == "group" && number == "1"){var box = eval("document.chmod.group1")}
// Other
if (user == "other" && number == "4"){var box = eval("document.chmod.other4")}
if (user == "other" && number == "2"){var box = eval("document.chmod.other2")}
if (user == "other" && number == "1"){var box = eval("document.chmod.other1")}
if (box.checked == true){
if (user == "owner"){
document.chmod.h_owner.value += ("+number")
var a= (document.chmod.h_owner.value)
var b= eval(a)
document.chmod.h_owner.value=b
document.chmod.t_owner.value=b
}if (user == "group"){
document.chmod.h_group.value += ("+number")
var a= (document.chmod.h_group.value)
var b= eval(a)
document.chmod.h_group.value=b
document.chmod.t_group.value=b
}if (user == "other"){
document.chmod.h_other.value += ("+number")
var a= (document.chmod.h_other.value)
var b= eval(a)
document.chmod.h_other.value=b
document.chmod.t_other.value=b
}
}
if (box.checked == false){
if (user == "owner"){
if (document.chmod.h_owner.value == ""){
document.chmod.t_owner.value=""
}else {
var a=(document.chmod.h_owner.value);
b=a-(number);
c=eval(b);
document.chmod.h_owner.value=c
document.chmod.t_owner.value=c
}}if (user == "group"){
if (document.chmod.h_group.value == ""){
document.chmod.t_group.value=""
}else {
var a=(document.chmod.h_group.value);
b=a-(number);
c=eval(b);
document.chmod.h_group.value=c
document.chmod.t_group.value=c
}}if (user == "other"){
if (document.chmod.h_other.value == ""){
document.chmod.t_other.value=""
}else {
var a=(document.chmod.h_other.value);
b=a-(number);
c=eval(b);
document.chmod.h_other.value=c
document.chmod.t_other.value=c
}}
}}
</script>

<form name="chmod">
<input name="h_owner" type="hidden" value="">
<input name="h_group" type="hidden" value="">
<input name="h_other" type="hidden" value="">
<table bgcolor="#491e1e" cellpadding="5" cellspacing="1">
<tr bgcolor="#ffffff">
       <td colspan="4"><font face="verdana" size="3"><b>Chmod</b></font></td>
</tr><tr bgcolor="#ffffff" align="center">
       <td><font face="verdana" size="-1"><b>Permission</b></font></td>
       <td><font face="verdana" size="-1"><b>Owner</b></font></td>
       <td><font face="verdana" size="-1"><b>Group</b></font></td>
	   <td><font face="verdana" size="-1"><b>Other</b></font></td>
</tr><tr bgcolor="#ffffff" align="center">
       <td><font face="verdana" size="-1"><b>Read</b></font></td>
       <td><input type="checkbox" name="owner4" value="4" onclick="calculator('owner', 4)"></td>
       <td><input type="checkbox" name="group4" value="4" onclick="calculator('group', 4)"></td>
       <td><input type="checkbox" name="other4" value="4" onclick="calculator('other', 4)"></td>
</tr><tr bgcolor="#ffffff" align="center">
       <td><font face="verdana" size="-1"><b>Write</b></font></td>
       <td><input type="checkbox" name="owner2" value="2" onclick="calculator('owner', 2)"></td>
       <td><input type="checkbox" name="group2" value="2" onclick="calculator('group', 2)"></td>
       <td><input type="checkbox" name="other2" value="2" onclick="calculator('other', 2)"></td>
</tr><tr bgcolor="#ffffff" align="center">
       <td><font face="verdana" size="-1"><b>Execute</b></font></td>
       <td><input type="checkbox" name="owner1" value="1" onclick="calculator('owner', 1)"></td>
       <td><input type="checkbox" name="group1" value="1" onclick="calculator('group', 1)"></td>
       <td><input type="checkbox" name="other1" value="1" onclick="calculator('other', 1)"></td>
</tr><tr bgcolor="#ffffff" align="center">
       <td><font face="verdana" size="-1"><b></b></font></td>
       <td><input type="text" name="t_owner" value="" size="1"></td>
       <td><input type="text" name="t_group" value="" size="1"></td>
       <td><input type="text" name="t_other" value="" size="1"></td>
</tr>
</table>
</form>

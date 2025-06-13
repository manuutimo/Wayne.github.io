# Wayne.github.io
<html>
 <body>
  <center>
  <img src="em.png"height=135 width=135>
  <font size="+3" color=red>Employee Registration Form</font>
  <form method=post action="prac.html">
  </form>
  <table>
   <tr>
    <td></td>
    <td><input type=radio name=initial checked>Mr.
     <input type=radio name>Mrs.
     <input type=radio name>Ms.</td>
   </tr>
   <tr>
    <td>First Name</td>
    <td><input type=text name=fn placeholder="First Name"></td>
   </tr>
   <tr>
    <td>Last Name</td>
    <td><input type=text name=in placeholder="Last Name"></td>
   </tr>
   <tr>
    <td>Mail Address1</td>
    <td><input type=text name=add1></td>
   </tr>
   <tr>
    <td>Mail Address2</td>
    <td><input type=text name=add2></td>
   </tr>
   <tr>
    <td>City</td>
    <td><input type=text name=ct></td>
   </tr>
   <tr>
    <td>State</td>
    <td><select name=state>
     <option value="Gujarat">Gujarat
     <option value="Maharastra">Maharastra
     <option value="Karnataka">Karnataka
     <option value="Delhi">Delhi
     </select>
    </td>
   </tr>
   <tr>
    <td>Zip</td>
    <td><input type=text name=zp></td>
   </tr>
   <tr>
    <td>Upload photo</td>
    <td><input type=text name=photo></td>
   </tr>
   <tr>
    <td>E-Mail</td>
    <td><input type=text name=email size=30></td>
   </tr>
   <tr>
    <td>Mobile</td>
    <td><input type=text name=mob placeholder="+91"></td>
   </tr>
   <tr>
    <td>Languages known</td>
    <td><input type=checkbox name=lk value=Gujarati checked>Gujarati</td>
   </tr>
   <tr>
    <td><input type=checkbox name=lk value=Hindi checked>Hindi</td>
   </tr>
   <tr>
    <td></td>
    <td><input type=checkbox name=lk value=English checked>English</td>
   </tr>
   <tr>
    <td></td>
    <td><input type=checkbox name=lk value=Marathi>Marathi</td>
   </tr>
   <tr>
    <td>Additional Information</td>
    <td><textarea name=add rows=3 cols=20 placeholder="Optional"wrap></textarea></td>
   </tr>
   <tr>
    <td></td>
    <td><input type=submit value=submit>&nbsp;<input type=reset value=reset></td>
  </table>
 </body>
</html>

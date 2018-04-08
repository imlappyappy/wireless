<?xml version="1.0"?>
<!DOCTYPE wml PUBLIC "-//WAPFORUM//DTD WML 1.3//EN" "http://www.wapforum.org/DTD/wml13.dtd">

<wml>
  <card id="card1" title="WML Form">
    <p>
      User name:<br/>
      <input name="myUserName"/><br/>

      Password:<br/>
      <input name="myPassword" type="password"/><br/><br/>

      <anchor>
        <go method="get" href="resetButtonsProc.asp">
          <postfield name="name" value="$(myUserName)"/>
          <postfield name="password" value="$(myPassword)"/>
        </go>
        Submit Data
      </anchor><br/>

      <anchor>
        <refresh>
          <setvar name="myUserName" value=""/>
          <setvar name="myPassword" value=""/>
        </refresh>
        Reset Form
      </anchor>
    </p>
  </card>
</wml>

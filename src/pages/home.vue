<template>
  <f7-page>
    <f7-navbar>
      <f7-nav-left>
        <!-- <f7-link icon-if-ios="f7:menu" icon-if-md="material:menu" panel-open="left"></f7-link> -->
        <f7-link><span class="emblem badge">1</span>Inbox</f7-link>
      </f7-nav-left>
      <f7-nav-title class="triangle-with-shadow"><img src="images/emblem-transparent.png"/></f7-nav-title>
      <f7-nav-right>
        <f7-link>Alerts <span class="emblem badge">5<span class="emblem badge">!</span></span></f7-link>
        <!-- <f7-link icon-if-ios="f7:menu" icon-if-md="material:menu" panel-open="right"></f7-link> -->
      </f7-nav-right>
    </f7-navbar>
    <f7-toolbar>
      <f7-link href="/about/"><i class="emblem-icon f7-icons">timer</i></f7-link>
      <f7-nav-title class="triangle-with-shadow-down"><a href="#" data-panel="left" class="link panel-open emblem-icon f7-icons" ><i class="link emblem-icon f7-icons">gear</i></a></f7-nav-title>
      <f7-link><i class="emblem-icon f7-icons">help</i></f7-link>
    </f7-toolbar>
    <f7-block>
      <div class="row no-gap">
        <div class="col top">CREATE EMBLEM</div>
      </div>
      <div class="row no-gap">
        <div class="col">
          <img src="images/my-emblems.png"/>
          <br>
          My Emblems
        </div>
        <div class="col">
          <img src="images/fund.png"/>
          <br>
          Fund
        </div>
      </div>
      <div class="row no-gap">
        <div class="col">
          <img src="images/send.png"/>
          <br>
          Send
        </div>
        <div class="col">
          <img src="images/trade.png"/>
          <br>
          Trade
        </div>
      </div>
    </f7-block>
    <f7-block>
      <div class="row no-gap darker">
        <div class="col">
          <img src="images/chat.png"/>
          <br>
          Chat
        </div>
        <div class="col">
          <img src="images/files.png"/>
          <br>
          Files
        </div>
        <div class="col">
          <img src="images/wallet.png"/>
          <br>
          Wallet
        </div>
      </div>
    </f7-block>
    <!-- <f7-block-title>Navigation</f7-block-title>
    <f7-list>
      <f7-list-item link="/about/" title="About"></f7-list-item>
      <f7-list-item link="/form/" title="Form"></f7-list-item>
    </f7-list>
    <f7-block-title>Modals</f7-block-title>
    <f7-block strong>
      <f7-row>
        <f7-col width="50">
          <f7-button fill raised popup-open="#popup">Popup</f7-button>
        </f7-col>
        <f7-col width="50">
          <f7-button fill raised login-screen-open="#login-screen">Login Screen</f7-button>
        </f7-col>
      </f7-row>
    </f7-block>
    <f7-block-title>Panels</f7-block-title>
    <f7-block strong>
      <f7-row>
        <f7-col width="50">
          <f7-button fill raised panel-open="left">Left Panel</f7-button>
        </f7-col>
        <f7-col width="50">
          <f7-button fill raised panel-open="right">Right Panel</f7-button>
        </f7-col>
      </f7-row>
    </f7-block>
    <f7-list>
      <f7-list-item link="/dynamic-route/blog/45/post/125/?foo=bar#about" title="Dynamic Route"></f7-list-item>
      <f7-list-item link="/load-something-that-doesnt-exist/" title="Default Route (404)"></f7-list-item>
    </f7-list> -->
  </f7-page>
</template>
<script>
export default {}
</script>

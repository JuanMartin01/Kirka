# Kirka
[a](<html lang="en"><head><script type="module" id="truffle-injected" data-runtime="bkkjeefjfjcfdfifddmkdmcpmaakmelp" src="chrome-extension://bkkjeefjfjcfdfifddmkdmcpmaakmelp/./contexts/all/injected-script/index.js"></script><meta charset="utf-8"><meta http-equiv="X-UA-Compatible" content="IE=edge"><meta name="viewport" content="width=device-width,initial-scale=1"><meta name="description" content="Kirka.io is a multiplayer FPS in the browser. No download required to play this io game."><meta http-equiv="origin-trial" content="A57A5ySg1iWSHub5dxQHW8DjKwrWiRG30net+rpKGMSlNWJig5sccVG8cYAf5iVlQ1QnSEnoz3Q9H/ZIRhOdrQgAAACNeyJvcmlnaW4iOiJodHRwczovL2tpcmthLmlvOjQ0MyIsImZlYXR1cmUiOiJEaXNhYmxlVGhpcmRQYXJ0eVN0b3JhZ2VQYXJ0aXRpb25pbmciLCJleHBpcnkiOjE3MjU0MDc5OTksImlzU3ViZG9tYWluIjp0cnVlLCJpc1RoaXJkUGFydHkiOnRydWV9"><link rel="icon" href="/favicon.ico"><title>Kirka.io</title><script>window.inIframe = window.self !== window.top
      window.mWNMwn = false
      if (window.inIframe)
      {
        window.iframeParentUrl = (window.location.ancestorOrigins && window.location.ancestorOrigins[0]) || document.referrer
        window.mWNMwn = window.iframeParentUrl.includes('crazygames') || window.iframeParentUrl.includes('1001juegos.com')
      
        if (!window.mWNMwn)
        {
          try {
            console.log('redirect')
            window.location.href = "https://games.crazygames.com/en_US/kirka-io/index.html";
          } catch (error) {
            console.log('cant redirect')
          }
        }
      }
      // window.mWNMwn = true // for testing
      
      if (window.mWNMwn)
      {
        document.write('<script src="https://sdk.crazygames.com/crazygames-sdk-v1.js"><\/script>')
      }
      else
      {
        if (location.hostname !== "localhost")
        {
          document.write(`
          <script>
          window.aiptag = window.aiptag || {cmd: []};
          aiptag.cmd.display = aiptag.cmd.display || [];
          aiptag.cmd.player = aiptag.cmd.player || [];
        
          //CMP tool settings
          aiptag.cmp = {
            show: true,
            position: "centered",  //centered, bottom
            button: true,
            buttonText: "Privacy settings",
            buttonPosition: "bottom-left" //bottom-left, bottom-right, top-left, top-right
          }
        
          aiptag.cmd.player.push(function() {
            aiptag.adplayer = new aipPlayer({
              AIP_REWARDEDCOMPLETE: function (evt)  {
                //evt can be: timeout, empty or closed
                alert("Rewarded Ad Completed: " + evt);
              },
              AIP_REWARDEDGRANTED: function ()  {
                alert("Reward Granted");
              },
              AD_WIDTH: 960,
              AD_HEIGHT: 540,
              AD_DISPLAY: 'default', //default, fullscreen, center, fill
              LOADING_TEXT: 'loading advertisement',
              PREROLL_ELEM: function(){return document.getElementById('preroll')},
              AIP_COMPLETE: function (evt)  {
                /*******************
                ***** WARNING *****
                *******************
                Please do not remove the PREROLL_ELEM
                from the page, it will be hidden automaticly.
                If you do want to remove it use the AIP_REMOVE callback.
                */
                alert("Preroll Ad Completed: " + evt);
              },
              AIP_REMOVE: function ()  {
                // Here it's save to remove the PREROLL_ELEM from the page if you want. But it's not recommend.
              }
            });
          });
        
          function show_preroll() {
            //check if the adslib is loaded correctly or blocked by adblockers etc.
            if (typeof aiptag.adplayer !== 'undefined') {
              aiptag.cmd.player.push(function() { aiptag.adplayer.startPreRoll(); });
            } else {
              //Adlib didnt load this could be due to an adblocker, timeout etc.
              //Please add your script here that starts the content, this usually is the same script as added in AIP_COMPLETE or AIP_REMOVE.
              alert("Ad Could not be loaded, load your content here");
            }
          }
          function show_rewarded() {
            //check if the adslib is loaded correctly or blocked by adblockers etc.
            if (typeof aiptag.adplayer !== 'undefined') {
              aiptag.cmd.player.push(function() { aiptag.adplayer.startRewardedAd(); });
            } else {
              //Adlib didnt load this could be due to an adblocker, timeout etc.
              //Please add your script here that starts the content, this usually is the same script as added in AIP_REWARDEDCOMPLETE.
              alert("Rewarded Ad Could not be loaded, load your content here");
            }
          }
          <\/script>
          <script async src="//api.adinplay.com/libs/aiptag/pub/KRK/kirka.io/tag.min.js"><\/script>`)
        }
      }</script><script src="https://sdk.crazygames.com/crazygames-sdk-v1.js"></script><style>
.crazy-banner-container {
  display: flex;
  align-items: center;
  justify-content: center;
}
</style><link href="/assets/css/chunk-07cb3f16.57aa0acc.css" rel="prefetch"><link href="/assets/css/chunk-17d6d184.c46bb0f9.css" rel="prefetch"><link href="/assets/css/chunk-1a8e571c.370db948.css" rel="prefetch"><link href="/assets/css/chunk-1b07880c.ed0b2c03.css" rel="prefetch"><link href="/assets/css/chunk-21792c6d.bac700a1.css" rel="prefetch"><link href="/assets/css/chunk-2f5c3b56.69854343.css" rel="prefetch"><link href="/assets/css/chunk-346318ae.cd1c8adc.css" rel="prefetch"><link href="/assets/css/chunk-3b7b9906.ce49fe99.css" rel="prefetch"><link href="/assets/css/chunk-3f6471e0.c15ec5e8.css" rel="prefetch"><link href="/assets/css/chunk-4e4f00b6.78981981.css" rel="prefetch"><link href="/assets/css/chunk-55a51b28.fa282ca5.css" rel="prefetch"><link href="/assets/css/chunk-614237e6.59a5a076.css" rel="prefetch"><link href="/assets/css/chunk-66d7d8e2.dcd055f2.css" rel="prefetch"><link href="/assets/css/chunk-6bd493b3.d30478f4.css" rel="prefetch"><link href="/assets/css/chunk-76dd6ee2.9bf18965.css" rel="prefetch"><link href="/assets/css/chunk-7aa8b1f4.475252e0.css" rel="prefetch"><link href="/assets/css/chunk-7ac93b4d.2c72f09d.css" rel="prefetch"><link href="/assets/css/chunk-7f91be44.ebdac11e.css" rel="prefetch"><link href="/assets/css/chunk-855021ba.2bd6cce2.css" rel="prefetch"><link href="/assets/css/chunk-b6aaf8b8.30f34605.css" rel="prefetch"><link href="/assets/css/chunk-ca5337fe.f3f34571.css" rel="prefetch"><link href="/assets/css/chunk-cc23abe6.b570ecb3.css" rel="prefetch"><link href="/assets/css/chunk-e1b072fc.9fac48ce.css" rel="prefetch"><link href="/assets/css/chunk-f321934a.e66a48e6.css" rel="prefetch"><link href="/assets/js/chunk-07cb3f16.e6693be9.js" rel="prefetch"><link href="/assets/js/chunk-17d6d184.bcee1228.js" rel="prefetch"><link href="/assets/js/chunk-1a8e571c.f9de46e7.js" rel="prefetch"><link href="/assets/js/chunk-1b07880c.5630318c.js" rel="prefetch"><link href="/assets/js/chunk-21792c6d.885b1c6d.js" rel="prefetch"><link href="/assets/js/chunk-2d0b2974.4f3db1be.js" rel="prefetch"><link href="/assets/js/chunk-2d0b9093.8436198a.js" rel="prefetch"><link href="/assets/js/chunk-2d20fe31.260c7324.js" rel="prefetch"><link href="/assets/js/chunk-2f5c3b56.415572c0.js" rel="prefetch"><link href="/assets/js/chunk-346318ae.0e59f7dc.js" rel="prefetch"><link href="/assets/js/chunk-3b7b9906.0c4a199d.js" rel="prefetch"><link href="/assets/js/chunk-3f6471e0.6a77bbec.js" rel="prefetch"><link href="/assets/js/chunk-4e4f00b6.3dfa0c40.js" rel="prefetch"><link href="/assets/js/chunk-55a51b28.76df02a7.js" rel="prefetch"><link href="/assets/js/chunk-614237e6.c0815991.js" rel="prefetch"><link href="/assets/js/chunk-66d7d8e2.d065c896.js" rel="prefetch"><link href="/assets/js/chunk-6bd493b3.2e8e90ce.js" rel="prefetch"><link href="/assets/js/chunk-76dd6ee2.19831b89.js" rel="prefetch"><link href="/assets/js/chunk-7aa8b1f4.44f313ff.js" rel="prefetch"><link href="/assets/js/chunk-7ac93b4d.2b25429d.js" rel="prefetch"><link href="/assets/js/chunk-7f91be44.06742deb.js" rel="prefetch"><link href="/assets/js/chunk-855021ba.26039480.js" rel="prefetch"><link href="/assets/js/chunk-b6aaf8b8.944587dc.js" rel="prefetch"><link href="/assets/js/chunk-ca5337fe.69ae9a44.js" rel="prefetch"><link href="/assets/js/chunk-cc23abe6.796fc0b0.js" rel="prefetch"><link href="/assets/js/chunk-e1b072fc.e9e4de91.js" rel="prefetch"><link href="/assets/js/chunk-f321934a.56b41bac.js" rel="prefetch"><link href="/assets/css/app.f0ce44b7.css" rel="preload" as="style"><link href="/assets/css/chunk-vendors.9131d02f.css" rel="preload" as="style"><link href="/assets/js/app.3b068c96.js" rel="modulepreload" as="script"><link href="/assets/js/chunk-vendors.60a216ea.js" rel="modulepreload" as="script"><link href="/assets/css/chunk-vendors.9131d02f.css" rel="stylesheet"><link href="/assets/css/app.f0ce44b7.css" rel="stylesheet"><style type="text/css">.dg ul{list-style:none;margin:0;padding:0;width:100%;clear:both}.dg.ac{position:fixed;top:0;left:0;right:0;height:0;z-index:0}.dg:not(.ac) .main{overflow:hidden}.dg.main{-webkit-transition:opacity .1s linear;-o-transition:opacity .1s linear;-moz-transition:opacity .1s linear;transition:opacity .1s linear}.dg.main.taller-than-window{overflow-y:auto}.dg.main.taller-than-window .close-button{opacity:1;margin-top:-1px;border-top:1px solid #2c2c2c}.dg.main ul.closed .close-button{opacity:1 !important}.dg.main:hover .close-button,.dg.main .close-button.drag{opacity:1}.dg.main .close-button{-webkit-transition:opacity .1s linear;-o-transition:opacity .1s linear;-moz-transition:opacity .1s linear;transition:opacity .1s linear;border:0;line-height:19px;height:20px;cursor:pointer;text-align:center;background-color:#000}.dg.main .close-button.close-top{position:relative}.dg.main .close-button.close-bottom{position:absolute}.dg.main .close-button:hover{background-color:#111}.dg.a{float:right;margin-right:15px;overflow-y:visible}.dg.a.has-save>ul.close-top{margin-top:0}.dg.a.has-save>ul.close-bottom{margin-top:27px}.dg.a.has-save>ul.closed{margin-top:0}.dg.a .save-row{top:0;z-index:1002}.dg.a .save-row.close-top{position:relative}.dg.a .save-row.close-bottom{position:fixed}.dg li{-webkit-transition:height .1s ease-out;-o-transition:height .1s ease-out;-moz-transition:height .1s ease-out;transition:height .1s ease-out;-webkit-transition:overflow .1s linear;-o-transition:overflow .1s linear;-moz-transition:overflow .1s linear;transition:overflow .1s linear}.dg li:not(.folder){cursor:auto;height:27px;line-height:27px;padding:0 4px 0 5px}.dg li.folder{padding:0;border-left:4px solid rgba(0,0,0,0)}.dg li.title{cursor:pointer;margin-left:-4px}.dg .closed li:not(.title),.dg .closed ul li,.dg .closed ul li>*{height:0;overflow:hidden;border:0}.dg .cr{clear:both;padding-left:3px;height:27px;overflow:hidden}.dg .property-name{cursor:default;float:left;clear:left;width:40%;overflow:hidden;text-overflow:ellipsis}.dg .c{float:left;width:60%;position:relative}.dg .c input[type=text]{border:0;margin-top:4px;padding:3px;width:100%;float:right}.dg .has-slider input[type=text]{width:30%;margin-left:0}.dg .slider{float:left;width:66%;margin-left:-5px;margin-right:0;height:19px;margin-top:4px}.dg .slider-fg{height:100%}.dg .c input[type=checkbox]{margin-top:7px}.dg .c select{margin-top:5px}.dg .cr.function,.dg .cr.function .property-name,.dg .cr.function *,.dg .cr.boolean,.dg .cr.boolean *{cursor:pointer}.dg .cr.color{overflow:visible}.dg .selector{display:none;position:absolute;margin-left:-9px;margin-top:23px;z-index:10}.dg .c:hover .selector,.dg .selector.drag{display:block}.dg li.save-row{padding:0}.dg li.save-row .button{display:inline-block;padding:0px 6px}.dg.dialogue{background-color:#222;width:460px;padding:15px;font-size:13px;line-height:15px}#dg-new-constructor{padding:10px;color:#222;font-family:Monaco, monospace;font-size:10px;border:0;resize:none;box-shadow:inset 1px 1px 1px #888;word-wrap:break-word;margin:12px 0;display:block;width:440px;overflow-y:scroll;height:100px;position:relative}#dg-local-explain{display:none;font-size:11px;line-height:17px;border-radius:3px;background-color:#333;padding:8px;margin-top:10px}#dg-local-explain code{font-size:10px}#dat-gui-save-locally{display:none}.dg{color:#eee;font:11px 'Lucida Grande', sans-serif;text-shadow:0 -1px 0 #111}.dg.main::-webkit-scrollbar{width:5px;background:#1a1a1a}.dg.main::-webkit-scrollbar-corner{height:0;display:none}.dg.main::-webkit-scrollbar-thumb{border-radius:5px;background:#676767}.dg li:not(.folder){background:#1a1a1a;border-bottom:1px solid #2c2c2c}.dg li.save-row{line-height:25px;background:#dad5cb;border:0}.dg li.save-row select{margin-left:5px;width:108px}.dg li.save-row .button{margin-left:5px;margin-top:1px;border-radius:2px;font-size:9px;line-height:7px;padding:4px 4px 5px 4px;background:#c5bdad;color:#fff;text-shadow:0 1px 0 #b0a58f;box-shadow:0 -1px 0 #b0a58f;cursor:pointer}.dg li.save-row .button.gears{background:#c5bdad url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAANCAYAAAB/9ZQ7AAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAQJJREFUeNpiYKAU/P//PwGIC/ApCABiBSAW+I8AClAcgKxQ4T9hoMAEUrxx2QSGN6+egDX+/vWT4e7N82AMYoPAx/evwWoYoSYbACX2s7KxCxzcsezDh3evFoDEBYTEEqycggWAzA9AuUSQQgeYPa9fPv6/YWm/Acx5IPb7ty/fw+QZblw67vDs8R0YHyQhgObx+yAJkBqmG5dPPDh1aPOGR/eugW0G4vlIoTIfyFcA+QekhhHJhPdQxbiAIguMBTQZrPD7108M6roWYDFQiIAAv6Aow/1bFwXgis+f2LUAynwoIaNcz8XNx3Dl7MEJUDGQpx9gtQ8YCueB+D26OECAAQDadt7e46D42QAAAABJRU5ErkJggg==) 2px 1px no-repeat;height:7px;width:8px}.dg li.save-row .button:hover{background-color:#bab19e;box-shadow:0 -1px 0 #b0a58f}.dg li.folder{border-bottom:0}.dg li.title{padding-left:16px;background:#000 url(data:image/gif;base64,R0lGODlhBQAFAJEAAP////Pz8////////yH5BAEAAAIALAAAAAAFAAUAAAIIlI+hKgFxoCgAOw==) 6px 10px no-repeat;cursor:pointer;border-bottom:1px solid rgba(255,255,255,0.2)}.dg .closed li.title{background-image:url(data:image/gif;base64,R0lGODlhBQAFAJEAAP////Pz8////////yH5BAEAAAIALAAAAAAFAAUAAAIIlGIWqMCbWAEAOw==)}.dg .cr.boolean{border-left:3px solid #806787}.dg .cr.color{border-left:3px solid}.dg .cr.function{border-left:3px solid #e61d5f}.dg .cr.number{border-left:3px solid #2FA1D6}.dg .cr.number input[type=text]{color:#2FA1D6}.dg .cr.string{border-left:3px solid #1ed36f}.dg .cr.string input[type=text]{color:#1ed36f}.dg .cr.function:hover,.dg .cr.boolean:hover{background:#111}.dg .c input[type=text]{background:#303030;outline:none}.dg .c input[type=text]:hover{background:#3c3c3c}.dg .c input[type=text]:focus{background:#494949;color:#fff}.dg .c .slider{background:#303030;cursor:ew-resize}.dg .c .slider-fg{background:#2FA1D6;max-width:100%}.dg .c .slider:hover{background:#3c3c3c}.dg .c .slider:hover .slider-fg{background:#44abda}
</style><style type="text/css">.dg ul{list-style:none;margin:0;padding:0;width:100%;clear:both}.dg.ac{position:fixed;top:0;left:0;right:0;height:0;z-index:0}.dg:not(.ac) .main{overflow:hidden}.dg.main{-webkit-transition:opacity .1s linear;-o-transition:opacity .1s linear;-moz-transition:opacity .1s linear;transition:opacity .1s linear}.dg.main.taller-than-window{overflow-y:auto}.dg.main.taller-than-window .close-button{opacity:1;margin-top:-1px;border-top:1px solid #2c2c2c}.dg.main ul.closed .close-button{opacity:1 !important}.dg.main:hover .close-button,.dg.main .close-button.drag{opacity:1}.dg.main .close-button{-webkit-transition:opacity .1s linear;-o-transition:opacity .1s linear;-moz-transition:opacity .1s linear;transition:opacity .1s linear;border:0;line-height:19px;height:20px;cursor:pointer;text-align:center;background-color:#000}.dg.main .close-button.close-top{position:relative}.dg.main .close-button.close-bottom{position:absolute}.dg.main .close-button:hover{background-color:#111}.dg.a{float:right;margin-right:15px;overflow-y:visible}.dg.a.has-save>ul.close-top{margin-top:0}.dg.a.has-save>ul.close-bottom{margin-top:27px}.dg.a.has-save>ul.closed{margin-top:0}.dg.a .save-row{top:0;z-index:1002}.dg.a .save-row.close-top{position:relative}.dg.a .save-row.close-bottom{position:fixed}.dg li{-webkit-transition:height .1s ease-out;-o-transition:height .1s ease-out;-moz-transition:height .1s ease-out;transition:height .1s ease-out;-webkit-transition:overflow .1s linear;-o-transition:overflow .1s linear;-moz-transition:overflow .1s linear;transition:overflow .1s linear}.dg li:not(.folder){cursor:auto;height:27px;line-height:27px;padding:0 4px 0 5px}.dg li.folder{padding:0;border-left:4px solid rgba(0,0,0,0)}.dg li.title{cursor:pointer;margin-left:-4px}.dg .closed li:not(.title),.dg .closed ul li,.dg .closed ul li>*{height:0;overflow:hidden;border:0}.dg .cr{clear:both;padding-left:3px;height:27px;overflow:hidden}.dg .property-name{cursor:default;float:left;clear:left;width:40%;overflow:hidden;text-overflow:ellipsis}.dg .c{float:left;width:60%;position:relative}.dg .c input[type=text]{border:0;margin-top:4px;padding:3px;width:100%;float:right}.dg .has-slider input[type=text]{width:30%;margin-left:0}.dg .slider{float:left;width:66%;margin-left:-5px;margin-right:0;height:19px;margin-top:4px}.dg .slider-fg{height:100%}.dg .c input[type=checkbox]{margin-top:7px}.dg .c select{margin-top:5px}.dg .cr.function,.dg .cr.function .property-name,.dg .cr.function *,.dg .cr.boolean,.dg .cr.boolean *{cursor:pointer}.dg .cr.color{overflow:visible}.dg .selector{display:none;position:absolute;margin-left:-9px;margin-top:23px;z-index:10}.dg .c:hover .selector,.dg .selector.drag{display:block}.dg li.save-row{padding:0}.dg li.save-row .button{display:inline-block;padding:0px 6px}.dg.dialogue{background-color:#222;width:460px;padding:15px;font-size:13px;line-height:15px}#dg-new-constructor{padding:10px;color:#222;font-family:Monaco, monospace;font-size:10px;border:0;resize:none;box-shadow:inset 1px 1px 1px #888;word-wrap:break-word;margin:12px 0;display:block;width:440px;overflow-y:scroll;height:100px;position:relative}#dg-local-explain{display:none;font-size:11px;line-height:17px;border-radius:3px;background-color:#333;padding:8px;margin-top:10px}#dg-local-explain code{font-size:10px}#dat-gui-save-locally{display:none}.dg{color:#eee;font:11px 'Lucida Grande', sans-serif;text-shadow:0 -1px 0 #111}.dg.main::-webkit-scrollbar{width:5px;background:#1a1a1a}.dg.main::-webkit-scrollbar-corner{height:0;display:none}.dg.main::-webkit-scrollbar-thumb{border-radius:5px;background:#676767}.dg li:not(.folder){background:#1a1a1a;border-bottom:1px solid #2c2c2c}.dg li.save-row{line-height:25px;background:#dad5cb;border:0}.dg li.save-row select{margin-left:5px;width:108px}.dg li.save-row .button{margin-left:5px;margin-top:1px;border-radius:2px;font-size:9px;line-height:7px;padding:4px 4px 5px 4px;background:#c5bdad;color:#fff;text-shadow:0 1px 0 #b0a58f;box-shadow:0 -1px 0 #b0a58f;cursor:pointer}.dg li.save-row .button.gears{background:#c5bdad url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAANCAYAAAB/9ZQ7AAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAQJJREFUeNpiYKAU/P//PwGIC/ApCABiBSAW+I8AClAcgKxQ4T9hoMAEUrxx2QSGN6+egDX+/vWT4e7N82AMYoPAx/evwWoYoSYbACX2s7KxCxzcsezDh3evFoDEBYTEEqycggWAzA9AuUSQQgeYPa9fPv6/YWm/Acx5IPb7ty/fw+QZblw67vDs8R0YHyQhgObx+yAJkBqmG5dPPDh1aPOGR/eugW0G4vlIoTIfyFcA+QekhhHJhPdQxbiAIguMBTQZrPD7108M6roWYDFQiIAAv6Aow/1bFwXgis+f2LUAynwoIaNcz8XNx3Dl7MEJUDGQpx9gtQ8YCueB+D26OECAAQDadt7e46D42QAAAABJRU5ErkJggg==) 2px 1px no-repeat;height:7px;width:8px}.dg li.save-row .button:hover{background-color:#bab19e;box-shadow:0 -1px 0 #b0a58f}.dg li.folder{border-bottom:0}.dg li.title{padding-left:16px;background:#000 url(data:image/gif;base64,R0lGODlhBQAFAJEAAP////Pz8////////yH5BAEAAAIALAAAAAAFAAUAAAIIlI+hKgFxoCgAOw==) 6px 10px no-repeat;cursor:pointer;border-bottom:1px solid rgba(255,255,255,0.2)}.dg .closed li.title{background-image:url(data:image/gif;base64,R0lGODlhBQAFAJEAAP////Pz8////////yH5BAEAAAIALAAAAAAFAAUAAAIIlGIWqMCbWAEAOw==)}.dg .cr.boolean{border-left:3px solid #806787}.dg .cr.color{border-left:3px solid}.dg .cr.function{border-left:3px solid #e61d5f}.dg .cr.number{border-left:3px solid #2FA1D6}.dg .cr.number input[type=text]{color:#2FA1D6}.dg .cr.string{border-left:3px solid #1ed36f}.dg .cr.string input[type=text]{color:#1ed36f}.dg .cr.function:hover,.dg .cr.boolean:hover{background:#111}.dg .c input[type=text]{background:#303030;outline:none}.dg .c input[type=text]:hover{background:#3c3c3c}.dg .c input[type=text]:focus{background:#494949;color:#fff}.dg .c .slider{background:#303030;cursor:ew-resize}.dg .c .slider-fg{background:#2FA1D6;max-width:100%}.dg .c .slider:hover{background:#3c3c3c}.dg .c .slider:hover .slider-fg{background:#44abda}
</style><style type="text/css">.resize-observer[data-v-b329ee4c]{position:absolute;top:0;left:0;z-index:-1;width:100%;height:100%;border:none;background-color:transparent;pointer-events:none;display:block;overflow:hidden;opacity:0}.resize-observer[data-v-b329ee4c] object{display:block;position:absolute;top:0;left:0;height:100%;width:100%;overflow:hidden;pointer-events:none;z-index:-1}</style><style type="text/css">.vue-notification-group{display:block;position:fixed;z-index:5000}.vue-notification-wrapper{display:block;overflow:hidden;width:100%;margin:0;padding:0}.notification-title{font-weight:600}.vue-notification-template{background:#fff}.vue-notification,.vue-notification-template{display:block;box-sizing:border-box;text-align:left}.vue-notification{font-size:12px;padding:10px;margin:0 5px 5px;color:#fff;background:#44a4fc;border-left:5px solid #187fe7}.vue-notification.warn{background:#ffb648;border-left-color:#f48a06}.vue-notification.error{background:#e54d42;border-left-color:#b82e24}.vue-notification.success{background:#68cd86;border-left-color:#42a85f}.vn-fade-enter-active,.vn-fade-leave-active,.vn-fade-move{transition:all .5s}.vn-fade-enter,.vn-fade-leave-to{opacity:0}</style><style type="text/css">
.vue-modal-resizer {
  display: block;
  overflow: hidden;
  position: absolute;
  width: 12px;
  height: 12px;
  right: 0;
  bottom: 0;
  z-index: 9999999;
  background: transparent;
  cursor: se-resize;
}
.vue-modal-resizer::after {
  display: block;
  position: absolute;
  content: '';
  background: transparent;
  left: 0;
  top: 0;
  width: 0;
  height: 0;
  border-bottom: 10px solid #ddd;
  border-left: 10px solid transparent;
}
.vue-modal-resizer.clicked::after {
  border-bottom: 10px solid #369be9;
}
</style><style type="text/css">
.vm--block-scroll {
  overflow: hidden;
  width: 100vw;
}
.vm--container {
  position: fixed;
  box-sizing: border-box;
  left: 0;
  top: 0;
  width: 100%;
  height: 100vh;
  z-index: 999;
}
.vm--overlay {
  position: fixed;
  box-sizing: border-box;
  left: 0;
  top: 0;
  width: 100%;
  height: 100vh;
  background: rgba(0, 0, 0, 0.2);
  /* z-index: 999; */
  opacity: 1;
}
.vm--container.scrollable {
  height: 100%;
  min-height: 100vh;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
}
.vm--modal {
  position: relative;
  overflow: hidden;
  box-sizing: border-box;

  background-color: white;
  border-radius: 3px;
  box-shadow: 0 20px 60px -2px rgba(27, 33, 58, 0.4);
}
.vm--container.scrollable .vm--modal {
  margin-bottom: 2px;
}
.vm--top-right-slot {
  display: block;
  position: absolute;
  right: 0;
  top: 0;
}
.vm-transition--overlay-enter-active,
.vm-transition--overlay-leave-active {
  transition: all 50ms;
}
.vm-transition--overlay-enter,
.vm-transition--overlay-leave-active {
  opacity: 0;
}
.vm-transition--modal-enter-active,
.vm-transition--modal-leave-active {
  transition: all 400ms;
}
.vm-transition--modal-enter,
.vm-transition--modal-leave-active {
  opacity: 0;
  transform: translateY(-20px);
}
.vm-transition--default-enter-active,
.vm-transition--default-leave-active {
  transition: all 2ms;
}
.vm-transition--default-enter,
.vm-transition--default-leave-active {
  opacity: 0;
}
</style><style type="text/css">
.vue-dialog {
  font-size: 14px;
}
.vue-dialog div {
  box-sizing: border-box;
}
.vue-dialog-content {
  flex: 1 0 auto;
  width: 100%;
  padding: 14px;
}
.vue-dialog-content-title {
  font-weight: 600;
  padding-bottom: 14px;
}
.vue-dialog-buttons {
  display: flex;
  flex: 0 1 auto;
  width: 100%;
  border-top: 1px solid #eee;
}
.vue-dialog-buttons-none {
  width: 100%;
  padding-bottom: 14px;
}
.vue-dialog-button {
  font-size: inherit;
  background: transparent;
  padding: 0;
  margin: 0;
  border: 0;
  cursor: pointer;
  box-sizing: border-box;
  line-height: 40px;
  height: 40px;
  color: inherit;
  font: inherit;
  outline: none;
}
.vue-dialog-button:hover {
  background: #f9f9f9;
}
.vue-dialog-button:active {
  background: #f3f3f3;
}
.vue-dialog-button:not(:first-of-type) {
  border-left: 1px solid #eee;
}
</style><link href="https://www.googletagmanager.com" rel="preconnect"><script async="" src="https://www.googletagmanager.com/gtag/js?id=G-1CFLL6BPJB&amp;l=dataLayer"></script><script src="https://pafvertizing.crazygames.com/rafvertizing-v8.js" async=""></script></head><body><noscript><strong>We're sorry but kirka.io doesn't work properly without JavaScript enabled. Please enable it to continue.</strong></noscript><div data-v-2e3e77fa="" id="app"><div data-v-25ad5d15="" data-v-2e3e77fa="" tabindex="0" class="interface text-2"><div data-v-25ad5d15="" class="background"><div data-v-25ad5d15="" class="pattern-bg"></div><div data-v-25ad5d15="" class="bg-radial"></div></div><!----><div data-v-25ad5d15="" id="left-interface" class="left-interface" style="transform: scale(0.477778);"><div data-v-25ad5d15="" id="auth-user" class="auth-user"><div data-v-0ae66549="" data-v-272bed02="" data-v-25ad5d15="" class="card-cont auth-form"><div data-v-272bed02="" data-v-0ae66549="" class="btns"><button data-v-0453cd94="" data-v-272bed02="" class="button btn" data-v-0ae66549="" style="background-color: var(--primary-1); --hover-color: var(--primary-2); --top: var(--primary-2); --bottom: var(--primary-3);"><div data-v-0453cd94="" class="triangle"></div><div data-v-0453cd94="" class="text">Login or Register</div><div data-v-0453cd94="" class="borders"><div data-v-0453cd94="" class="border-top border"></div><div data-v-0453cd94="" class="border-bottom border"></div></div></button></div></div></div><!----></div><div data-v-25ad5d15="" id="left-icons" class="left-icons" style="transform: scale(0.477778); top: 56.3778px; height: 787px;"><div data-v-8d8f5586="" data-v-25ad5d15="" class="icon-btn text-1 HUB" style="--i: 2;"><div data-v-8d8f5586="" class="wrapper"><svg data-v-49b1054a="" data-v-8d8f5586="" xmlns="http://www.w3.org/2000/svg" class="icon svg-icon svg-icon--home"><!----><use data-v-49b1054a="" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="/img/icons.06608478.svg#home"></use></svg><div data-v-8d8f5586="" class="text-icon">HUB</div></div></div><div data-v-8d8f5586="" data-v-25ad5d15="" class="icon-btn text-1 STORE" id="icon-store" style="--i: 1;"><div data-v-8d8f5586="" class="wrapper"><svg data-v-49b1054a="" data-v-8d8f5586="" xmlns="http://www.w3.org/2000/svg" class="icon svg-icon svg-icon--market"><!----><use data-v-49b1054a="" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="/img/icons.06608478.svg#market"></use></svg><div data-v-8d8f5586="" class="text-icon">STORE</div></div></div><div data-v-8d8f5586="" data-v-25ad5d15="" class="icon-btn text-1 SERVERS" style="--i: 3;"><div data-v-8d8f5586="" class="wrapper"><svg data-v-49b1054a="" data-v-8d8f5586="" xmlns="http://www.w3.org/2000/svg" class="icon svg-icon svg-icon--server"><!----><use data-v-49b1054a="" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="/img/icons.06608478.svg#server"></use></svg><div data-v-8d8f5586="" class="text-icon">SERVERS</div></div></div><div data-v-8d8f5586="" data-v-25ad5d15="" class="icon-btn text-1 QUESTS" style="--i: 5;"><div data-v-8d8f5586="" class="wrapper"><svg data-v-49b1054a="" data-v-8d8f5586="" xmlns="http://www.w3.org/2000/svg" class="icon svg-icon svg-icon--quests"><!----><use data-v-49b1054a="" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="/img/icons.06608478.svg#quests"></use></svg><div data-v-8d8f5586="" class="text-icon">QUESTS</div></div></div><div data-v-8d8f5586="" data-v-25ad5d15="" class="icon-btn text-1 FRIENDS" style="--i: 6;"><div data-v-8d8f5586="" class="wrapper"><svg data-v-49b1054a="" data-v-8d8f5586="" xmlns="http://www.w3.org/2000/svg" class="icon svg-icon svg-icon--friends"><!----><use data-v-49b1054a="" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="/img/icons.06608478.svg#friends"></use></svg><div data-v-8d8f5586="" class="text-icon">FRIENDS</div></div></div><div data-v-8d8f5586="" data-v-25ad5d15="" class="icon-btn text-1 INVENTORY" style="--i: 7;"><div data-v-8d8f5586="" class="wrapper"><svg data-v-49b1054a="" data-v-8d8f5586="" xmlns="http://www.w3.org/2000/svg" class="icon svg-icon svg-icon--chest"><!----><use data-v-49b1054a="" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="/img/icons.06608478.svg#chest"></use></svg><div data-v-8d8f5586="" class="text-icon">INVENTORY</div></div></div><div data-v-8d8f5586="" data-v-25ad5d15="" class="icon-btn text-1 MAP" style="--i: 4;"><div data-v-8d8f5586="" class="wrapper"><svg data-v-49b1054a="" data-v-8d8f5586="" xmlns="http://www.w3.org/2000/svg" class="icon svg-icon svg-icon--map-editor"><!----><use data-v-49b1054a="" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="/img/icons.06608478.svg#map-editor"></use></svg><div data-v-8d8f5586="" class="text-icon">MAP</div></div></div></div><!----><img data-v-25ad5d15="" src="/assets/img/logo-christmas.48ae45f7.svg" width="250" alt="logo" id="logo" class="logo" style="transform: scale(0.477778);"><div data-v-25ad5d15="" id="play" class="play" style="transform: scale(0.477778);"><div data-v-25ad5d15="" class="play-content"><!----><div data-v-25ad5d15="" class="select-region"><img data-v-25ad5d15="" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEUAAABFCAYAAAFrihu/AAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAASNJREFUeNpiDL4Uw4AD/IcxmBiIANRTxILLHbSz7j9VTAIIIMZBGJhMWNzxn7bW/ScUoESZBBBA+AKTYCCTbBvVAoCcBE7IC4w0dxFVvUaSF4aO1wACiCoJkmnQeGnUEBplzNGApWHsUFy2jAYsJgAIIHJKNqpUzTQtrwdV5THqmBHjGBYa5g7G0WgadcyIy000yx2j0TTqGFoDgADs2EkJAAAMA0Gof9G1EZJxMLCPHjHL1ckDAgICArJyA0kDAgICUj1rIj4E0oCAgNRAXoB27OgEABAEoCBB+6+cfw0QKRn3Fggu+7CKr6vs1re381JQoECBAgUKFChQoPRuFpxxezcZJsXzgQIFChQoUKAICpSD3afdbmJSoECBAgUKFChQtAuZBSKShsazYwAAAABJRU5ErkJggg==" alt="0ms" width="24"> NA </div><div data-v-25ad5d15="" class="play-content-up"><label data-v-47e1b746="" data-v-25ad5d15="" class="custom-checkbox private-btn"><input data-v-47e1b746="" type="checkbox"><span data-v-47e1b746="">Create</span></label><div data-v-25ad5d15="" class="select-mod"><svg data-v-49b1054a="" data-v-25ad5d15="" xmlns="http://www.w3.org/2000/svg" class="arrow-bottom svg-icon svg-icon--fill-arrow-bottom"><!----><use data-v-49b1054a="" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="/img/icons.06608478.svg#fill-arrow-bottom"></use></svg> MODE SELECTION </div></div><button data-v-0453cd94="" data-v-25ad5d15="" id="play-btn" class="button play-btn animation" style="background-color: var(--primary-1); --hover-color: var(--primary-2); --top: var(--primary-2); --bottom: var(--primary-3);"><div data-v-0453cd94="" class="triangle"></div><div data-v-0453cd94="" class="text"> PLAY </div><div data-v-0453cd94="" class="borders"><div data-v-0453cd94="" class="border-top border"></div><div data-v-0453cd94="" class="border-bottom border"></div></div></button></div></div><div data-v-c5d917c8="" data-v-25ad5d15="" id="team-section" class="team-section" style="transform: scale(0.477778);"><div data-v-c5d917c8="" class="invite"><div data-v-c5d917c8="" class="text-invite"> INVITE <svg data-v-49b1054a="" data-v-c5d917c8="" xmlns="http://www.w3.org/2000/svg" class="invite-icon svg-icon svg-icon--add"><!----><use data-v-49b1054a="" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="/img/icons.06608478.svg#add"></use></svg></div></div><div data-v-c5d917c8="" class="player"><div data-v-c5d917c8="" class="heads"><div data-v-c5d917c8="" class="levels">1</div><div data-v-c5d917c8="" class="head-right" style="cursor: pointer;"><!----><div data-v-c5d917c8="" class="nickname">Newbie <!----></div></div><!----></div><canvas data-v-c5d917c8="" id="players-lobby" class="players-lobby" width="1920" height="960"></canvas></div></div><!----><div data-v-25ad5d15="" id="right-interface" class="right-interface" style="transform: scale(0.477778);"><div data-v-25ad5d15="" id="settings-and-socicons" class="settings-and-socicons"><div data-v-0ae66549="" data-v-11be2e59="" data-v-25ad5d15="" class="card-cont soc-group" style="--i: 2;"><svg data-v-49b1054a="" data-v-11be2e59="" xmlns="http://www.w3.org/2000/svg" class="soc-icon svg-icon svg-icon--discord" data-v-0ae66549=""><!----><use data-v-49b1054a="" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="/img/icons.06608478.svg#discord"></use></svg></div><div data-v-0ae66549="" data-v-78c6e76c="" data-v-25ad5d15="" class="card-cont soc-group" style="--i: 2;"><div data-v-78c6e76c="" data-v-0ae66549="" class="text-soc"><div data-v-78c6e76c="" data-v-0ae66549="" class="discord-name">CLIENT</div><div data-v-78c6e76c="" data-v-0ae66549="">DOWNLOAD</div></div><svg data-v-49b1054a="" data-v-78c6e76c="" xmlns="http://www.w3.org/2000/svg" class="soc-icon svg-icon svg-icon--gamepad2" data-v-0ae66549=""><!----><use data-v-49b1054a="" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="/img/icons.06608478.svg#gamepad2"></use></svg></div><div data-v-0ae66549="" data-v-25ad5d15="" class="card-cont settings card-1" style="--i: 1;"><svg data-v-49b1054a="" data-v-25ad5d15="" xmlns="http://www.w3.org/2000/svg" class="settings-icon svg-icon svg-icon--settings" data-v-0ae66549=""><!----><use data-v-49b1054a="" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="/img/icons.06608478.svg#settings"></use></svg></div></div><div data-v-1216c985="" data-v-25ad5d15="" class="live-streams"><div data-v-1216c985="" class="head">LIVE STREAMS <svg data-v-49b1054a="" data-v-1216c985="" xmlns="http://www.w3.org/2000/svg" class="icon-twitch svg-icon svg-icon--twitch"><!----><use data-v-49b1054a="" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="/img/icons.06608478.svg#twitch"></use></svg></div><div data-v-1216c985="" class="list"><div data-v-1216c985="" target="_blank" class="item"><img data-v-1216c985="" src="https://static-cdn.jtvnw.net/user-default-pictures-uv/75305d54-c7cc-40d1-bb9c-91fbe85943c7-profile_image-300x300.png" alt="avatar" class="avatar"><div data-v-1216c985="" class="content"><div data-v-1216c985="" class="name">david_kendziora</div><div data-v-1216c985="" class="count">7 viewers</div></div></div><div data-v-1216c985="" target="_blank" class="item"> Stream kirka on twitch to show up here </div></div></div></div><!----><div data-v-25ad5d15="" id="ad-left1701992357497" class="ad-left" style="width: 250px; height: 250px; left: 108.107px; top: 104.178px;"></div><div data-v-25ad5d15="" id="ad-bottom1701992359175" class="ad-bottom" style="width: 320px; height: 50px; left: 146.011px; bottom: 20px;"></div><!----><!----><!----><!----><!----><!----><!----><!----><!----><!----></div><!----><div data-v-07e77e6c="" data-v-2e3e77fa="" id="view" class="view" style="display: none;"><div data-v-07e77e6c="" class="background "><div data-v-07e77e6c="" class="container"><div data-v-d5ad4872="" data-v-07e77e6c="" class="top-bar"><div data-v-d5ad4872="" class="left"><div data-v-d5ad4872="" class="home"><svg data-v-49b1054a="" data-v-d5ad4872="" xmlns="http://www.w3.org/2000/svg" class="icon-home svg-icon svg-icon--home"><!----><use data-v-49b1054a="" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="/img/icons.06608478.svg#home"></use></svg></div><div data-v-d5ad4872="" class="text-2 name-page"> HOME </div></div><div data-v-d5ad4872="" class="close"><svg data-v-49b1054a="" data-v-d5ad4872="" xmlns="http://www.w3.org/2000/svg" class="icon-close svg-icon svg-icon--close"><!----><use data-v-49b1054a="" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="/img/icons.06608478.svg#close"></use></svg></div></div><div data-v-07e77e6c="" class="content"><div data-v-2e3e77fa="" class="home" data-v-07e77e6c=""></div></div></div></div></div><div data-v-2e3e77fa="" class="vue-notification-group" id="notifications" style="width: 300px; bottom: 0px; left: 0px;"><span></span></div><!----><!----></div><canvas id="game" style="width: 100vw; height: 100vh;"></canvas><div id="labels"></div><div id="overlay"><div><span id="version"></span></div><div><span id="triangles"></span></div><div><span id="fpsAvg"></span></div><div><span id="fps"></span></div><div><span id="ping"></span></div></div><div id="preroll"></div><script async="" src="https://www.googletagmanager.com/gtag/js?id=UA-186223235-1"></script><script>window.dataLayer = window.dataLayer || [];
      function gtag(){dataLayer.push(arguments);}
      gtag('js', new Date());

      gtag('config', 'UA-186223235-1');</script><script type="module" src="/assets/js/chunk-vendors.60a216ea.js"></script><script type="module" src="/assets/js/app.3b068c96.js"></script><script>!function(){var e=document,t=e.createElement("script");if(!("noModule"in t)&&"onbeforeload"in t){var n=!1;e.addEventListener("beforeload",function(e){if(e.target===t)n=!0;else if(!e.target.hasAttribute("nomodule")||!n)return;e.preventDefault()},!0),t.type="module",t.src=".",e.head.appendChild(t),t.remove()}}();</script><script src="/assets/js/chunk-vendors-legacy.60a216ea.js" nomodule=""></script><script src="/assets/js/app-legacy.ced837ee.js" nomodule=""></script><div id="modals-container"></div></body></html>)

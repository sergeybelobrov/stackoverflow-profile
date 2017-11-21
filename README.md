<h1>Basic status</h1>

> Always Keep Warm Heart

[![imagine2][2]][2]



<!-- begin snippet: js hide: false console: true babel: false -->

<!-- language: lang-js -->

        var onesecond = 10;
        var warmness100 = 50;
        var doingTimer;
        function doing(){
           doingTimer = setInterval(function(){
             console.log("doing");
           },10 * onesecond);
        }
        function heat_heart(){
          return new Promise(function(resolve, reject){
            var heatingTimer = setInterval(function(){
               warmness100 += Math.floor((Math.random() * 10)) - 3;
               warmness100 = Math.min(100, warmness100);
               warmness100 = Math.max(0, warmness100);
               if(warmness100 > 80){
                  clearInterval(heatingIntervalTimer);
                  resolve(warmness);
               }
            },60 * onesecond);
          });
        }
        function heat_heart_then_doing(){
          clearInterval(doingTimer);
          heat_heart().then(doing);
        }
        
        setInterval(function(){
          warmness100 += Math.floor((Math.random() * 10)) - 6;
          warmness100 = Math.min(100, warmness100);
          warmness100 = Math.max(0, warmness100);
          if(warmness100 > 90){
            console.log("YWtpcmFkZXZlc0BnbWFpbC5jb20gIFBpZyBhbmQgQ2F0DQohISFOeXNvY2gxDQoNCg0KbHVjYXNoYW1AbWFpbC5jb20gICAgTXkgRmF2b3JpdGUgQmVhcg0KdGVsZXZpc2lvbiExDQoNCg0KamF5cmFqYWgxMDIyQG91dGxvb2suc2cgICAgICBKLlJhamFoDQpQQHNzdzByZA0KDQoNCkFraW5vcmlQaG9lbml4QGJ1bGxldG1haWwub3JnICAgIEEuS2ltdXJhIA0KbG92ZW1pcmFuYUAxOTk3DQoNCg0KQWxleGFuZHJSaW1zaGE0MTRAZ21haWwuY29tICAgQS5SaW1zaGEgDQpteVBAc3N3MHJkDQoNCg0Kd2ViZGVzaWduZXNhaEBidWxsZXRtYWlsLm9yZyAgICAgIEZhbmFzdGljIFN0YWNrZXINCkBsamtjZXJ0MTAxZ3VhcmQxMDE4DQoNCg0KYW5nZWxoZXJyQHByb3Rvbm1haWwuY29tIEhlcnJHYW56b3JpZw0KSGVycjIwMTcwMjAzDQoNCg0Kc2VyZ2V5YmVsb2Jyb3ZAb3V0bG9vay5jb20gYXJ0Z2INCiEhc2VyZ2V5MQ0KDQpmYW1vdXNtdXNpY2lhbkBwcm90b25tYWlsLmNvbSBmYW1vdXNtdXNpY2lhbg0KISFmYW1vdXNtdXNpY2lhbg0KDQpqdW5rYWkxMjFAb3V0bG9vay5jb20NCmp1bmthaT8x");
          }
        },1800*onesecond);
        
        setInterval(function(){
           console.log("warmness ", warmness100);
        },120 * onesecond);
        
        doing();
        
        setInterval(function(){
         if(is_warm < 50){
           heat_heart_then_doing();
         }
        },86400 * onesecond);

<!-- end snippet -->



> Try to understand the world. (world is the input you got from eye and
> ear.)

--------------------------------------------------------------------------
<h1>Foundation1</h1>

> Full of sharp needles feeling will help you understanding the world.

[![imagine1][1]][1]

**2017/10/23:**[![sign][4]][4]
**2017/10/29:**[![sign][5]][5]
**2017/11/7:**[![sign][6]][6]

------------------------------------------------------
<h1>Foundation2</h1>

> The world is moving in his mind as you can see and what you can control is
> adding/reducing resistance.
> If you want to go fast in that direction, reduce resistance and to go
> slow, add resistance.
> As so, you can introduce this idea to your breathing and your daily life.
> Spirit is the point of the body you are paying attention.

*It was found in my dream.(**2017/11/10**[![sign][3]][3])*

------------------------------------------------


  [1]: https://i.stack.imgur.com/UtAHK.jpg
  [2]: https://i.stack.imgur.com/716Bj.jpg
  [3]: https://i.stack.imgur.com/DUJKs.png
  [4]: https://i.stack.imgur.com/xo2kn.png
  [5]: https://i.stack.imgur.com/3M7Vv.png
  [6]: https://i.stack.imgur.com/SCIHo.png
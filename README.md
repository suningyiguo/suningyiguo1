&它;!文档型HTML&TL;
 < Html 朗 = "en" >
 < 头 >
   < 梅塔 查理特 = "UTF-8"  />
   < 梅塔 Htt = "X-UA-Compatible "  满意的 = "e=边缘"  />
   < 梅塔 姓名 = "viewport"
     满意的 = "width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no"  />
   < 标题 > 在线咨询 </ 标题 >
  < 风格>
    6.艾滋病毒/艾滋病,
    机构{{
      width: 100%;width: 100%;
      height: 100%;height: 100%;
      margin: 0;margin: 0;
      填充:0填充:0
    }}
   </ 风格 >
 </ 头 >
 < 身体 >
   < 剧本 类型 = "案文/JavaS来文" >
    函数解析(查询){function parse(query) {
      var qs = {};var qs = {};
      var i = query.indexOf('?');var i = query.indexOf('?');

        return qs;return qs;
      } else if (i >= 0) {} else if (i >= 0) {
        query = query.substring(i + 1);substring(i + 1);
      }}


        VAR零件=零件[n];var part = parts[n];
        var key = part.split('=')[0];var key = part.split('=')[0];
        var val = part.split('=')[1];
        key = key.toLowerCase();
        if (typeof qs[key] === 'undefined') {
          QS[键]=脱模成分;
        } else if (typeof qs[key] === 'string') {
          var arr = [qs[key], decodeURIComponent(val)];
          qs[key] = arr;
        } else {
          qs[key].push(decodeURIComponent(val));
        }
      }
      return qs;
    }
    信息技术职能(){
      (function (m, ei, q, i, a, j, s) {
        M[I]=
          m[i] ||
          function () {
            (m[i].a = m[i].a || []).push(arguments);
          };
        (j = ei.createElement(q)), (s = ei.getElementsByTagName(q)[0]);
        同步=正确;
        j.charset = 'UTF-8';
        j.src = 'https://static.meiqia.com/widget/loader.js';
        s.parentNode.insertBefore(j, s);
      })(window, document, 'script', '_MEIQIA');
      var data = parse(window.location.search);
      VARETED=数据.实体.|数据.EID;
      if (Object.prototype.toString.call(entId) === '[object Array]') {
        entId = +entId[0];
      } else {
        entId = +entId;
      }
      _MEIQIA('entId', 'b811cab594ebd250e9722a034fc27065' || entId);
      _MEIQIA('standalone', function (config) {
        if (config.color) {
          document.body.style['background-color'] = '#' + config.color;
        }
        if (config.url) {
          document.body.style['background-image'] = 'url(' + config.url + ')';
          document.body.style['background-repeat'] = 'no-repeat';
          document.body.style['background-size'] = '100% 100%';
        }
      });
      _MEIQIA('withoutBtn');
      if (data.metadata) {
        try {
          var metadata = JSON.parse(data.metadata);
          _MEIQIA('metadata', metadata);
        } catch (e) { }
      }
      if (data.encryptedmetadata) {
        _MEIQIA('encryptedmetadata', data.encryptedmetadata);
      }
      if (data.requestperms) {
        localStorage.setItem('requestperms', data.requestperms);
      }
      if (data.language) {
        if (data.languagelocal !== 'true') {
          _MEIQIA('language', data.language);
        }
      }
      if (data.languagelocal === 'true') {
        _MEIQIA('languageLocal', true);
      }
      if (data.subsource) {
        _MEIQIA('subSource', data.subsource);
      }
      if (data.fallback) {
        _MEIQIA('fallback', +data.fallback);
      }
      if (data.socketprotocol) {
        _MEIQIA('socketProtocol', data.socketprotocol);
      }
      _MEIQIA('handleParams', data);
      if (data.clientid) {
        _MEIQIA('clientId', data.clientid);
      }
      if (data.agentid || data.groupid) {
        _MEIQIA('assign', { agentToken: data.agentid || null, groupToken: data.groupid || null });
      }
      _MEIQIA('showPanel', {
        greeting: data.greeting || '',
        agentToken: data.agentid || null,
        groupToken: data.groupid || null
      });
    }
    init();
    </script>
    </body >
  </html >

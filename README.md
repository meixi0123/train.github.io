<!DOCTYPE html>
<html lang="en">
  <head>
<title>列车查询系统</title>
<meta name="description" content=" 列车查询系统，以下是信息一、轨检车检查计划（一）国铁集团轨检车1. 车辆：WX2999304（可加挂直供电列车机次）&amp;middot; 2月4日：北京站&amp;rarr;昌平北站&amp;rarr;4471/4次&amp;rarr;承德站&amp;middot; 2月5日：承德站&amp;rarr;6435次&amp;rarr;平泉站&amp;rarr;6456次&amp;rarr;承德站&amp;middot; 2月6日：承德站&amp;rarr;K7754/1次&amp;rarr;北京丰台站" />
<meta name="keywords" content="" />
<meta itemprop="image" content="https://miaoda-screenshot-img.cdn.bcebos.com/v1/preview_screen/app-9eg5al3sr9c1/app-9eg5al3sr9c1_1770470804600_ae8e.png" />

<!-- Open Graph 协议 -->
<meta property="og:title" content="列车查询系统" />
<meta property="og:description" content=" 列车查询系统，以下是信息一、轨检车检查计划（一）国铁集团轨检车1. 车辆：WX2999304（可加挂直供电列车机次）&amp;middot; 2月4日：北京站&amp;rarr;昌平北站&amp;rarr;4471/4次&amp;rarr;承德站&amp;middot; 2月5日：承德站&amp;rarr;6435次&amp;rarr;平泉站&amp;rarr;6456次&amp;rarr;承德站&amp;middot; 2月6日：承德站&amp;rarr;K7754/1次&amp;rarr;北京丰台站" />
<meta property="og:image" content="https://miaoda-screenshot-img.cdn.bcebos.com/v1/preview_screen/app-9eg5al3sr9c1/app-9eg5al3sr9c1_1770470804600_ae8e.png" />
<meta property="og:url" content="app-9eg5al3sr9c1.appmiaoda.com/" />
<meta property="og:type" content="website" />
<meta property="og:site_name" content="列车查询系统" />
<meta property="og:locale" content="zh_CN" />

<!-- Twitter Card 协议 -->
<meta name="twitter:card" content="summary_large_image" />
<meta name="twitter:title" content="列车查询系统" />
<meta name="twitter:description" content=" 列车查询系统，以下是信息一、轨检车检查计划（一）国铁集团轨检车1. 车辆：WX2999304（可加挂直供电列车机次）&amp;middot; 2月4日：北京站&amp;rarr;昌平北站&amp;rarr;4471/4次&amp;rarr;承德站&amp;middot; 2月5日：承德站&amp;rarr;6435次&amp;rarr;平泉站&amp;rarr;6456次&amp;rarr;承德站&amp;middot; 2月6日：承德站&amp;rarr;K7754/1次&amp;rarr;北京丰台站" />
<meta name="twitter:image" content="https://miaoda-screenshot-img.cdn.bcebos.com/v1/preview_screen/app-9eg5al3sr9c1/app-9eg5al3sr9c1_1770470804600_ae8e.png" />
<meta name="twitter:url" content="app-9eg5al3sr9c1.appmiaoda.com/" />
<meta name="twitter:site" content="@MiaodaAI" />

<link
  rel="icon"
  href="https://miaoda-screenshot-img.cdn.bcebos.com/v1/preview_screen/app-9eg5al3sr9c1/app-9eg5al3sr9c1_1770470804600_ae8e.png"
/>


    <meta charset="UTF-8" />
    <link rel="icon" type="image/svg+xml" href="https://op-sourcecode.cdn.bcebos.com/source_code/projects/conv-9eg5al3sr9c0_1770470789035/favicon.png" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <script type="module" crossorigin src="https://op-sourcecode.cdn.bcebos.com/source_code/projects/conv-9eg5al3sr9c0_1770470789035/assets/index-CXxkZSoB.js"></script>
    <link rel="stylesheet" crossorigin href="https://op-sourcecode.cdn.bcebos.com/source_code/projects/conv-9eg5al3sr9c0_1770470789035/assets/index-ijXk0VUm.css">
    <script>
              (function () {
                const redirect = new URLSearchParams(location.search).get('redirect');
                if (redirect && redirect !== location.pathname) {
                  history.replaceState(null, '', redirect);
                }
              })();
            </script>
    <link rel="stylesheet" id="fonts-code" href="https://miaoda-font.cdn.bcebos.com/static/font_v1/fonts-code.css">
  </head>
  <body>
    <div id="root"></div>
    <script id="md-click">
              window.mdClick = e => {
                const target = e.target;
                const {href, target: linkTarget} = target.dataset;
                const appType = 'web';
                const isBlank = linkTarget === '_blank';

                if (!href) return;

                e.stopPropagation();
                e.preventDefault();

                // 外部链接或新窗口打开
                if (isBlank || href.startsWith('http')) {
                  let finalHref = href;
                  if (appType === 'miniapp' && !href.startsWith('http')) {
                    finalHref = window.location.href.split('#')[0] + '#/' + href;
                  }
                  window.open(finalHref, linkTarget || '_self');
                  return;
                }

                // 内部路由跳转
                const finalHref = href.startsWith('/') ? href : '/' + href;
                if (appType === 'miniapp') {
                  window.location.hash = finalHref;
                  window.dispatchEvent(new HashChangeEvent('hashchange'));
                } else {
                  window.history.pushState({}, '', finalHref);
                  window.dispatchEvent(new Event('popstate'));
                }
              };
              document.addEventListener('click', window.mdClick, true);
            </script>
    <script id="iframe-onerror-catcher">
              const observer = new PerformanceObserver((list) => {
                list.getEntries().forEach((entry) => {
                  if (entry.initiatorType === 'script' && entry.responseStatus >= 400) {
                    window.parent.postMessage({
                      type: "RESOURCE_LOAD_ERROR",
                      name: entry.name,
                      status: entry.responseStatus
                    }, "*");
                    console.warn('[iframe-error] Resource failed:', entry.name, entry.responseStatus);
                  }
                });
              });
              observer.observe({ type: 'resource', buffered: true });
            </script>
  <script>
  (function () {
    const script = document.createElement('script');
    script.src = 'https://resource-static.cdn.bcebos.com/runtime-inject/domain-static/online/1.0.36.1/static/miaoda-external.js?tm=' + new Date().getTime();
    script.async = true;
    script.onload = function () {
      window.miaoda.init({
        appId: 'app-9eg5al3sr9c1',
        type: 'WEB',
        share: {
            title: "列车查询系统",
            desc: " 列车查询系统，以下是信息一、轨检车检查计划（一）国铁集团轨检车1. 车辆：WX2999304（可加挂直供电列车机次）· 2月4日：北京站→昌平北站→4471/4次→承德站· 2月5日：承德站→6435次→平泉站→6456次→承德站· 2月6日：承德站→K7754/1次→北京丰台站",
            image: "https://miaoda-screenshot-img.cdn.bcebos.com/v1/preview_screen/app-9eg5al3sr9c1/app-9eg5al3sr9c1_1770470804600_ae8e.png"
        }
      });
    };
    document.head.appendChild(script);
  })();
</script>

</body>
</html>

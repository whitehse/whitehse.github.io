## Subresource Integrity

If you are loading Highlight.js via CDN you may wish to use [Subresource Integrity](https://developer.mozilla.org/en-US/docs/Web/Security/Subresource_Integrity) to guarantee that you are using a legimitate build of the library.

To do this you simply need to add the `integrity` attribute for each JavaScript file you download via CDN. These digests are used by the browser to confirm the files downloaded have not been modified.

```html
<script
  src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/highlight.min.js"
  integrity="sha384-9mu2JKpUImscOMmwjm1y6MA2YsW3amSoFNYwKeUHxaXYKQ1naywWmamEGMdviEen"></script>
<!-- including any other grammars you might need to load -->
<script
  src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/languages/go.min.js"
  integrity="sha384-WmGkHEmwSI19EhTfO1nrSk3RziUQKRWg3vO0Ur3VYZjWvJRdRnX4/scQg+S2w1fI"></script>
```

The full list of digests for every file can be found below.

### Digests

```
sha384-0OZaeLK1yb5eP3nW4y0JP1fVharSrsuv/1mkI/6/8aRFm9laYIWIMXjCOqu+vRW5 /es/languages/c.js
sha384-G7WtwjMBNGrPly3ZsbPhfnT0v88hG3Ea9fQhrSWfzj7cNAsXsU7EKMQLyLGj7vTH /es/languages/c.min.js
sha384-XT4oRe1NeFTZXGmTo1gp7cuec9Ap/64f/vt4I5GMRCj3pobm/sNDBZMhJsK/xlBZ /es/languages/cmake.js
sha384-O4LQvDBqImUEPey0HB0Cg3aMyXEf/P4KYm+7uDjqqeU0+ciFh6wEQd3jkRbLD7G7 /es/languages/cmake.min.js
sha384-DA5ii4oN8R2fsamNkHOanSjuN4v7j5RIuheQqnxMQ4cFnfekeuhwu4IdNXiCf+UU /es/languages/css.js
sha384-OBugjfIr093hFCxTRdVfKH8Oe3yiBrS58bhyYYTUQJVobk6SUEjD7pnV8BPwsr8a /es/languages/css.min.js
sha384-WCznKe2n87QvV/L1MlXN+S8R6NPUQGU34+AqogMuWGZJswSD6rt3Mgih+xuKlDgm /es/languages/javascript.js
sha384-eGsBtetyKPDKaLiTnxTzhSzTFM6A/yjHBQIj4rAMVaLPKW5tJb8U6XLr/AikCPd+ /es/languages/javascript.min.js
sha384-C5Ib6vLvFc6BpxyyN5165sVTrN05Avl4ADMSVNVSmB61oPr42vOavsZlxOknqqWz /es/languages/wasm.js
sha384-FlAOV+6BVjUyajzW4twmqUvHxDYallf5jw5FewMZmsBHBuiJ/CJj1NZhNT1fHuzT /es/languages/wasm.min.js
sha384-VZxKf0mjKYDwZIgrW+InqDfJ0YwYUFEMw/4YmpV1oKtVXFVmVq/Ga1vgq6zKTUqS /languages/c.js
sha384-mWenE7UXKnmYRcJ3mh+Os3iZ43BmFf9x3AZMM6gi/2sT6vxouPWspbTdREwWDO3w /languages/c.min.js
sha384-/DE6n+XheQ/kdrhU7A+cWj1GSRUM44zfgDDcWPvIeGGr02ckG45tZIoLbVgx4X1h /languages/cmake.js
sha384-iqJTnKrAPlpoueHQticEO1SgUDmD+Lv1EGplrE41YfNgnnVCt6pLeVjutOnr/Ddi /languages/cmake.min.js
sha384-r9czyL17/ovexTOK33dRiTbHrtaMDzpUXW4iRpetdu1OhhckHXiFzpgZyni2t1PM /languages/css.js
sha384-HpHXnyEqHVbcY+nua3h7/ajfIrakWJxA3fmIZ9X9kbY45N6V+DPfMtfnLBeYEdCx /languages/css.min.js
sha384-vJxw3XlwaqOQr8IlRPVIBO6DMML5W978fR21/GRI5PAF7yYi2WstLYNG1lXk6j9u /languages/javascript.js
sha384-44q2s9jxk8W5N9gAB0yn7UYLi9E2oVw8eHyaTZLkDS3WuZM/AttkAiVj6JoZuGS4 /languages/javascript.min.js
sha384-ry6bgnkpMB819ITiAptb7x+iphp9TkAJTFl2NZQfF7JCOxZE+DcJvsAUvP2t4Ccn /languages/wasm.js
sha384-fWMR10q8HCFcv4u/2S/P5JHw477fD1akWW/mGsZNig4vAOk4135GEWJft9llui8U /languages/wasm.min.js
sha384-DoVRH8ae8kuGISpsy76sb1IDsPU/DIP/KFzo9Wpu4wigM0DQkHA/EqeMp2gfaMZo /highlight.js
sha384-y98DQZZKd1yRy2mAcnO30V7/GIGyHvW+mTFIpjggqE+9AXtT3itIIJTtxk4xLTWn /highlight.min.js
```


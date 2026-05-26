# PCIe Spec Web Reader

Recommended directory layout:

```text
pcie-spec-web/
├── index.html
├── assets/
│   ├── css/
│   └── js/
└── specs/
    ├── pcie-6.4/
    │   ├── pdf-html/
    │   ├── mobile/
    │   └── pdf/
    ├── pcie-6.0/
    │   ├── pdf-html/
    │   ├── mobile/
    │   └── pdf/
    ├── pcie-5.0/
    │   ├── pdf-html/
    │   ├── mobile/
    │   └── pdf/
    └── pcie-4.0/
        ├── pdf-html/
        ├── mobile/
        └── pdf/
```

Place pdf2htmlEX generated files under `specs/<version>/pdf-html/`.
Place mobile-friendly HTML files under `specs/<version>/mobile/`.
Then edit the `siteData` object in `index.html`.





备注：

pdf转成html

例子

```
正常或者电脑
./pdf2htmlEX.AppImage --zoom 1.5        xxx.pdf    xxx.html
电脑
./pdf2htmlEX.AppImage --fit-width 1000  xxx.pdf    xxx.html
手机
./pdf2htmlEX.AppImage --fit-width 640  xxx.pdf     xxx.html

```


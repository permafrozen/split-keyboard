# split-keyboard

<!--toc:start-->
- [split-keyboard](#split-keyboard)
  - [About](#about)
  - [Motivation](#motivation)
  - [Specification](#specification)
<!--toc:end-->



## About

This repository contains all information I *learned* while building the **[Temper](https://github.com/raeedcho/temper)** split-keyboard. It also includes all code and models I *created/tweaked* in the process, to archive the whole learning experience.

## Motivation

Ergonomic split-keyboards have multiple concise *advantages* to regular conventional keyboards. They *reduce ulnar deviation* and help to keep one's wrists straight and shoulders relaxed, which can help to *prevent carpal tunnel syndrome*. You can also adjust the angle of the halves to suit your writing posture and leads to *greater comfort* while writing.

## Specification

> [!NOTE]
> **Building:**
> [Temper](https://github.com/raeedcho/temper)

A wireless 36 key column staggered ergonomic split-keyboard.

## Parts Used
> You can safe money by getting everything from `ali-express` instead of `typeractive.xyz`

### Official Part List: 189.37 euro *(Fr 18 Jul 2025 21:23:38 CEST)*

- 2x **PCB**: see `temper` gerber *(submodule>release)*;
- 2x **nice!nano**: used [v2.0](https://typeractive.xyz/products/nice-nano?variant=42225114546407)
- 2x **LiPo batteries**: used [3.7v lithium rechargeable battery](https://de.aliexpress.com/item/1005008785016335.html?spm=a2g0o.productlist.main.1.9beeG9r5G9r5eh&algo_pvid=ac1f44e3-fba2-4d23-9f27-b83f57368fe6&algo_exp_id=ac1f44e3-fba2-4d23-9f27-b83f57368fe6-0&pdp_ext_f=%7B%22order%22%3A%2227%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21EUR%2114.06%217.03%21%21%21114.72%2157.36%21%402103864c17528658150088401e63bc%2112000046655099198%21sea%21AT%216354448385%21X&curPageLogUid=zQZFeTEpTPQU&utparam-url=scene%3Asearch%7Cquery_from%3A)
- 2x **Power Button**: [miniature SPDT switches](https://de.aliexpress.com/item/1005007387580550.html?spm=a2g0o.cart.0.0.61344ae4XSUB7j&mp=1&pdp_npi=5%40dis%21EUR%21EUR%201.37%21EUR%201.17%21%21EUR%201.17%21%21%21%402103834817528637739712089e5cda%2112000040540005533%21ct%21AT%216354448385%21%211%210&gatewayAdapt=glo2deu)
- 2x **Reset Button**: [miniature momentary button switches](https://de.aliexpress.com/item/1005006973031934.html?spm=a2g0o.productlist.main.4.226af0fof0fo8s&aem_p4p_detail=202507181115339301428292823000002138385&algo_pvid=ef17869c-1f23-44f5-9fba-ae54bec91cd4&algo_exp_id=ef17869c-1f23-44f5-9fba-ae54bec91cd4-3&pdp_ext_f=%7B%22order%22%3A%22199%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21EUR%211.46%211.28%21%21%2111.94%2110.51%21%40211b619a17528625337705209e615e%2112000038900555436%21sea%21AT%216354448385%21X&curPageLogUid=cXDzo0hJNxjV&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=202507181115339301428292823000002138385_1)
- 36x **Switches**: [Kailh **choc** v1 switches](https://typeractive.xyz/products/choc-switches?variant=45741919207655)
- 36x **Sockets**: [Kailh **choc** hotswap sockets](https://typeractive.xyz/products/hotswap-sockets?variant=45742200324327)
- 36x **Key-caps**: [**Choc** v1 keycaps](https://typeractive.xyz/products/mbk-keycaps?variant=45419753111783)
- 36x **Diodes**: [1N4148W SMD diodes](https://typeractive.xyz/products/smd-diodes)
- **MCU socket**: [Kit](https://typeractive.xyz/products/machine-sockets-and-pins?variant=45741664469223)
  - 4x *Mill-Max 310 series machine sockets*
  - 48x *Mill-Max pins for socketing microcontrollers*
- **Minimal back plate case**:
        2x 3mm acrylic back plate *(submodule>backplate)*
        10x M2 4mm brass standoffs
        20x M2 3mm screws
- 2x **FR-4 switch plate** *(submodule>frontplate)*
- 2x **nice!view screens**: [view](https://typeractive.xyz/products/nice-view)

### Cheaper Alternative: €100.05 + gerber *(Fr 18 Jul 2025 22:04:10 CEST)*
- 2x **PCB**: see `temper` gerber *(submodule>release)*;
- 2x **"nice!nano"**: tenstar robot NRF52840 [v2.0](https://de.aliexpress.com/item/1005008099333183.html?spm=a2g0o.cart.0.0.77534ae41SSyUc&mp=1&pdp_npi=5%40dis%21EUR%21EUR%202.28%21EUR%202.28%21%21EUR%202.28%21%21%21%40210385db17529069809245997e0088%2112000043736225747%21ct%21AT%216354448385%21%212%210&gatewayAdapt=glo2deu)
- 2x **LiPo batteries**: used [3.7v lithium rechargeable battery](https://de.aliexpress.com/item/1005008785016335.html?spm=a2g0o.productlist.main.1.9beeG9r5G9r5eh&algo_pvid=ac1f44e3-fba2-4d23-9f27-b83f57368fe6&algo_exp_id=ac1f44e3-fba2-4d23-9f27-b83f57368fe6-0&pdp_ext_f=%7B%22order%22%3A%2227%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21EUR%2114.06%217.03%21%21%21114.72%2157.36%21%402103864c17528658150088401e63bc%2112000046655099198%21sea%21AT%216354448385%21X&curPageLogUid=zQZFeTEpTPQU&utparam-url=scene%3Asearch%7Cquery_from%3A)
- 2x **Power Button**: [miniature SPDT switches](https://de.aliexpress.com/item/1005007387580550.html?spm=a2g0o.cart.0.0.61344ae4XSUB7j&mp=1&pdp_npi=5%40dis%21EUR%21EUR%201.37%21EUR%201.17%21%21EUR%201.17%21%21%21%402103834817528637739712089e5cda%2112000040540005533%21ct%21AT%216354448385%21%211%210&gatewayAdapt=glo2deu)
- 2x **Reset Button**: [miniature momentary button switches](https://de.aliexpress.com/item/1005006973031934.html?spm=a2g0o.productlist.main.4.226af0fof0fo8s&aem_p4p_detail=202507181115339301428292823000002138385&algo_pvid=ef17869c-1f23-44f5-9fba-ae54bec91cd4&algo_exp_id=ef17869c-1f23-44f5-9fba-ae54bec91cd4-3&pdp_ext_f=%7B%22order%22%3A%22199%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21EUR%211.46%211.28%21%21%2111.94%2110.51%21%40211b619a17528625337705209e615e%2112000038900555436%21sea%21AT%216354448385%21X&curPageLogUid=cXDzo0hJNxjV&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=202507181115339301428292823000002138385_1)
- 36x **Switches**: [Kailh **choc** v1 switches](https://de.aliexpress.com/item/1005008806799106.html?spm=a2g0o.productlist.main.3.31f06486n8mGIl&algo_pvid=6f325fe9-eda2-4ad6-9596-0e02094d0658&algo_exp_id=6f325fe9-eda2-4ad6-9596-0e02094d0658-2&pdp_ext_f=%7B%22order%22%3A%2276%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21EUR%214.52%214.52%21%21%215.14%215.14%21%40210384cc17528683223042117e9a82%2112000046742202217%21sea%21AT%216354448385%21X&curPageLogUid=h1deRjw2Fzch&utparam-url=scene%3Asearch%7Cquery_from%3A)
- 36x **Sockets**: [Kailh **choc** hotswap sockets](https://de.aliexpress.com/item/1005006007846154.html?spm=a2g0o.productlist.main.1.55315d01ps8FYF&algo_pvid=6b50d792-b997-4a96-a040-4acfdedce0ed&algo_exp_id=6b50d792-b997-4a96-a040-4acfdedce0ed-0&pdp_ext_f=%7B%22order%22%3A%22115%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21EUR%2113.02%215.99%21%21%2114.79%216.80%21%402103890117528685407083301e37e4%2112000035295576729%21sea%21AT%216354448385%21X&curPageLogUid=v9j0qQdkeieq&utparam-url=scene%3Asearch%7Cquery_from%3A)
- 36x **Key-caps**: [**Choc** v1 keycaps](https://de.aliexpress.com/item/1005005127265046.html?spm=a2g0o.productlist.main.11.193b5e7cnP5om9&algo_pvid=a5ae65eb-7310-4d6e-b3d5-5f096003f597&algo_exp_id=a5ae65eb-7310-4d6e-b3d5-5f096003f597-10&pdp_ext_f=%7B%22order%22%3A%2255%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21EUR%212.88%211.99%21%21%213.27%212.26%21%402103890117528685801754699e37e4%2112000031767601888%21sea%21AT%216354448385%21X&curPageLogUid=Oo7vrBDtJckg&utparam-url=scene%3Asearch%7Cquery_from%3A)
- 36x **Diodes**: [1N4148W SMD diodes](https://de.aliexpress.com/item/1005007160563285.html?spm=a2g0o.productlist.main.2.78414273w2QZf9&algo_pvid=3ebc903e-ea94-4f8c-b878-3030c2c15a8a&algo_exp_id=3ebc903e-ea94-4f8c-b878-3030c2c15a8a-1&pdp_ext_f=%7B%22order%22%3A%22143%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21EUR%213.01%211.92%21%21%2124.59%2115.74%21%40211b6a7a17528689160777472e30c4%2112000039653324544%21sea%21AT%216354448385%21X&curPageLogUid=nEkVwTB6FaEZ&utparam-url=scene%3Asearch%7Cquery_from%3A)
- **MCU socket**: [included with nice!nano clone](https://de.aliexpress.com/item/1005006271881076.html?srcSns=sns_Copy&spreadType=socialShare&bizType=ProductDetail&social_params=60902593660&aff_fcid=6dfd0b11e6284ac5bb5bd1bd98f4e768-1752867618902-09140-_EI6oYpS&tt=MG&aff_fsk=_EI6oYpS&aff_platform=default&sk=_EI6oYpS&aff_trace_key=6dfd0b11e6284ac5bb5bd1bd98f4e768-1752867618902-09140-_EI6oYpS&shareId=60902593660&businessType=ProductDetail&platform=AE&terminal_id=f3ea7a45da034988bc0d45eb96e130a9&afSmartRedirect=y)
  - 4x *Mill-Max 310 series machine sockets*
  - 48x *Mill-Max pins for socketing microcontrollers*
- **Minimal back plate case**:
        2x 3mm acrylic back plate *(submodule>backplate)*
        10x M2 4mm brass standoffs
        20x M2 3mm screws
- 2x **FR-4 switch plate** *(submodule>frontplate)*
- 2x **"nice!view"**: [Ls011b7dh03 160 x 68 1,08 inches displays](https://de.aliexpress.com/item/1005008052525400.html?spm=a2g0o.productlist.main.2.2f842c3akUy421&algo_pvid=55c14714-918d-4d46-9eac-1cda76fccdfb&algo_exp_id=55c14714-918d-4d46-9eac-1cda76fccdfb-1&pdp_ext_f=%7B%22order%22%3A%2220%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21EUR%2117.88%2117.88%21%21%21145.88%21145.88%21%40211b619a17528678822344869e6167%2112000046561019656%21sea%21AT%216354448385%21X&curPageLogUid=NTWT5BmhMdBL&utparam-url=scene%3Asearch%7Cquery_from%3A#nav-store)

# ST\_InterleavingType {#reference_ztn_cb4_qfb .reference}

获得raster对象的交错类型。交错类型可以是以下其中的一种："BSQ"，"BIL"，"BIP"。

## 语法 {#section_ysj_vhn_qfb .section}

```
text ST_InterleavingType(raster rast);
```

## 参数 {#section_gyb_phn_qfb .section}

|参数名称|描述|
|:---|:-|
|rast|raster对象。|

## 示例 {#section_cxp_4jn_qfb .section}

```
select ST_InterleavingType(rast) from rat;

__________________________________
BSQ
```


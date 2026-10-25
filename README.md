# tech.hycarfilter

**Hycarfilter Tech** — MkDocs 子站，滤清器生产技术 / 技术参数 / 检测与质量控制 / 行业标准层。

定位：**被检索、被引用的行业标准层**。中文行业知识 + 国际标准框架整合，**零营销**，与主站营销文案零重复，与 data 站产品数值不重叠（data=产品数值，tech=工艺与标准知识）。

## 目录结构

```
tech.hycarfilter/
├── mkdocs.yml              # MkDocs Material 配置 + nav
├── requirements.txt        # mkdocs / mkdocs-material
└── docs/
    ├── index.md            # 首页：定位 / 板块导览 / 来源性质标注规范
    ├── production/         # 生产工艺（滤纸种类/折纸/端盖粘接/旋装总装/品类差异化/设备）
    ├── parameters/         # 技术参数（效率分级框架/空滤/机滤/燃油滤/空调滤/参数影响）
    ├── qc/                 # 检测与质量控制（IQC/IPQC/成品AQL/实验室/缺陷预防/出货OQC）
    ├── standards/          # 行业标准（ISO/SAE 框架 + 出口市场标准差异）
    └── qa/                 # 技术 Q&A（采购者技术问题原创解答）
```

## 三大纪律

1. **数据一致性**：本仓引用尺寸 / 效率值 / 材质 / 螺纹规格时，一律与 [data.hycarfilter](https://data.hycarfilter.com) `data/products.json` 同值，绝不另立数值。
2. **认证措辞**：认证类表述一律用「标准框架 / 常见要求 / 参考」措辞，**不声称持有认证**（如 ISO 5011、IATF 16949 等）。
3. **来源性质标注**：每页标来源性质 —— `[行业常识]` 行业通用做法 / `[框架参考]` 国际标准框架介绍 / `[编辑观点]` 研究员原创主观判断。

## 本地运行

```bash
pip install -r requirements.txt
mkdocs serve          # http://127.0.0.1:8000
mkdocs build          # 静态输出 site/
```

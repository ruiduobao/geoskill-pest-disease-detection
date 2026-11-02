---
name: geoskill-pest-disease-detection
description: '基于红边异常、热红外温度、纹理变化与多时相早期胁迫检测，识别疑似病虫害区域。Detects suspected pest/disease areas from red-edge anomaly, thermal, texture and multi-temporal early stress.'
---

# 病虫害遥感检测 | Pest and Disease Detection

(Fill in 2-3 paragraphs of Chinese introduction here: functionality, application scenarios, core algorithm.)

## Dependencies / 依赖

```bash
pip install 'numpy' 'rasterio' 'scipy'
```

## Usage / 使用方法

### Basic usage

```bash
python geoskill-pest-disease-detection.py --bbox 116.0 39.0 117.0 40.0 [other options]
```

### Example 1 (synthetic data, offline)

```bash
python geoskill-pest-disease-detection.py --bbox 116.0 39.0 117.0 40.0 --synthetic --output-dir ./out
```

### Examples 2-5

(Add at least 4 real-world usage examples.)

## Output / 输出

| File | Format | Description |
|---|---|---|
| `result.tif` | GeoTIFF | Main output |
| `output-manifest.json` | JSON | Run manifest |

## Data Source / 数据源 / Source

(Describe the data source: free satellite data / local input / synthetic.)

## Privacy / 隐私声明 / Privacy

- Runs offline by default; `--synthetic` mode requires no network at all.
- All processing is performed locally; user data is never uploaded.

## License / License

MIT

---

> 中文完整版：需要时再读 [references/SKILL.zh-CN.md](references/SKILL.zh-CN.md)，不要默认全量加载。

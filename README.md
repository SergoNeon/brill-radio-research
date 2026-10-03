# BRILL RADIO — Internet Radio Benchmarks 2026

Open, reproducible reference data for internet-radio planning: bitrate, listener bandwidth and estimated data transfer.

**Research hub:** https://radio.brill.city/research/  
**Interactive benchmark page:** https://radio.brill.city/internet-radio-benchmarks-2026/  
**Free calculators:** https://radio.brill.city/tools/

## Dataset

The repository contains the same public dataset published by BRILL RADIO in CSV and JSON formats.

- `data/internet-radio-benchmarks-2026.csv`
- `data/internet-radio-benchmarks-2026.json`

The table covers common bitrates from 64 to 320 kbps and listener counts from 1 to 1000.

## Method

The values are deterministic calculations, not claimed audience averages or proprietary industry measurements.

- stream Mbps = bitrate kbps × listeners ÷ 1000
- recommended Mbps = stream Mbps × 1.20
- MB per listener-hour = bitrate kbps × 3600 ÷ 8 ÷ 1000
- GB per listener-day = MB/hour × 24 ÷ 1000
- GB per listener / 30 days = GB/day × 30

Decimal network units are used for transfer calculations. Real-world usage can differ because of reconnects, protocol overhead, caching, silence, transcoding and listening duration.

## Cite BRILL RADIO

When referencing the dataset or formulas, please cite the research page:

> BRILL RADIO, “Internet Radio Benchmarks 2026”, https://radio.brill.city/internet-radio-benchmarks-2026/

## About BRILL RADIO

BRILL RADIO is a platform for creating and operating internet radio stations with AutoDJ, LIVE broadcasting, media management, scheduling and embeddable web players.

https://radio.brill.city/

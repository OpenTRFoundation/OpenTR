---
title: "Metodoloji"
linkTitle: "Metodoloji"
weight: 20
description: >
  OpenTR'nin çalışma metodolojisi ve süreçleri
---

### Metodoloji

OpenTR'nin [strateji belgesi](../strategy/) hedefleri belirlemekte ancak burada belirtilen metodoloji ise bu belirlenen hedeflere nasıl uygun çalışmalar yapılacağını belirtmektedir.

OpenTR, 6 aylık dönemler halinde çalışmaktadır. Her dönemde, öncelikle üzerinde çalışılacak konular belirlenmekte ve bu konular için veri toplanmakta ve analiz yapılmaktadır.

Veri ve analiz doğrultusunda, dönem için çalışmalar belirlenmekte ve sonrasında bu çalışmalar gerçekleştirilmektedir. Çalışmalar OpenTR'nin web sitesinde yayınlanmakta ve GitHub sayfasında açık kaynak olarak paylaşılmaktadır.

Her dönem sonunda aktiviteler bir rapor şeklinde paylaşılmaktadır.

Dönem hedefleri, çıktıları ve raporlarının bulunduğu dönem belgeleri için [Dönemler](../../terms/) sayfasına bakabilirsiniz.

```mermaid
  %%{
  init: {
  'theme': 'base',
  'themeVariables': {
  'primaryColor': '#FAFAFA',
  'primaryTextColor': '#333333',
  'primaryBorderColor': '#333333',
  'lineColor': '#666666',
  'secondaryColor': '#00FF00',
  'tertiaryColor': '#0000FF',
  'fontFamily': "Open Sans",
  'fontSize': '0.8em'
  }
  }
  }%%

  flowchart TD
  Start(fa:fa-car OpenTR oluşum başlangıcı) --> TermStart(fa:fa-play Dönem başlangıcı)
  TermStart --> Analysis(fa:fa-magnifying-glass-chart Anket ve ihtiyaç analizi)
  Analysis --> Strategy(fa:fa-bullseye OpenTR dönem çalışma stratejisi)
  Strategy --> Documents(fa:fa-book Rehber ve strateji belgeleri hazırlama)
  Documents --> Report(fa:fa-file-lines Rapor hazırlama)
  Report --> IterationEnd(fa:fa-flag-checkered Dönem sonu)
  IterationEnd --> TermStart
  ```

### Dönemler

```mermaid
    %%{init: { 'logLevel': 'debug', 'theme': 'default', 'themeVariables': {
    'cScale0': '#666',
    'cScale1': '#CCC'
    } } }%%
    timeline
    section 2023
        Mayıs : 2023 1. Dönem başı (oluşum başlangıcı)
        Haziran : 2023 1. Dönem sonu : Rapor yayını
        Temmuz : 2023 2. Dönem başı
        Aralık : 2023 2. Dönem sonu : Rapor yayını
    section 2024
        Ocak : 2024 1. Dönem Başı
        Haziran : 2024 1. Dönem sonu : Rapor yayını
        Temmuz : 2024 2. Dönem başı
        Aralık : 2024 2. Dönem sonu : Rapor yayını
```

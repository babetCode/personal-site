---
date: 2024-12-26T19:42:54-07:00
draft: true
title: Biomechanics
---

{{< tabs items="IMU analysis,YAML,TOML" >}}

  {{< tab >}}
  ```python
  for step in gait:
    track position
    detect heel-strike
    detect toe-off
    calculate stride length
  ```
  {{< /tab >}}

  {{< tab >}}
  ```toml
  for step in gait:
    track position
    detect heel-strike
    detect toe-off
    calculate stride length
  ```
  {{< /tab >}}

  ... add other tabs similarly

{{< /tabs >}}
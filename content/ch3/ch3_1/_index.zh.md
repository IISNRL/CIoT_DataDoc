+++
title = "時間序列處理"
weight = 10
description = "時間序列處理"
+++

{{ $title := .Title }}
{{ $url := printf "%s" .URL | absLangURL }}
{{ $body := print $title ", by " .Site.Title "\n" .Params.description "\n\n" $url "\n" }}
<div id="sharing">
  <a href="http://www.facebook.com/sharer.php?u={{ $url }}" class="facebook" aria-label="share on Facebook">
    {{ partial "svg/facebook.svg" (dict "size" "32px") }}
  </a>

  <a href="http://twitter.com/share?url={{ $url }}&text={{ $title }}&via={{with .Site.Social.twitter }}{{ . }}{{ end }}" class="twitter" aria-label="share on Twitter">
    {{ partial "svg/twitter.svg" (dict "size" "32px") }}
  </a>

  <a href="mailto:?subject=Check%20out%20{{ $title }}.&body={{ $body }}" class="twitter" aria-label="share on Email">
    {{ partial "svg/email.svg" (dict "size" "32px") }}
  </a>
</div>


## 時間序列處理

- 週期性分析
- Filtering (Gaussian Processes, Kalman Filter, Moving Average)
    - [Filtering Models — darts documentation](https://unit8co.github.io/darts/generated_api/darts.models.filtering.html)
- Change Point Detection
    - [Kats: a Generalizable Framework to Analyze Time Series Data in Python | by Khuyen Tran | Towards Data Science](https://towardsdatascience.com/kats-a-generalizable-framework-to-analyze-time-series-data-in-python-3c8d21efe057)
- Outlier Detection
    - [Kats: a Generalizable Framework to Analyze Time Series Data in Python | by Khuyen Tran | Towards Data Science](https://towardsdatascience.com/kats-a-generalizable-framework-to-analyze-time-series-data-in-python-3c8d21efe057)


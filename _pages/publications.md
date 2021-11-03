---
title: "Nishimoto Lab - Publications"
layout: gridlay
excerpt: "Publications"
sitemap: false
permalink: /publications/
---


## 出版物


（より詳細な業績リストは[Google Scholar](https://scholar.google.ch/citations?user=y1pLEGkAAAAJ)や[ResearchMap](https://researchmap.jp/shinjinishimoto/)などをご参照ください)

### ハイライト

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>

### 論文 （2020年以降）

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}

（より詳細なリストは[Google Scholar](https://scholar.google.ch/citations?user=y1pLEGkAAAAJ)や[ResearchMap](https://researchmap.jp/shinjinishimoto/)などをご参照ください)


<br />
### 特許

<em>西田 知史, 西本 伸志, 前田 直哉</em><br />脳活動予測装置、知覚認知内容推定システム、及び脳活動予測方法<br /> 日本国特許6928348 (2021)

<em>西本 伸志, 柏岡 秀樹</em><br />通过脑活动的解析推测感知语义内容的推测方法 <br /> 中国特許ZL201680019204.7 (2021)

<em>西本 伸志, 西田 知史, 柏冈 秀纪</em><br />素材评价方法以及素材评价装置<br /> 中国特許ZL201780002397.X (2020)

<em>Shinji Nishimoto, Satoshi Nishida, Hideki Kashioka</em><br />Material evaluation method and material evaluation device <br /> 欧州特許EP3406191B1 (2020)

<em>西本 伸志, 西田 知史, 柏岡 秀紀</em><br />素材評価方法、及び素材評価装置<br /> 日本国特許6687940 (2020)

<em>西本 伸志, 西田 知史, 柏岡 秀紀, 矢野 亮, 前田 直哉, 角 将高, 萩原 一平, 茨木 拓也</em><br />視聴素材評価方法、視聴素材評価システム、及びプログラム<br /> 日本国特許6662644 (2020)

<em>西本 伸志, 柏岡 秀紀</em><br />知覚意味内容推定装置および脳活動の解析による知覚意味内容の推定方法<br /> 日本国特許6618702 (2019)



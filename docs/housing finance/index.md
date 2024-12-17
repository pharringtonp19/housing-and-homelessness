---
title: Housing Finance
layout: default
permalink: /housing-finance/
nav_order: 4
---

### **Historical Overview**

In this class we discuss the history of housing finance in the United States. Relying largley on Chapter Three of Alex F. Schultz' ["Housing Policy in the United States"](https://www.taylorfrancis.com/books/mono/10.4324/9781003097501/housing-policy-united-states-alex-schwartz), we learn about the key policy changes which have lead to the current state of the housing market. [Slides](https://slides.com/pharringtonp19/history-of-housing-finance/fullscreen)

<details>
<summary>Related Articles</summary>
<ul>
  <li><a href="https://www.wsj.com/real-estate/boomer-millennials-housing-market-2a32a374?mod=article_inline&mod=article_inline">Boomers Buying Houses Had It Bad in the ’80s. Millennials Have It Worse.</a></li>
  <li><a href="https://www.wsj.com/finance/adjustable-rate-mortgage-interest-rates-86086ac5?mod=article_inline">Adjustable-Rate Mortgages Are No Longer a Bargain</a></li>
  <li><a href="https://www.wsj.com/economy/housing/mortgages-fed-interest-rate-cuts-7e5345b8">If the Fed Is Cutting Rates, Why Aren’t Mortgage Rates Falling?</a></li>
</ul>
</details>

<div style="padding: 10px; text-align: center; width: calc(33.33% - 1%); margin: 0 auto; box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);">
  <!-- Title of the PNG -->
  
  <!-- PNG Image -->
  <a href="https://www.taylorfrancis.com/books/mono/10.4324/9781003097501/housing-policy-united-states-alex-schwartz" style="display: block;">
    <img src="./../assets/images/hp.png" alt="Alt text" style="width: 100%; height: auto;" />
  </a>
</div>

### **Government Sponsored Enterprises**

In this class we examine the role the Government Sponsored Enterprises had on the development of housing.

<div style="padding: 10px; text-align: center; width: calc(33.33% - 1%); margin: 0 auto; box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);">
  <!-- Title of the PNG -->
  
  <!-- PNG Image -->
  <a href="https://openroadmedia.com/ebook/the-fateful-history-of-fannie-mae/9781614236993" style="display: block;">
    <img src="./../assets/images/hagerty.png" alt="Alt text" style="width: 100%; height: auto;" />
  </a>
</div>



<style>
/* Tabs styling */
.article-tabs {
  display: flex;
  justify-content: space-between;
  border-bottom: 2px solid #ccc;
  margin-bottom: 20px;
  font-family: Arial, sans-serif;
}

.article-tabs button {
  flex: 1;
  background-color: transparent;
  border: none;
  font-size: 16px;
  padding: 10px 20px;
  cursor: pointer;
  transition: background-color 0.3s ease;
  border-bottom: 2px solid transparent;
}

.article-tabs button:hover {
  background-color: #f0f0f0;
}

.article-tabs button.active {
  border-bottom: 2px solid black;
  font-weight: bold;
}

.tab-content {
  display: none;
  margin-top: 20px;
}

.tab-content.active {
  display: block;
}
</style>

### **Insurance**
In this class, we read through a recent reporting by Bloomberg on the recent developments in the Insurance Market. The report covers the changing relationship between rating agencies, predictive analytic companies, insurance companies, and insurance commisioners. 

<details>
<summary>Related Articles</summary>
<ul>
  <li><a href="https://www.bloomberg.com/features/2024-catastrophe-bonds-fermat/">How a Physics Whiz Made a Fortune Betting on Nature’s Catastrophes</a></li>
  <li><a href="  https://www.bloomberg.com/news/articles/2024-02-04/hedge-funds-record-profits-entice-investors-to-catastrophe-bonds?sref=GBEdnt3o">Hedge Funds’ Mega Returns Set Off Demand Spiral for Catastrophe Bonds</a></li>
</ul>
</details>

<div class="article-tabs">
  <button class="tab-link active" data-article-id="article1">Part 1</button>
  <button class="tab-link" data-article-id="article2">Part 2</button>
  <button class="tab-link" data-article-id="article3">Part 3</button>
  <button class="tab-link" data-article-id="article4">Part 4</button>
  <button class="tab-link" data-article-id="article5">Part 5</button>
</div>

<div id="article1" class="tab-content active">
  <p>
    <strong>Part 1:</strong> <a href="https://www.bloomberg.com/features/2024-home-insurance-real-estate-crisis/" target="_blank">A Hidden Crisis in US Housing</a>
  </p>
  <p>FILL IN</p>
</div>

<div id="article2" class="tab-content">
  <p>
    <strong>Part 2:</strong> <a href="https://www.bloomberg.com/graphics/2024-flood-fire-climate-risk-analytics/" target="_blank">The Risky Business of Predicting Where Climate Disaster Will Hit</a>
  </p>
  <p>FILL IN</p>
</div>

<div id="article3" class="tab-content">
  <p>
    <strong>Part 3:</strong> <a href="https://www.bloomberg.com/features/2024-jamaica-hurricane-catastrophe-bonds/" target="_blank">The Harsh Reality of ‘Hurricane Insurance’</a>
  </p>
  <p>This article discusses the insurance market that developing countries face.</p>
</div>

<div id="article4" class="tab-content">
  <p>
    <strong>Part 4:</strong> <a href="https://www.bloomberg.com/features/2024-uk-home-flood-re-insurance/" target="_blank">The UK Is Losing the Race Against Devastating Floods</a>
  </p>
  <p>FILL IN</p>
</div>

<div id="article5" class="tab-content">
  <p>
    <strong>Part 5:</strong> <a href="https://www.bloomberg.com/graphics/2024-home-insurance-risky-policy/" target="_blank">The Quiet Rise of Lightly Regulated Home Insurance</a>
  </p>
  <p>The article describes the recent growth in non-admitted insurance policies and highlights the potential issues possed by these companies moving forward (thinly capitalized, potentially volitile prices, lack of a guaranty fund) </p>
</div>

{% raw %}
<script>
document.addEventListener("DOMContentLoaded", function () {
  function openArticle(event, articleId) {
    const tabContents = document.querySelectorAll(".tab-content");
    tabContents.forEach((content) => content.classList.remove("active"));

    const tabs = document.querySelectorAll(".article-tabs button");
    tabs.forEach((tab) => tab.classList.remove("active"));

    document.getElementById(articleId).classList.add("active");
    event.currentTarget.classList.add("active");
  }

  const buttons = document.querySelectorAll(".article-tabs button");
  buttons.forEach((button) => {
    button.addEventListener("click", function (event) {
      const articleId = this.getAttribute("data-article-id");
      openArticle(event, articleId);
    });
  });
});
</script>
{% endraw %}

### **Low-Income Housing**
- tax credits 
- soft loans 
- city and state funds 
- developer fees 
- HOPE VI grants
- Tax increment financing

<!-- ### **Technical Overview**

In this class, we cover some of the more technical aspects related to housing finance. In particular we introduce the notion of Presevent Values and discuss how mortages are priced. [Slides](https://slides.com/pharringtonp19/real-estate-finance/fullscreen)


<div style="padding: 10px; text-align: center; width: calc(33.33% - 1%); margin: 0 auto;">
  <!-- Title of the PNG -->
  
  <!-- PNG Image -->
  <!-- <a href="https://www.mheducation.com/highered/product/real-estate-finance-investments-brueggeman-fisher/M9781260734300.html" style="display: block;">
    <img src="./../assets/images/ref.png" alt="Alt text" style="width: 100%; height: auto;" />
  </a>
</div> --> 

<!-- 
Writings:[Blackstone](https://www.wsj.com/real-estate/blackstone-making-10-billion-multifamily-purchase-going-on-the-real-estate-offensive-f3126928?mod=article_inline), [Making It Pencil](https://ternercenter.berkeley.edu/wp-content/uploads/2023/12/Development-Math-2023.pdf)


### **Banking**
- SRT

Writings:
[Regional Banks Want to Slim Down. Hedge Funds Smell a Bargain](https://www.wsj.com/finance/banking/regional-banks-want-to-slim-down-hedge-funds-smell-a-bargain-f4e1d0fe?mod=hp_lead_pos6)
[Nonbanks Are Growing but Their Growth Is Heavily Supported by Banks](https://libertystreeteconomics.newyorkfed.org/2024/06/nonbanks-are-growing-but-their-growth-is-heavily-supported-by-banks/)

### **Multi-family**


Writings:
[Blackstone](https://www.wsj.com/real-estate/blackstone-making-10-billion-multifamily-purchase-going-on-the-real-estate-offensive-f3126928?mod=article_inline), [KKR](https://www.wsj.com/real-estate/kkr-makes-its-biggest-foray-into-apartments-betting-on-rising-rents-94213297?mod=hp_major_pos1#cxrecs_s) -->
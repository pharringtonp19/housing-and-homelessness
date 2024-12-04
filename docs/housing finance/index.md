---
title: Housing Finance
layout: default
permalink: /housing-finance/
nav_order: 4
---

### **Historical Overview**

In this class we discuss the history of housing finance in the United States. Relying largley on Chapter Three of Alex F. Schultz' ["Housing Policy in the United States"](https://www.taylorfrancis.com/books/mono/10.4324/9781003097501/housing-policy-united-states-alex-schwartz), we learn about the key policy changes which have lead to the current state of the housing market. [Slides](https://slides.com/pharringtonp19/history-of-housing-finance/fullscreen)


<div style="padding: 10px; text-align: center; width: calc(33.33% - 1%); margin: 0 auto;">
  <!-- Title of the PNG -->
  
  <!-- PNG Image -->
  <a href="https://www.taylorfrancis.com/books/mono/10.4324/9781003097501/housing-policy-united-states-alex-schwartz" style="display: block;">
    <img src="./../assets/images/hp.png" alt="Alt text" style="width: 100%; height: auto;" />
  </a>
</div>

<details>
<summary>Articles</summary>
<ul>
  <li><a href="https://www.wsj.com/real-estate/boomer-millennials-housing-market-2a32a374?mod=article_inline&mod=article_inline">Boomers Buying Houses Had It Bad in the ’80s. Millennials Have It Worse.</a></li>
  <li><a href="https://www.wsj.com/finance/adjustable-rate-mortgage-interest-rates-86086ac5?mod=article_inline">Adjustable-Rate Mortgages Are No Longer a Bargain</a></li>
  <li><a href="https://www.wsj.com/economy/housing/mortgages-fed-interest-rate-cuts-7e5345b8">If the Fed Is Cutting Rates, Why Aren’t Mortgage Rates Falling?</a></li>
</ul>
</details>


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

<script>
document.addEventListener("DOMContentLoaded", function () {
  // Function to handle tab switching
  function openArticle(event, articleId) {
    // Hide all tab contents
    const tabContents = document.querySelectorAll(".tab-content");
    tabContents.forEach((content) => {
      content.classList.remove("active");
    });

    // Remove active class from all tabs
    const tabs = document.querySelectorAll(".article-tabs button");
    tabs.forEach((tab) => {
      tab.classList.remove("active");
    });

    // Show the selected tab content and mark the tab as active
    document.getElementById(articleId).classList.add("active");
    event.currentTarget.classList.add("active");
  }

  // Attach click event handlers to buttons
  const buttons = document.querySelectorAll(".article-tabs button");
  buttons.forEach((button) => {
    button.addEventListener("click", function (event) {
      const articleId = this.getAttribute("data-article-id");
      openArticle(event, articleId);
    });
  });
});
</script>

### **Insurance**

In this class, we cover some of the more technical aspects related to housing finance. In particular, we introduce the notion of Present Values and discuss how mortgages are priced.

<div class="article-tabs">
  <button class="tab-link active" data-article-id="article1">Article 1</button>
  <button class="tab-link" data-article-id="article2">Article 2</button>
  <button class="tab-link" data-article-id="article3">Article 3</button>
  <button class="tab-link" data-article-id="article4">Article 4</button>
  <button class="tab-link" data-article-id="article5">Article 5</button>
</div>

<div id="article1" class="tab-content active">
  <p>
    <strong>Article 1:</strong> <a href="https://www.wsj.com/real-estate/boomer-millennials-housing-market-2a32a374?mod=article_inline" target="_blank">Boomers Buying Houses Had It Bad in the ’80s. Millennials Have It Worse.</a>
  </p>
  <p>This article explores how Millennials face even greater housing challenges compared to Boomers in the 1980s.</p>
</div>

<div id="article2" class="tab-content">
  <p>
    <strong>Article 2:</strong> <a href="https://www.wsj.com/finance/adjustable-rate-mortgage-interest-rates-86086ac5?mod=article_inline" target="_blank">Adjustable-Rate Mortgages Are No Longer a Bargain</a>
  </p>
  <p>This article discusses why adjustable-rate mortgages (ARMs) have become less attractive in the current financial climate.</p>
</div>

<div id="article3" class="tab-content">
  <p>
    <strong>Article 3:</strong> <a href="https://www.wsj.com/economy/housing/mortgages-fed-interest-rate-cuts-7e5345b8" target="_blank">If the Fed Is Cutting Rates, Why Aren’t Mortgage Rates Falling?</a>
  </p>
  <p>This article explores the disconnect between Federal Reserve rate cuts and mortgage interest rates.</p>
</div>

<div id="article4" class="tab-content">
  <p>
    <strong>Article 4:</strong> <a href="https://example.com/article4" target="_blank">Article 4 Title</a>
  </p>
  <p>This article discusses how housing policies impact affordability and the role of insurance in financial planning.</p>
</div>

<div id="article5" class="tab-content">
  <p>
    <strong>Article 5:</strong> <a href="https://example.com/article5" target="_blank">Article 5 Title</a>
  </p>
  <p>This article delves into the role of insurance pricing in shaping housing markets and its impact on homeownership rates.</p>
</div>


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
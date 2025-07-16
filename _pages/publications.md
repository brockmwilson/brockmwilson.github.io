---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

<style>
img {
    max-width: 80%;
    width: auto;
    height: auto;
    vertical-align: middle;
    border: 0;
    display:flex;
    align-items: center;
}

h1 {
  font-size: 2.563em
}

</style>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% -->

<hr style="border: none; height: 2px; background-color: #D3D3D3;">

<p style="font-size: 1.25em; text-decoration: none; font-weight: bold; margin-bottom: -15px"> 
  <a href="http://brockmwilson.github.io/files/Wilson-RetirementRetentionRecruitment.pdf" style="text-decoration: none; color: navy;">
    Retirement, Retention, Recruitment: Evidence from a Federal Pension Policy
  </a>
</p>

<p style="font-size: 6; font-style: italic;"> Revise and Resubmit, Labour Economics</p>

<!-- Dropdown for the Abstract and Image -->
<details>
  <summary style="font-size: 1em; font-weight: normal; cursor: pointer; 
          display: inline-block; 
          border: 0px; border-radius: 15px; 
          padding: 5px 10px; background-color: #f0f0f0; 
          color: black; transition: all 0.3s ease;">
    Click to view abstract
  </summary>

  <!-- Box around abstract when expanded -->
  <div style="border: 2px solid #ccc; border-radius: 10px; padding: 15px; margin-top: 10px;">
    <p style="font-size: 1em; margin-top: 10px;"> 
      I exploit a policy change for U.S. federal workers’ pension benefits to estimate the effect of pension generosity on worker retirement, retention, and recruitment. The policy increased pensions by 16-25%. I find there is a 30.3% decrease in job quits for permanent workers. However, there is little evidence that pension generosity has an effect on new hires. This suggests salience may play a role in how workers value pensions. Additionally, I find a large heterogeneous labor supply response to pension generosity. Altogether, this shows that pension generosity is effective in retaining workers and may have important implications for workforce planning.
    </p>

  <img src="images/pension-labor-outcomes2.jpg" alt="Pension Labor Outcomes" style="max-width: 100%; height: auto; margin-top: 10px;">
  </div>
</details>

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% -->

<hr style="border: none; height: 2px; background-color: #D3D3D3;">

<p style="font-size: 1.25em; text-decoration: none; font-weight: bold; margin-bottom: 0px">
  <a href="http://brockmwilson.github.io/files/BKPW_20250524.pdf" style="text-decoration: none; color: navy;">
    Rehabilitating Delinquent Digital Borrowers<br>
    (with Alfredo Burlando, Silvia Prina, and Michael Kuhn)
  </a>
</p>

<div style="height: 1.3em;"></div>

<!-- Dropdown for the Abstract and Image -->
<details>
  <summary style="font-size: 1em; font-weight: normal; cursor: pointer; 
          display: inline-block; 
          border: 0px; border-radius: 15px; 
          padding: 5px 10px; background-color: #f0f0f0; 
          color: black; transition: all 0.3s ease;">
    Click to view abstract
  </summary>

  <!-- Box around abstract when expanded -->
  <div style="border: 2px solid #ccc; border-radius: 10px; padding: 15px; margin-top: 10px;">
    <p style="font-size: 1em; margin-top: 10px;"> 
      We partner with a digital lender in Africa to examine how offering delinquent digital borrowers a strategy to repay their overdue loan (payment plan) and the possibility of regaining access to future credit (renewed eligibility) affects repayment behavior and welfare. The payment plan significantly increases repayment, settlement, and re-borrowing, while eligibility alone has no effect. Although the payment plan has no impact on welfare, the eligibility treatment raises stress and perceived financial insecurity. Our analysis suggests that impatience, time inconsistency, and liquidity constraints could play a role in explaining our results.
    </p>

  <img src="images/repayment-behavior.jpg" alt="Repayment behavior" style="max-width: 100%; height: auto; margin-top: 10px;">
  </div>
</details>

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% -->

<!-- <hr style="border: none; height: 2px; background-color: #D3D3D3;">

<p style="font-size: 1.25em; text-decoration: none; font-weight: bold; margin-bottom: -15px"> 
Rehabilitating Delinquent Digital Borrowers<br>
(with Alfredo Burlando, Silvia Prina, and Michael Kuhn)
</p>

<p style="font-size: 6; font-style: italic;"> Under Review</p> -->

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% -->


<hr style="border: none; height: 2px; background-color: #D3D3D3;">

<p style="font-size: 1.25em; text-decoration: none; font-weight: bold; margin-bottom: 0px">
  <a href="http://brockmwilson.github.io/files/Waddell-Wilson_Disability-Mandates_20250714.pdf" style="text-decoration: none; color: navy;">
    How did federal agencies respond to disability quotas?<br>
    (with Glen Waddell)
  </a>
</p>

<div style="height: 1.3em;"></div>

<!-- Dropdown for the Abstract and Image -->
<details>
  <summary style="font-size: 1em; font-weight: normal; cursor: pointer; 
          display: inline-block; 
          border: 0px; border-radius: 15px; 
          padding: 5px 10px; background-color: #f0f0f0; 
          color: black; transition: all 0.3s ease;">
    Click to view abstract
  </summary>

  <!-- Box around abstract when expanded -->
  <div style="border: 2px solid #ccc; border-radius: 10px; padding: 15px; margin-top: 10px;">
    <p style="font-size: 1em; margin-top: 10px;"> 
We study the rollout of two disability related policies that intended to increase representation in the U.S. federal workforce---an executive order to increase employment across all agencies, and a second that mandated quotas be met at each agency. The first of these is followed by a large increase in disability employment. At lower-pay positions, increases in representation are largely through hiring, while at higher-pay positions increases are through updating disability statuses. However, with the quota introduction we find evidence that agencies target the minimum threshold—this lead to declines in disability representation at agencies that were already in compliance.
    </p>

  <img src="images/disability-mandates.png" alt="" style="max-width: 100%; height: auto; margin-top: 10px;">
  </div>
</details>

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% -->

<hr style="border: none; height: 2px; background-color: #D3D3D3;">

<p style="font-size: 1.25em; text-decoration: none; font-weight: bold; margin-bottom: 150px;"> Selection Into Motorcycling: What Can Licensing Laws Tell Us?<br> 
(with Glen Waddell) </p>

<hr style="border: none; height: 2px; background-color: black;">

<h1>Media</h1>

<hr style="border: none; height: 2px; background-color: #D3D3D3;">

<h2>News</h2>

<a href = "https://www.adn.com/business-economy/2024/12/25/alaskans-backed-a-measure-to-raise-the-minimum-wage-and-establish-sick-leave-now-employers-are-trying-to-make-it-work/">Alaskans backed a measure to raise the minimum wage and establish sick leave. Now employers are trying to make it work.</a>

<a href = "https://alaskapublic.org/news/politics/2025-03-13/disparaging-dismissals-aside-alaskas-fired-federal-workers-file-for-unemployment">Disparaging dismissals aside, Alaska’s fired federal workers file for unemployment</a>

<a href = "https://www.adn.com/politics/2025/03/13/138-fired-federal-employees-have-applied-for-unemployment-insurance-in-alaska/">At least 138 fired federal employees have applied for unemployment insurance in Alaska</a>

<hr style="border: none; height: 2px; background-color: #D3D3D3;">

<h2>Expert Testimony</h2>

<a href = "https://www.akleg.gov/basis/Meeting/Detail?Meeting=HJUD%202025-03-12%2013:00:00#tab4_4e">Economic Contributions of Federal Civilian Workers in Alaska</a>

<hr style="border: none; height: 2px; background-color: #D3D3D3;">

<h2>Podcasts</h2>

<a href = "https://open.spotify.com/episode/324MZgkEknAlgD32U3IwCF?si=a34879b3625d4e3b">Brock Wilson, PhD: Labor Economist at UAA's Institute of Social & Economic Research (ISER)</a>




---
layout: page
title: home
permalink: /
---

<!-- Two-column layout -->
<table style="width:100%; max-width:600px; border-collapse:collapse; border:none; margin:2rem auto;">
  <tr>
    <!-- Left column: photo -->
    <td style="width:120px; vertical-align:top; border:none; padding:0;">
      <img src="/assets/images/SIX_34D84334-6FBF-4529-BBE9-7557ADF4174D.JPG" 
           alt="My photo" 
           style="width:120px; border-radius:10px; display:block;" />
    </td>
    <!-- Right column: text -->
    <td style="padding-left:20px; vertical-align:top; border:none;">
      <!-- Page title hidden manually -->
      <h1 style="display:none;">Home</h1>
      <h1>hi, i'm Caroline!</h1>
      <p>website in progress</p>
    </td>
  </tr>
</table>

<!-- Inline styles to hide footer and make layout responsive -->
<style>

  /* Hide homepage title */
  body.page h1.post-title {
    display: none !important;
  }
  
  /* Hide Minima footer */
  .site-footer { display: none !important; }

  /* Stack columns on small screens */
  @media (max-width: 600px) {
    table, tr, td {
      display: block !important;
      width: 100% !important;
      text-align: center;
      padding-left: 0 !important;
    }

    img {
      width: 80px !important;
      margin: 0 auto 1rem auto !important;
    }
  }
</style>

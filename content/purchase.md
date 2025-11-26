---
title: "Purchase"
description: "Get the Cashflow & Networth Analysis Workbook"
featured_image: "/images/fi-summary-dashboard.png"
menu:
  main:
    name: "Purchase"
    weight: 3
---

{{< rawhtml >}}
<style>
.purchase-container {
  max-width: 1000px;
  margin: 0 auto;
  padding: 2rem 1rem;
}
.purchase-options {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}
.purchase-card {
  border: 2px solid #e2e8f0;
  border-radius: 12px;
  padding: 2rem;
  background: white;
  position: relative;
}
.purchase-card.featured {
  border-color: #48bb78;
  box-shadow: 0 4px 20px rgba(72, 187, 120, 0.2);
}
.purchase-card.featured::before {
  content: "RECOMMENDED";
  position: absolute;
  top: -12px;
  left: 50%;
  transform: translateX(-50%);
  background: #48bb78;
  color: white;
  padding: 0.25rem 1rem;
  border-radius: 20px;
  font-size: 0.75rem;
  font-weight: 600;
}
.card-header {
  text-align: center;
  padding-bottom: 1.5rem;
  border-bottom: 1px solid #e2e8f0;
  margin-bottom: 1.5rem;
}
.card-title {
  font-size: 1.5rem;
  color: #1a365d;
  margin-bottom: 0.5rem;
}
.card-price {
  font-size: 2.5rem;
  font-weight: 700;
  color: #2d3748;
}
.card-price span {
  font-size: 1rem;
  font-weight: 400;
  color: #718096;
}
.card-description {
  color: #4a5568;
  margin-bottom: 1.5rem;
  line-height: 1.6;
}
.features-list {
  list-style: none;
  padding: 0;
  margin: 0 0 2rem 0;
}
.features-list li {
  padding: 0.5rem 0;
  display: flex;
  align-items: flex-start;
  gap: 0.5rem;
}
.features-list li::before {
  content: "✓";
  color: #48bb78;
  font-weight: bold;
  flex-shrink: 0;
}
.purchase-button {
  display: block;
  width: 100%;
  padding: 1rem;
  text-align: center;
  border-radius: 8px;
  font-size: 1.1rem;
  font-weight: 600;
  text-decoration: none;
  transition: all 0.3s ease;
}
.purchase-button.primary {
  background: #48bb78;
  color: white;
}
.purchase-button.primary:hover {
  background: #38a169;
  color: white;
}
.purchase-button.secondary {
  background: #e2e8f0;
  color: #2d3748;
}
.purchase-button.secondary:hover {
  background: #cbd5e0;
}
.guarantee-section {
  text-align: center;
  margin-top: 3rem;
  padding: 2rem;
  background: #f7fafc;
  border-radius: 12px;
}
.guarantee-section h3 {
  color: #1a365d;
  margin-bottom: 1rem;
}
.faq-section {
  margin-top: 3rem;
}
.faq-section h2 {
  text-align: center;
  color: #1a365d;
  margin-bottom: 2rem;
}
.faq-item {
  border-bottom: 1px solid #e2e8f0;
  padding: 1rem 0;
}
.faq-item h4 {
  color: #2d3748;
  margin-bottom: 0.5rem;
}
.faq-item p {
  color: #4a5568;
  margin: 0;
}
</style>

<div class="purchase-container">
  <h2 style="text-align: center; color: #1a365d;">Choose Your Option</h2>

  <div class="purchase-options">
    <div class="purchase-card">
      <div class="card-header">
        <h3 class="card-title">Free Trial</h3>
        <p class="card-price">$0 <span>forever</span></p>
      </div>
      <p class="card-description">Try an older version of the workbook to see if it meets your needs before purchasing.</p>
      <ul class="features-list">
        <li>Full workbook functionality</li>
        <li>All dashboards included</li>
        <li>Older version (v1.3)</li>
        <li>No support included</li>
        <li>No updates</li>
      </ul>
      <a href="https://jackmansean64.github.io/blog/files/CashflowNetworthAnalysisTemplate1.3.xlsx" class="purchase-button secondary">Download Trial</a>
    </div>

    <div class="purchase-card featured">
      <div class="card-header">
        <h3 class="card-title">Full Version</h3>
        <p class="card-price">$XX <span>one-time</span></p>
      </div>
      <p class="card-description">Get the latest version with all features, free updates, and dedicated support.</p>
      <ul class="features-list">
        <li>Latest version of the workbook</li>
        <li>All dashboards and features</li>
        <li>Free lifetime updates</li>
        <li>Email support</li>
        <li>Tiller Data Copy Tool included</li>
      </ul>
      <a href="#STRIPE_PAYMENT_LINK" class="purchase-button primary">Buy Now</a>
    </div>
  </div>

  <div class="guarantee-section">
    <h3>What's Included With Your Purchase</h3>
    <p>When you purchase the Cashflow & Networth Analysis Workbook, you receive:</p>
    <ul style="text-align: left; max-width: 500px; margin: 1rem auto;">
      <li><strong>The Complete Workbook</strong> - Latest version with all dashboards and features</li>
      <li><strong>Free Updates</strong> - All future updates and improvements at no additional cost</li>
      <li><strong>Email Support</strong> - Direct support for setup and troubleshooting questions</li>
      <li><strong>Tiller Data Copy Tool</strong> - Utility to help migrate your existing Tiller data</li>
    </ul>
  </div>

  <div class="faq-section">
    <h2>Frequently Asked Questions</h2>

    <div class="faq-item">
      <h4>Do I need a Tiller subscription to use this workbook?</h4>
      <p>No, the workbook works standalone. However, if you want automatic transaction imports, you'll need a Tiller subscription. You can also manually enter or import your data.</p>
    </div>

    <div class="faq-item">
      <h4>What version of Excel do I need?</h4>
      <p>The workbook is designed for Microsoft Excel (desktop version). It uses features like Power Pivot and the Data Model, so Excel 2016 or later is recommended.</p>
    </div>

    <div class="faq-item">
      <h4>Can I customize the workbook?</h4>
      <p>Absolutely! The workbook is built without macros or VBA, making it fully transparent and customizable. You can modify categories, add calculations, or create new visualizations.</p>
    </div>

    <div class="faq-item">
      <h4>How do I get updates?</h4>
      <p>When updates are released, you'll receive an email with download instructions. Updates are free for all purchasers.</p>
    </div>

    <div class="faq-item">
      <h4>What if I have questions or need help?</h4>
      <p>Contact me directly via email for support. I'm happy to help with setup, troubleshooting, or customization questions.</p>
    </div>
  </div>
</div>
{{< /rawhtml >}}

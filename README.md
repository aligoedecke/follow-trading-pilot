NinjaTrader Collective2 Follow Trading Pilot.html
<!DOCTYPE html>
<!-- saved from url=(0079)file:///C:/Users/AliGoedecke/Downloads/follow-trading-leader-guide-print_1.html -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Follow Trading - Strategy Leader Guide</title>
<link href="./NinjaTrader Collective2 Follow Trading Pilot_files/css2" rel="stylesheet">
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    font-family: 'Montserrat', 'Segoe UI', sans-serif;
    background: #ffffff;
    color: #1a1a1a;
    line-height: 1.6;
    -webkit-font-smoothing: antialiased;
  }

  .page {
    max-width: 680px;
    margin: 0 auto;
    padding: 36px 32px 48px;
  }

  .eyebrow {
    font-size: 9px;
    font-weight: 800;
    letter-spacing: 0.14em;
    text-transform: uppercase;
    color: #FF4200;
    margin-bottom: 6px;
  }

  h1 {
    font-size: 28px;
    font-weight: 900;
    letter-spacing: -0.02em;
    line-height: 1.1;
    margin-bottom: 8px;
    color: #1a1a1a;
  }

  .subtitle {
    font-size: 13.5px;
    color: #555;
    line-height: 1.55;
    margin-bottom: 24px;
  }

  .divider {
    height: 1px;
    background: #e0e0e0;
    margin: 18px 0;
  }

  h2 {
    font-size: 16px;
    font-weight: 800;
    letter-spacing: -0.01em;
    margin-bottom: 8px;
    color: #1a1a1a;
  }

  p {
    font-size: 12.5px;
    color: #444;
    line-height: 1.6;
    margin-bottom: 10px;
  }

  p:last-child { margin-bottom: 0; }

  .card {
    background: #f7f7f7;
    border: 1px solid #e0e0e0;
    border-left: 3px solid #FF4200;
    border-radius: 8px;
    padding: 12px 14px;
    margin-bottom: 10px;
  }

  .card-label {
    font-size: 9px;
    font-weight: 800;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: #FF4200;
    margin-bottom: 3px;
  }

  .card p {
    margin-bottom: 0;
    font-size: 12px;
    color: #444;
  }

  .steps {
    display: flex;
    flex-direction: column;
    gap: 7px;
    margin-bottom: 6px;
  }

  .step {
    background: #f7f7f7;
    border: 1px solid #e0e0e0;
    border-radius: 8px;
    padding: 10px 14px;
    display: flex;
    gap: 12px;
    align-items: flex-start;
  }

  .step-num {
    flex-shrink: 0;
    width: 24px;
    height: 24px;
    border-radius: 50%;
    background: rgba(255,66,0,0.08);
    border: 1px solid rgba(255,66,0,0.25);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 11px;
    font-weight: 800;
    color: #FF4200;
    margin-top: 1px;
  }

  .step-content h3 {
    font-size: 12.5px;
    font-weight: 700;
    margin-bottom: 2px;
    color: #1a1a1a;
  }

  .step-content p {
    font-size: 11.5px;
    margin-bottom: 0;
    color: #555;
  }

  .faq-item {
    margin-bottom: 12px;
  }

  .faq-item:last-child { margin-bottom: 0; }

  .faq-q {
    font-size: 12.5px;
    font-weight: 700;
    color: #1a1a1a;
    margin-bottom: 2px;
  }

  .faq-a {
    font-size: 12px;
    color: #555;
    line-height: 1.5;
  }

  .video-list {
    display: flex;
    flex-direction: column;
    gap: 6px;
    margin-top: 4px;
  }

  .video-link {
    background: #f7f7f7;
    border: 1px solid #e0e0e0;
    border-radius: 6px;
    padding: 10px 14px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    text-decoration: none;
    color: inherit;
  }

  .video-info {
    display: flex;
    flex-direction: column;
    gap: 1px;
  }

  .video-title {
    font-size: 12px;
    font-weight: 600;
    color: #1a1a1a;
  }

  .video-desc {
    font-size: 10.5px;
    color: #888;
  }

  .video-duration {
    font-size: 10px;
    font-weight: 700;
    color: #999;
    flex-shrink: 0;
    margin-left: 16px;
  }

  .cta-section {
    background: #f7f7f7;
    border: 1px solid #e0e0e0;
    border-radius: 10px;
    padding: 20px 20px;
    text-align: center;
    margin-top: 6px;
  }

  .cta-section h2 {
    margin-bottom: 4px;
  }

  .cta-section p {
    margin-bottom: 12px;
    font-size: 12px;
    color: #555;
  }

  .cta-btn {
    display: inline-block;
    background: #FF4200;
    color: white;
    border: none;
    padding: 10px 22px;
    border-radius: 4px;
    font-size: 12.5px;
    font-weight: 800;
    letter-spacing: -0.01em;
    text-decoration: none;
    cursor: pointer;
    font-family: 'Montserrat', 'Segoe UI', sans-serif;
  }

  .cta-note {
    font-size: 10.5px;
    color: #999;
    margin-top: 10px;
    margin-bottom: 0;
  }

  .footer {
    margin-top: 28px;
    padding-top: 16px;
    border-top: 1px solid #e0e0e0;
    font-size: 9.5px;
    color: #999;
    line-height: 1.5;
  }

  .footer a {
    color: #999;
    text-decoration: none;
  }

  .logo-text {
    font-size: 18px;
    font-weight: 900;
    letter-spacing: 0.02em;
    color: #FF4200;
    margin-bottom: 12px;
    font-family: 'Montserrat', 'Segoe UI', sans-serif;
  }

  @media (max-width: 520px) {
    .page { padding: 32px 20px 48px; }
    h1 { font-size: 26px; }
    .step { flex-direction: column; gap: 8px; }
    .video-link { flex-direction: column; align-items: flex-start; gap: 4px; }
    .video-duration { margin-left: 0; }
  }

  @media print {
    @page {
      margin: 0.5in;
      size: letter;
    }
    .page { padding: 0; max-width: 100%; }
    .card { break-inside: avoid; page-break-inside: avoid; }
    .step { break-inside: avoid; page-break-inside: avoid; }
    .video-link { break-inside: avoid; page-break-inside: avoid; }
    .faq-item { break-inside: avoid; page-break-inside: avoid; }
    .cta-section { break-inside: avoid; page-break-inside: avoid; }
    .steps { break-inside: avoid; page-break-inside: avoid; }
    h2 { break-after: avoid; page-break-after: avoid; }
    .divider { break-after: avoid; page-break-after: avoid; }
    .video-list { break-inside: avoid; page-break-inside: avoid; }
    .cta-btn { background: #FF4200 !important; color: white !important; -webkit-print-color-adjust: exact; print-color-adjust: exact; }
    .step-num { background: rgba(255,66,0,0.08) !important; -webkit-print-color-adjust: exact; print-color-adjust: exact; }
    .card { background: #f7f7f7 !important; -webkit-print-color-adjust: exact; print-color-adjust: exact; }
    .step { background: #f7f7f7 !important; -webkit-print-color-adjust: exact; print-color-adjust: exact; }
    .video-link { background: #f7f7f7 !important; -webkit-print-color-adjust: exact; print-color-adjust: exact; }
    .cta-section { background: #f7f7f7 !important; -webkit-print-color-adjust: exact; print-color-adjust: exact; }
  }
</style>
</head>
<body>
<div class="page">

  <div class="logo-text">NINJATRADER</div>
  <div class="eyebrow">Follow Trading Pilot</div>
  <h1>Strategy Leader Guide</h1>
  <p class="subtitle">You've been invited to publish your trading strategy on NinjaTrader's Follow Trading platform. Here's everything you need to know.</p>

  <div class="divider"></div>

  <h2>How It Works</h2>
  <p>You keep trading in your NinjaTrader brokerage account exactly as you do today. Your trades are automatically replicated to subscribers who choose to follow your strategy. Subscribers pay a monthly fee to follow you, and you earn a share of that subscription revenue.</p>

  <div class="card">
    <div class="card-label">Key Point</div>
    <p>This is a subscription model. Your earnings come from the monthly fees your followers pay to follow your strategy.</p>
  </div>

  <div class="divider"></div>

  <h2>What You Earn</h2>
  <p>Subscribers pay a monthly subscription to follow your strategy. You earn a share of that subscription revenue, paid out monthly. The subscription price for your strategy is set during the setup process.</p>
  <p>Billing, payments, and payouts are handled by Collective2, our technology partner that powers the Follow Trading infrastructure. They'll walk you through the exact economics when you set up your strategy.</p>

  <div class="divider"></div>

  <h2>What Changes for You</h2>

  <div class="card">
    <div class="card-label">Nothing changes about your trading</div>
    <p>You trade in your own NinjaTrader brokerage account, with the same instruments, margins, and platform you already use. Your account size and positions are never visible to followers.</p>
  </div>

  <div class="card">
    <div class="card-label">What's new</div>
    <p>Your trades are connected to a strategy page where subscribers can see your track record and choose to follow. You set your subscription price and strategy description. Followers' trades are executed automatically based on your signals.</p>
  </div>

  <div class="divider"></div>

  <h2>Getting Started</h2>
  <div class="steps">
    <div class="step">
      <div class="step-num">1</div>
      <div class="step-content">
        <h3>Review this guide and the videos</h3>
        <p>Watch the walkthroughs below to understand how the platform works and what the setup process looks like.</p>
      </div>
    </div>
    <div class="step">
      <div class="step-num">2</div>
      <div class="step-content">
        <h3>Set up your strategy</h3>
        <p>Create your strategy page, set your subscription price, and connect your NinjaTrader brokerage account using BrokerTransmit so your trades replicate automatically.</p>
      </div>
    </div>
    <div class="step">
      <div class="step-num">3</div>
      <div class="step-content">
        <h3>Shadow period</h3>
        <p>Trade normally while we validate execution together. No followers see your strategy during this phase. You decide when you're ready to go live.</p>
      </div>
    </div>
    <div class="step">
      <div class="step-num">4</div>
      <div class="step-content">
        <h3>Go live</h3>
        <p>Your strategy becomes visible to NinjaTrader traders on the Follow Trading platform. Subscribers can start following your trades.</p>
      </div>
    </div>
  </div>

  <div class="divider"></div>

  <h2>Video Walkthroughs</h2>
  <p>These short videos walk through the platform and setup process. We recommend watching them before getting started.</p>

  <div class="video-list">
    <a href="https://vimeo.com/1174509673/d1574f4b9f?share=copy&amp;fl=sv&amp;fe=ci" target="_blank" class="video-link">
      <div class="video-info">
        <span class="video-title">Starting Your First Strategy</span>
        <span class="video-desc">Create your strategy, set pricing, enter trades via the platform</span>
      </div>
      <span class="video-duration">~13 min</span>
    </a>
    <a href="https://vimeo.com/1174518432/8376fb86ec?share=copy&amp;fl=sv&amp;fe=ci" target="_blank" class="video-link">
      <div class="video-info">
        <span class="video-title">BrokerTransmit Setup</span>
        <span class="video-desc">Connect your brokerage account so your live trades replicate automatically</span>
      </div>
      <span class="video-duration">~4 min</span>
    </a>
    <a href="https://vimeo.com/1174797361/ebada2bef8?share=copy&amp;fl=sv&amp;fe=ci" target="_blank" class="video-link">
      <div class="video-info">
        <span class="video-title">How AutoTrade Works (Subscriber View)</span>
        <span class="video-desc">See what your followers experience when they subscribe and enable auto-trading</span>
      </div>
      <span class="video-duration">~9 min</span>
    </a>
  </div>

  <div class="divider"></div>

  <h2>Common Questions</h2>

  <div class="faq-item">
    <div class="faq-q">Can followers see my account size or positions?</div>
    <div class="faq-a">No. Your personal account balance and position sizes are never exposed. Followers see your strategy's track record and performance, not your brokerage account.</div>
  </div>

  <div class="faq-item">
    <div class="faq-q">Do I need to change how I trade?</div>
    <div class="faq-a">No. You trade in your own NinjaTrader brokerage account as you normally do. BrokerTransmit connects your account so trades replicate to the strategy automatically.</div>
  </div>

  <div class="faq-item">
    <div class="faq-q">What instruments are supported?</div>
    <div class="faq-a">Futures contracts traded through NinjaTrader brokerage accounts. The platform supports contract size variants (for example, ES and MES) so followers can choose the size that fits their account.</div>
  </div>

  <div class="faq-item">
    <div class="faq-q">Is there any cost to me as a strategy leader?</div>
    <div class="faq-a">Publishing your strategy on the NinjaTrader Follow Trading platform does not require a separate platform subscription. You earn subscription revenue from followers. Collective2 will walk you through the full details during setup.</div>
  </div>

  <div class="faq-item">
    <div class="faq-q">Am I locked in?</div>
    <div class="faq-a">No. There's no obligation. You can remove your strategy at any time.</div>
  </div>

  <div class="faq-item">
    <div class="faq-q">Who handles billing and subscriber payments?</div>
    <div class="faq-a">Collective2, our technology partner, is the merchant of record. They handle all subscriber billing, payments, refunds, and payouts to you.</div>
  </div>

  <div class="faq-item">
    <div class="faq-q">Who is Collective2?</div>
    <div class="faq-a">Collective2 is a registered CTA (Commodity Trading Advisor) that provides the auto-trading and strategy distribution technology behind our Follow Trading platform. The experience is NinjaTrader-branded, powered by Collective2's infrastructure.</div>
  </div>

  <div class="faq-item">
    <div class="faq-q">What if I have more questions?</div>
    <div class="faq-a">Reply to your invitation email and we'll get you answers. Once you're ready to set up your strategy, the Collective2 team will walk you through the platform, economics, and any technical questions.</div>
  </div>

  <div class="divider"></div>

  <div class="cta-section">
    <h2>Ready to Explore?</h2>
    <p>Visit the Follow Trading platform to see what it looks like. When you're ready, reply to your invitation email and we'll set you up with strategy manager access.</p>
    <a href="https://follow.ninjatrader.com/" target="_blank" class="cta-btn">Visit follow.ninjatrader.com</a>
    <p class="cta-note">You'll need an invitation to create a strategy. The link above lets you browse the platform.</p>
  </div>

  <div class="footer">
    NinjaTrader, LLC ("NT") is a software development company operating under NinjaTrader Group, LLC. NT owns and supports proprietary technology relating to and including the NinjaTrader and Tradovate trading platforms. This document is confidential and intended only for invited participants in the Follow Trading pilot program.<br><br>
    Questions? Reply to your invitation email or contact <a href="mailto:ali.goedecke@ninjatrader.com">ali.goedecke@ninjatrader.com</a>
  </div>

</div>


</body></html>

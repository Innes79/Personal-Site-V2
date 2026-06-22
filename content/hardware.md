---
title: "Hardware"
layout: "single"
---

<style>
/* =========================================
   1. HOME PAGE (Profile Mode) STYLES 
   ========================================= */
.profile_inner {
    transform: scale(1.5); 
    transform-origin: center;
    margin-top: 80px; 
}

.profile_inner h1 {
    font-size: 52px !important; 
    margin-bottom: 25px !important;
    letter-spacing: 1px;
}

.profile_inner .profile_description {
    font-size: 22px !important;
    line-height: 1.8; 
}

.social-icons a svg {
    height: 36px !important;
    width: 36px !important;
}

.social-icons a:hover {
    transform: scale(1.1);
    transition: 0.2s;
}

.social-icons a:active {
    transform: scale(0.9);
    transition: 0.1s;
}

/* =========================================
   2. HARDWARE PAGE STYLES (iPad & Desktop)
   ========================================= */
.post-header {
    text-align: center !important;
    margin-top: 40px !important; 
    margin-bottom: 40px !important;
}

.post-title {
    display: block !important;
    font-weight: 800 !important;
    text-transform: uppercase;
    font-size: 3.5rem !important; 
}

.pc-container {
    display: flex;
    justify-content: center;
    gap: 15px;
    flex-wrap: nowrap; 
    width: 100vw;
    position: relative;
    left: 50%;
    right: 50%;
    margin-left: -50vw;
    margin-right: -50vw;
    margin-bottom: 60px;
}

.pc-box {
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 20px;
    background: var(--entry);
    width: 300px; 
    box-shadow: 0 4px 15px rgba(0,0,0,0.3);
}

.pc-box h3 { 
    margin-top: 0; 
    text-align: center; 
    font-size: 1.4rem;
    margin-bottom: 15px;
    color: var(--primary);
}

.hw-table { width: 100%; border-collapse: collapse; }
.hw-table td { padding: 10px 5px; border-bottom: 1px solid #333; font-size: 0.85rem; }
.hw-table td:first-child { font-weight: bold; width: 35%; color: #888; text-transform: uppercase; font-size: 0.7rem; }

.gadget-container {
    display: flex;
    justify-content: center;
    gap: 80px; 
    width: 100%;
    margin-top: 30px;
    padding-bottom: 50px; 
}

.gadget-column { text-align: center; }
.gadget-column h3 { 
    border-bottom: 3px solid var(--primary); 
    display: inline-block; 
    padding-bottom: 8px;
    margin-bottom: 20px;
    font-size: 1.8rem;
}

.gadget-column ul { list-style: none; padding: 0; margin: 0; }
.gadget-column li { 
    padding: 10px 0; 
    border-bottom: 1px dashed #444; 
    width: 200px; 
    margin: 0 auto;
}

.section-label { 
    font-size: 2.2rem; 
    font-weight: bold; 
    text-align: center; 
    margin-bottom: 30px; 
    color: #eee;
}

/* =========================================
   3. PHONE ONLY FIX (Small Screens < 768px)
   ========================================= */
@media screen and (max-width: 768px) {
    .profile_inner {
        transform: scale(1.0); 
        margin-top: 40px; 
        padding: 0 20px;
    }
    .profile_inner h1 { font-size: 32px !important; }
    .social-icons a svg { height: 32px !important; width: 32px !important; }

    .post-title { font-size: 2.2rem !important; }
    
    .pc-container {
        flex-wrap: wrap !important; 
        width: 100% !important;
        margin-left: 0 !important;
        margin-right: 0 !important;
        left: 0 !important;
        right: 0 !important;
        gap: 25px;
    }

    .pc-box {
        width: 95% !important;
        max-width: 350px;
    }

    .gadget-container {
        flex-direction: column !important;
        gap: 40px;
    }
}
</style>

<div class="section-label">Computers</div>

<div class="pc-container">

<div class="pc-box">
<h3>Main PC</h3>
<table class="hw-table">
  <tr><td>CPU</td><td>Intel I5 14400F 4.7GHz</td></tr>
  <tr><td>GPU</td><td>NVIDIA GeForce RTX 4060 Ti</td></tr>
  <tr><td>RAM</td><td>6000MT/s 32GB DDR5</td></tr>
  <tr><td>Storage</td><td>1TB SSD | 500GB SSD</td></tr>
  <tr><td>Case</td><td>Corsair 3500X Mid-Tower</td></tr>
  <tr><td>OS</td><td>Windows 11 PRO</td></tr>
</table>
</div>

<div class="pc-box">
<h3>Innes-Lab</h3>
<table class="hw-table">
  <tr><td>CPU</td><td>Intel Pentium E5300 2.60GHz</td></tr>
  <tr><td>GPU</td><td>NVIDIA GeForce GT 220</td></tr>
  <tr><td>RAM</td><td>1600 MT/s 4GB DDR2</td></tr>
  <tr><td>Storage</td><td>3x 500GB HDD | 500GB SSD</td></tr>
  <tr><td>Case</td><td>Stock ASUS Case</td></tr>
  <tr><td>OS</td><td>Ubuntu Server 24.04.3 LTS</td></tr>
</table>
</div>

<div class="pc-box">
<h3>HUAWEI</h3>
<table class="hw-table">
  <tr><td>CPU</td><td>Intel i5-1135G7 4.20GHz</td></tr>
  <tr><td>GPU</td><td>Intel Iris XE</td></tr>
  <tr><td>RAM</td><td>2400 MT/s 8GB DDR4</td></tr>
  <tr><td>Storage</td><td>500GB SSD</td></tr>
  <tr><td>Case</td><td>Stock Huawei Case</td></tr>
  <tr><td>OS</td><td>Windows 11 | Endeavour OS Hyprland</td></tr>
</table>
</div>

</div>

<div class="section-label">Gadgets</div>

<div class="gadget-container">

<div class="gadget-column">
<h3>Peripherals</h3>
<ul>
  <li>Razer Viper v3 Hyperspeed</li>
  <li>SteelSeries Aerox 3 Wireless</li>
  <li>Mamabasnake M3</li>
  <li>Ajazz AK820 PRO</li>
  <li>UGreen 12000 mAH powerbank</li>
  <li>KTC H27T22</li>
  <li>AOC M2470SWH</li>
</ul>
</div>

<div class="gadget-column">
<h3>Items</h3>
<ul>
  <li>ESP-32 S3 LCD</li>
  <li>ESP-32 Wroom 32D</li>
  <li>5 Inch HDMI LCD</li>
  <li>Laser pointer</li>
  <li>Echo POP</li>
  <li>Apple Watch SE (Gen 2)</li>
  <li>Apple iPad A16 (128GB)</li>
  <li>Apple iPhone 13 mini</li>
</ul>
</div>

</div>

<div style="display: flex; justify-content: center; margin-top: 50px; padding-bottom: 50px;">
    <a href="/" style="
        padding: 12px 25px;
        background-color: var(--primary);
        color: var(--theme);
        text-decoration: none;
        border-radius: 8px;
        font-weight: bold;
        transition: transform 0.2s, opacity 0.2s;
        display: inline-block;
    " onmouseover="this.style.opacity='0.8'; this.style.transform='scale(1.05)'" 
       onmouseout="this.style.opacity='1'; this.style.transform='scale(1)'">
        ← Back to Home
    </a>
</div>

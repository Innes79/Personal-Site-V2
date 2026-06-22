---
title: "Links"
layout: "single"
---

<style>
/* 1. Page Header Spacing */
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

/* 2. Centralized Layout for Buttons */
.links-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px;
    width: 100%;
    max-width: 500px;
    margin: 0 auto;
    padding-bottom: 60px;
}

/* 3. Button Design matching your theme */
.link-btn {
    display: block;
    width: 100%;
    padding: 18px;
    text-align: center;
    background-color: var(--entry);
    color: var(--primary);
    border: 1px solid var(--border);
    border-radius: 12px;
    font-size: 1.2rem;
    font-weight: bold;
    text-decoration: none;
    box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    transition: transform 0.2s, background-color 0.2s, border-color 0.2s;
}

/* Hover/Active states for desktop and mobile */
.link-btn:hover {
    transform: scale(1.03);
    background-color: var(--tertiary);
    border-color: var(--primary);
}

.link-btn:active {
    transform: scale(0.98);
}
</style>

<div class="links-container">

    <a href="https://www.innes-gg.com/nexterm" target="_blank" class="link-btn">
        🖥️ SSH Server (Nexterm)
    </a>

    <a href="#" class="link-btn">
        🔗 Placeholder Link 2
    </a>

    <a href="#" class="link-btn">
        🔗 Placeholder Link 3
    </a>

    <a href="#" class="link-btn">
        🔗 Placeholder Link 4
    </a>

</div>

<div style="display: flex; justify-content: center; margin-top: 30px; padding-bottom: 50px;">
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

---
layout: default
title: Publications
permalink: /publications/
---

<div class="container">
    <h1 class="page-title">Publications</h1>
    <p class="subtitle">> Selected research works.</p>

    <div class="publication-list">
        <!-- Example Publication Entry -->
        <div class="publication-item">
            <div class="pub-year">2025</div>
            <div class="pub-content">
                <h3><a href="#">Title of the Paper: A Very Cool 3D Vision Method</a></h3>
                <div class="authors">
                    <strong>Fei Yu</strong>, Co-author Name, Advisor Name
                </div>
                <div class="venue">
                    Conference on Computer Vision and Pattern Recognition (CVPR), 2025
                </div>
                <div class="links">
                    <a href="#" class="link-btn">[PDF]</a>
                    <a href="#" class="link-btn">[Code]</a>
                    <a href="#" class="link-btn">[Project Page]</a>
                </div>
            </div>
        </div>

        <div class="publication-item">
            <div class="pub-year">2024</div>
            <div class="pub-content">
                <h3><a href="#">Another Interesting Research on Generative Models</a></h3>
                <div class="authors">
                    Co-author Name, <strong>Fei Yu</strong>, Advisor Name
                </div>
                <div class="venue">
                    International Conference on Computer Vision (ICCV), 2024
                </div>
                <div class="links">
                    <a href="#" class="link-btn">[PDF]</a>
                    <a href="#" class="link-btn">[Code]</a>
                </div>
            </div>
        </div>
    </div>
</div>

<style>
    .publication-list {
        margin-top: 3rem;
        border-left: 2px solid rgba(255, 255, 255, 0.1);
        padding-left: 2rem;
    }

    .publication-item {
        margin-bottom: 3rem;
        position: relative;
    }

    .publication-item::before {
        content: '';
        position: absolute;
        left: -2.4rem;
        top: 0.5rem;
        width: 10px;
        height: 10px;
        background: var(--bg-color);
        border: 2px solid var(--accent-color);
        border-radius: 50%;
    }

    .pub-year {
        font-family: var(--font-mono);
        color: var(--accent-color);
        font-size: 0.9rem;
        margin-bottom: 0.5rem;
    }

    .pub-content h3 {
        margin: 0 0 0.5rem 0;
        font-size: 1.3rem;
    }
    
    .pub-content h3 a {
        color: #fff;
    }
    
    .pub-content h3 a:hover {
        color: var(--accent-color);
        text-decoration: none;
    }

    .authors {
        color: #ccc;
        margin-bottom: 0.5rem;
    }

    .venue {
        font-style: italic;
        color: #888;
        margin-bottom: 1rem;
    }

    .link-btn {
        font-family: var(--font-mono);
        font-size: 0.8rem;
        margin-right: 10px;
        color: var(--secondary-color);
    }
    
    .link-btn:hover {
        color: var(--accent-color);
    }
</style>

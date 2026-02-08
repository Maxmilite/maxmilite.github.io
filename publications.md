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
            <div class="pub-teaser">
                <video autoplay muted loop playsinline>
                    <source src="/assets/teasers/2025-orbit.mp4" type="video/mp4">
                </video>
            </div>
            <div class="pub-details">
                <div class="pub-year">2025</div>
                <div class="pub-content">
                    <h3><a href="https://pku-vcl-geometry.github.io/Orbit2Ground/">From Orbit to Ground: Generative City Photogrammetry from Extreme Off-Nadir Satellite Images</a></h3>
                    <div class="authors">
                        <strong>Fei Yu</strong><sup>*</sup>, Yu Liu<sup>*</sup>, Luyang Tang, Mingchao Sun, Zengye Ge, Rui Bu, Yuchao Jin, Haisen Zhao, He Sun, Yangyan Li, Mu Xu, Wenzheng Chen, Baoquan Chen
                    </div>
                    <div class="venue">
                        Preprint.
                    </div>
                    <div class="links">
                        <a href="https://arxiv.org/pdf/2512.07527" class="link-btn">[PDF]</a>
                        <a href="https://pku-vcl-geometry.github.io/Orbit2Ground/" class="link-btn">[Project Page]</a>
                    </div>
                </div>
            </div>
        </div>

        <div class="publication-item">
            <div class="pub-teaser">
                <img src="/assets/teasers/2025-invblur.png" alt="Blur Recovery teaser">
            </div>
            <div class="pub-details">
                <div class="pub-year">2025</div>
                <div class="pub-content">
                    <h3><a href="https://maxmilite.github.io/rec-from-ultrafast-blur/">Recovering 3D Shapes from Ultra-Fast Motion-Blurred Images</a></h3>
                    <div class="authors">
                        <strong>Fei Yu</strong>, Shudan Guo, Shiqing Xin, Beibei Wang, Haisen Zhao, Wenzheng Chen
                    </div>
                    <div class="venue">
                        International Conference on 3D Vision (3DV), 2026
                    </div>
                    <div class="links">
                        <a href="https://maxmilite.github.io/rec-from-ultrafast-blur/static/paper.pdf" class="link-btn">[PDF]</a>
                        <a href="https://github.com/Maxmilite/rec-from-ultrafast-blur/" class="link-btn">[Code (Coming Soon)]</a>
                        <a href="https://maxmilite.github.io/rec-from-ultrafast-blur/" class="link-btn">[Project Page]</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<style>
    .publication-list {
        margin-top: 3rem;
    }

    .publication-item {
        margin-bottom: 4rem;
        display: flex;
        gap: 2rem;
        background: rgba(30, 41, 59, 0.3);
        backdrop-filter: blur(10px);
        -webkit-backdrop-filter: blur(10px);
        border: 1px solid rgba(59, 130, 246, 0.2);
        border-radius: 16px;
        padding: 1.5rem;
        transition: all 0.3s ease;
        align-items: stretch;
    }

    .publication-item:hover {
        transform: translateY(-5px);
        box-shadow: 0 8px 24px rgba(59, 130, 246, 0.3);
        border-color: var(--accent-color);
        background: rgba(30, 41, 59, 0.5);
    }

    @media (max-width: 1024px) {
        .publication-item {
            flex-direction: column;
            gap: 1rem;
        }
    }

    .pub-teaser {
        flex-shrink: 0;
        width: 30%;
        border-radius: 12px;
        overflow: hidden;
        background: rgba(15, 23, 42, 0.5);
        border: 1px solid rgba(59, 130, 246, 0.3);
        display: flex;
        align-items: center;
        justify-content: center;
    }

    @media (max-width: 1024px) {
        .pub-teaser {
            width: 100%;
            aspect-ratio: 16/9;
        }
    }

    .pub-teaser img, .pub-teaser video {
        width: 100%;
        height: 100%;
        object-fit: cover;
        transition: transform 0.3s ease;
        display: block;
    }

    .publication-item:hover .pub-teaser img,
    .publication-item:hover .pub-teaser video {
        transform: scale(1.05);
    }

    .pub-details {
        flex: 1;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }

    .pub-year {
        font-family: var(--font-mono);
        color: var(--accent-color);
        font-size: 0.9rem;
        margin-bottom: 0.5rem;
        font-weight: 600;
    }

    .pub-content h3 {
        margin: 0 0 0.75rem 0;
        font-size: 1.4rem;
        line-height: 1.4;
    }

    .pub-content h3 a {
        color: #fff;
        transition: color 0.3s ease;
    }

    .pub-content h3 a:hover {
        color: var(--accent-color);
        text-decoration: none;
    }

    .authors {
        color: #cbd5e1;
        margin-bottom: 0.75rem;
        font-size: 1rem;
        line-height: 1.6;
    }

    .venue {
        font-style: italic;
        color: #94a3b8;
        margin-bottom: 1.25rem;
        font-size: 0.95rem;
    }

    .links {
        margin-top: auto;
        display: flex;
        flex-wrap: wrap;
        gap: 8px;
    }

    .link-btn {
        font-family: var(--font-mono);
        font-size: 0.85rem;
        color: var(--secondary-color);
        padding: 6px 14px;
        border: 1px solid var(--secondary-color);
        border-radius: 6px;
        display: inline-block;
        transition: all 0.3s ease;
    }

    .link-btn:hover {
        color: #fff;
        background: var(--accent-color);
        border-color: var(--accent-color);
        text-decoration: none;
        box-shadow: 0 0 12px rgba(59, 130, 246, 0.4);
    }
</style>

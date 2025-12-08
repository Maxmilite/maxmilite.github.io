---
layout: default
title: Projects
permalink: /projects/
---

<div class="container">
    <h1 class="page-title">Projects & Open Source</h1>
    <p class="subtitle">> Code, tools, and experiments.</p>

    <div class="card-grid">
        <!-- Example Project -->
        <div class="card project-card">
            <div class="card-header">
                <h3>Project Name 1</h3>
                <div class="stars">
                    ★ 120
                </div>
            </div>
            <p>A short description of the project. Maybe it's a renderer or a utility library for 3D vision.</p>
            <div class="tech-stack">
                <span>Python</span>
                <span>PyTorch</span>
                <span>CUDA</span>
            </div>
            <div class="card-actions">
                <a href="#">View on GitHub</a>
            </div>
        </div>

        <div class="card project-card">
            <div class="card-header">
                <h3>Project Name 2</h3>
                <div class="stars">
                    ★ 45
                </div>
            </div>
            <p>Another cool project. This one might be a web tool or a visualization script.</p>
            <div class="tech-stack">
                <span>JavaScript</span>
                <span>WebGL</span>
            </div>
            <div class="card-actions">
                <a href="#">View on GitHub</a>
            </div>
        </div>
        
        <!-- Add more projects here -->
    </div>
</div>

<style>
    .project-card .card-header {
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
    }
    
    .project-card .stars {
        font-family: var(--font-mono);
        color: #ffd700;
        font-size: 0.9rem;
    }
    
    .tech-stack {
        margin: 1rem 0;
        display: flex;
        gap: 10px;
    }
    
    .tech-stack span {
        font-size: 0.75rem;
        font-family: var(--font-mono);
        color: #888;
        border: 1px solid #333;
        padding: 2px 6px;
        border-radius: 4px;
    }
    
    .card-actions {
        margin-top: auto;
        padding-top: 1rem;
        border-top: 1px solid rgba(255,255,255,0.05);
    }
    
    .card-actions a {
        font-family: var(--font-mono);
        font-size: 0.8rem;
    }
</style>

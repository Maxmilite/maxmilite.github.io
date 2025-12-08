---
layout: default
title: Blog
permalink: /blog/
---

<div class="container">
    <h1 class="page-title">Blog</h1>
    <p class="subtitle">> Thoughts, tutorials, and updates.</p>

    <div class="blog-list">
        {% for post in site.posts %}
        <article class="blog-post-item">
            <span class="post-date">{{ post.date | date: "%Y-%m-%d" }}</span>
            <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
            <div class="post-excerpt">
                {{ post.excerpt }}
            </div>
            <a href="{{ post.url | relative_url }}" class="read-more">Read More_</a>
        </article>
        {% endfor %}
    </div>
</div>

<style>
    .blog-post-item {
        margin-bottom: 3rem;
        padding-bottom: 2rem;
        border-bottom: 1px solid rgba(255, 255, 255, 0.05);
    }
    
    .post-date {
        font-family: var(--font-mono);
        color: var(--accent-color);
        font-size: 0.8rem;
        display: block;
        margin-bottom: 0.5rem;
    }
    
    .blog-post-item h2 {
        margin-top: 0;
        font-size: 1.5rem;
    }
    
    .blog-post-item h2 a {
        color: #fff;
    }
    
    .blog-post-item h2 a:hover {
        color: var(--accent-color);
        text-decoration: none;
    }
    
    .post-excerpt {
        color: #ccc;
        margin-bottom: 1rem;
    }
    
    .read-more {
        font-family: var(--font-mono);
        font-size: 0.9rem;
    }
</style>

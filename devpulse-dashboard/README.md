# DevPulse - SaaS for cloud infrastructure

DevPulse is a fictional company offering Software-as-a-Service (SaaS) solutions for cloud infrastructure.

# DevPulse User Stories

## Story 1

As an infrastructure engineer, I want to understand DevPulse's business value, use easy navigation links, and have a CTA.

## Story 2

As a DevOps lead, I want to understand DevPulse's main features (Latency tracking, Log aggregation, auto-remediation).

## Story 3

As an engineering manager, I want to analyze the 3 main service tiers DevPulse provides (Developer, Pro Cluster, Business Enterprise).

## Story 4

As a system architect, I need to enter the company's node count and compute requirements.

## Story 5

As a developer, I would like to be provisioned an API sandbox after filling out a registration form.

# DOM

index.html
<head>
<body>
<header class=“site-header”>
<div class=“header-logo”>
<img>
<nav class=“header-navbar” aria-label=“DevPulse navigation bar”>
<a href=“#features”>
<a href= “#tiers”>
<a href= “#register”>
<a class= “btn-primary”>
<main>
<section id=“hero” class=“hero-section”>
<div class="news-pill">
<h1 class=“hero-title”> (“Powerful and painless cloud and SaaS services.”)
<p class=“hero-caption”>
<a href=“#register” class=“btn-primary”> (“Get API access”)
<section id=“features” class=“section-area”>
<header=“section-header”>
<h2 class= “section-title”> (“Feel the pulse of your infrastructure”)
<p class= “section-caption”>
<div class=“features-grid”>
<article class=“feature-box”>
<h3 class=“feature-title”> (“Latency Tracking”)
<p class=“feature-caption”>
<img class=“feature-img”>
<article class=“feature-box”>
<h3 class=“feature-title”> (“Log Aggregation”)
<p class=“feature-caption”>
<img class=“feature-img”>
<article class=“feature-box”>
<h3 class=“feature-title”> (“Auto-Remediation”)
<p class=“feature-caption”>
<img class=“feature-img”>
<section id=“tiers” class=“section-area”>
<header=“section-header”>
<h2 class= “section-title”> (“From personal projects to enterprise systems, we handle it all.”)
<p class= “section-caption”>
<div class=“tier-grid”>
<article class=“tier-box”>
<h3 class=“tier-title”> (“Developer”)
<p class=“tier-caption”>
<ul class=“tier-features”>
<li>
<li>
<li>
<a href=“#register” class= “btn-primary”> (“Request API access”)
<article class=“tier-box popular”>
<div class="popular-pill">
<h3 class=“tier-title”> (“Pro Cluster”)
<p class=“tier-caption”>
<ul class=“tier-features”>
<li>
<li>
<li>
<a href=“#register” class= “btn-primary”> (“Request API access”)
<article class=“tier-box”>
<h3 class=“tier-title”> (“Enterprise Dedicated”)
<p class=“tier-caption”>
<ul class=“tier-features”>
<li>
<li>
<li>
<a href=“#register” class= “btn-primary”> (“Request API access”)
<section id=“section-area” class=“register-section”>
<header=“section-header”>
<h2 class=“section-title”> (“Claim your API Keys”)
<p class=“section-caption”>
<form class=“request-form”>
<div class=“form-group”>
<label for=“work-email” class=“form-label”> (“Work Email”)
<input type=“text” name=“workEmail” id=“wotk-email” class=“form-input” placeholder=“example@abc.com” required>
<div class=“form-group”>
<label for=“node-count” class=“form-label”> (“Number of Nodes”)
<input type=“number” name=“nodeCount” id=“node-count” class=“form-input” min= “50” max= “1000 step=“50” placeholder=“500” required>
<span class= input-range> (“Min: 50 – Max: 1000”)
<div class=“form-group”>
<label for=“throughput” class=“form-label”> (“Max Throughput (bps)”)
<input type=“number” name=“throughput” id=“throughput” class=“form-input” min= “1000” max= “10000 step=“500” placeholder=“5000” required>
<span class= input-range> (“Min: 1000 bps – Max: 10000 bps”)
<div class=“form-group”>
<label for=“tier-type” class=“form-label”> (“Tier Type”)
<select name=“tierType” id= “tier-type” class=“form-control”>
<option value=“developer”> (“Developer – $5 monthly”)
<option value=“pro”> (“Pro Cluster – $15 monthly”)
<option value=“enterprise”> (“Enterprise Dedicated – Custom pricing”)
<button type=“submit” class= “btn-primary> (“Get API Sandbox”)
<footer class= “site-footer”>
<p class= “footer-copyright” $copy;>
<nav class “footer-links” aria-label= “DevPulse footer links”>
<a href= “#hero”>
<a href=“#features”>
<a href=“#tiers”>

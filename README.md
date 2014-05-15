#Base Website Framework

Minimal front-end template built using Foundation 5 and made to work with IE8 (F3 fallback).

=====================

## Framework

- Foundation 5.2.2

## Style

- normalize.scss
- style.scss 

## Vendor Scripts

- jQuery v.2.1.1
- Modernizr v2.7.2

## Legacy

- Foundation 3.2.5
- JQuery v.1.9.0
- Modernizr v2.6.2

## Compiler
- Hammer 

## Folder Structure

<pre><code>
framework/ 
| 
|– assets/ 
|   |– css/						# Styles
|		|– components/			# F5 styles
|		|– legacy/				# F3 styles
|		|– normalize.scss			# Reset
|		|– style.scss				# Global styles and imports
|   |– img/						# Global elements
|		|– icons/					# favicons
|		|– ui/					# UI elements
|   |– js/						# Scripts 
|		|– foundation/			# F5 scripts
|		|– legacy/				# F3 scripts
|		|– vendor/				# Original vendor scripts
|		|– lib.js					# Used Foundation scripts
|		|– main.js				# Custom
|		|– vendor.js				# Compiled vendor scripts
| 
|– Built/ 						# Static site rendered by Hammer
|
|– includes/						# Template snippets
|   |– _icons.html/				# Favicons
|   |– _meta.html/				# Opengraph info 
|   |– _scripts-footer.html/		# Script links in footer
|   |– _scripts-head.html/		# Script links in header
|   |– _styles.html/				# CSS links
| 
|– media/ 						# Content assets
|   |– files/						# All files
|   |– images/					# All images
|   |– videos/					# All videos
| 
|– index.html/ 					# UI Toolkit
| 
|– template.html/ 				# Base page layout
</code></pre>
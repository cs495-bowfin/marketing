# How to Install/Setup

<!--
What needs to be on this page
- If someone wanted to deploy your application on their own environment, what should they do?  
- What software is needed?  (docker really shines here)
- What external resources are used (put any free/paid tier information here)
-->

## Installation Guide



## Required Software

Since all code editing is done on the cloud through WordPress, no software is required. This solution is optimal for this use case, since it allows non-technical customers to freely make simple modifications to the site without worry of breaking anything. However, the external Elementor extension has been added to the WordPress account to improve ease of use of editing for anyone who wishes to modify the site.

## External Resources

A variety of external resources have been used for this project. WordPress is a paid service that requires credentials from the project sponsor to access and modify. Similarly, Google Tag Manager requires credentials from the sponsor to access, but the free version of the service is used by the sponsor. The other tools (Elementor, Jupyter Book, GitHub) are free services used.

### WordPress



### Elementor



### Google Tag Manager

<a href="https://marketingplatform.google.com/about/tag-manager/" target="_blank">Google Tag Manager (GTM)</a> is used to manage the user tracking for the Beechnut Kennels Site. The account for 

### Jupyter Book

This website, which houses the project website requirements as well as the documentation, is built on <a href="https://github.com/jupyter-book/jupyter-book" target="_blank">Jupyter Book</a>. This tool, which is built on <a href="https://github.com/sphinx-doc/sphinx" target="_blank">Spinx</a>, allows us to render Markdown files to HTML documentation using YAML configuration files. Jupyter Book is licensed under <a href="https://github.com/jupyter-book/jupyter-book?tab=BSD-3-Clause-1-ov-file" target="_blank">BSD-3-Clause</a> allowing for open use.

The config files defining this Jupyter Book are found in <a href="https://github.com/cs495-bowfin/marketing/blob/main/_config.yml" target="_blank">_config.yml</a> and <a href="https://github.com/cs495-bowfin/marketing/blob/main/_toc.yml" target="_blank">_toc.yml</a>. Each Markdown page and image used for the site is found in the <a href="https://github.com/cs495-bowfin/marketing/tree/main/pweb" target="_blank">pweb</a> directory of our GitHub repository.

### GitHub Actions

GitHub Actions are used to automatically recompile the Jupyter Book site when modifications are made to the project repository. This action is defined in <a href="https://github.com/cs495-bowfin/marketing/blob/main/.github/workflows/main.yml" target="_blank">.github/workflows/main.yml</a>.

For more information on using GitHub Actions, please see the <a href="https://docs.github.com/en/actions" target="_blank">GitHub Actions documentation</a>. All usage for this project conforms to the <a href="https://docs.github.com/en/site-policy/github-terms/github-terms-of-service" target="_blank">GitHub Terms of Service</a>.

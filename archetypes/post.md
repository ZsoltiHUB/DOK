---
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
date: {{ .Date }}
# weight: 1 # Post order weight (lower numbers appear first)
# aliases: ["/first"] # Alternative URLs that redirect to this post
tags: ["tag1", "tag2"] # Tags for categorization and filtering
categories: ["category"] # Categories for broader classification
author: "Kis Zsolt" # Post author name
# author: ["Author1", "Author2"] # Multiple authors (uncomment if needed)

# Table of Contents settings
showToc: true # Show table of contents
TocOpen: false # Whether TOC is expanded by default

# Post status and visibility
draft: false # Set to true to hide post from public site
hidemeta: false # Hide post metadata (date, author, etc.)
comments: false # Enable/disable comments (if comment system is configured)

# SEO and meta information
description: "Brief description of the post content for SEO and social sharing."
canonicalURL: "https://kukievo.hu/posts/{{ .File.ContentBaseName }}/" # Canonical URL for SEO
keywords: ["keyword1", "keyword2"] # SEO keywords

# Code highlighting settings
disableHLJS: false # Disable Hugo's built-in syntax highlighting
# disableHLJS: true # Uncomment to disable if using external highlighter

# Social sharing and discovery
disableShare: false # Hide social share buttons (controlled by site config ShowShareButtons)
searchHidden: false # Hide from site search results
# searchHidden: true # Uncomment to exclude from search

# Reading experience settings
ShowReadingTime: true # Display estimated reading time
ShowBreadCrumbs: true # Show breadcrumb navigation
ShowPostNavLinks: true # Show previous/next post navigation
ShowWordCount: true # Display word count
ShowRssButtonInSectionTermList: true # Show RSS button in lists
UseHugoToc: true # Use Hugo's built-in table of contents
hideSummary: false # Hide post summary/excerpt in lists

# Cover image configuration
cover:
    image: "/images/post-cover.jpg" # Cover image path (relative to static folder)
    alt: "Cover image description" # Alternative text for accessibility
    caption: "Image caption displayed under cover" # Caption text below image
    relative: false # Set to true when using page bundles with local images
    hidden: true # Hide cover image on single post page (show only in lists)
    # hidden: false # Uncomment to show cover on single post page too

# Post editing configuration (for GitHub integration)
editPost:
    URL: "https://github.com/ZsoltiHUB/DOK/" # Base URL for edit links
    Text: "Javaslat változtatásra" # Text for edit link button
    appendFilePath: true # Append file path to edit URL for direct GitHub editing
---

# {{ replace .File.ContentBaseName "-" " " | title }}

Ide írd a poszt tartalmát...

## Alcím

További tartalom...

### Kisebb alcím

- Lista elem 1
- Lista elem 2
- Lista elem 3

**Fontos:** Ez egy példa poszt sablon.

---

*{{ .Site.Params.author }} - {{ dateFormat "2006. január 2." .Date }}*

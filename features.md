# Sitemapy Features

## Core Features

### Sitemap Analysis

- Fetch and analyze sitemaps
- View status codes and page counts
- Display sitemap index hierarchy
- Automatically detect sitemap URLs from robots.txt

### Directory View

- Browse sitemap pages in a structured directory view
- View page counts by directory
- Example structure:

```
/articles (150 pages)
/topics (75 pages)
    /engineering (20 pages)
        /how-to-migrate-from-next-to-vite
        /how-to-open-source-my-project
        ...
/authors
  /kevin
  /...
```

## Monitoring & Alerts

### Automated Crawling

- Schedule regular crawls (daily, monthly)
- Track changes between crawls
- Monitor page modifications:
  - New pages added
  - Existing pages updated
  - Pages removed

#### Enterprise Features

- Detailed change tracking
  - page level
  - store sitemap crawls in JSON (S3) to be able to do advanced monitoring

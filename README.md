# Recipes Offline

https://www.justtherecipe.com/

[Recipe Scrapers](https://github.com/hhursev/recipe-scrapers)

- [x] come up with a recipe scraping strategy
- [x] cap at 100 recipes and play around with different strategies
- [x] generalize recipe walker algorithm
- [ ] find schemas for the websites in websites.json

- [ ] get all recipe links for allrecipes.com
- [ ] figure out how long it will take to scrape
- [ ] scrape recipes
- [ ] come up with a filesystem schema with checkpoints

rules:
- look for recipe prefix (this is faster since we don't need to load the recipe link)
- look for yoast-schema-graph type="application/ld+json"

